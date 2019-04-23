# 个人邮箱搭建

## Email原理

### DNS - MX记录

电子邮件用一种特殊的DNS记录称为**MX记录（Mail Exchange）**。

如果你发一封邮件给`1234@qq.com`，发送方服务器会对`@`分隔符后面的`http://qq.com`做一个**MX记录查询**。DNS返回的查询结果举个例子是`receive.qq.com`，发送方服务器就会连上`http://receive.qq.com`的特定端口（如25）开始传输邮件。

自己可以很容易的做MX查询，打开一个命令行，输入`nslookup -qt=mx http://qq.com`回车就行。



  


