# 双系统配置note

冷启动前插入Ubuntu安装盘后，EasyBCD会在启动时自动识别到安装盘，很方便。

进入安装盘后，建议选择"Try ..."。由于我的笔记本装了Nvidia卡，需要在启动前按`e`修改grub配置：将`quiet splash`修改为`quiet splash nomodeset`。

进入后，由于分辨率与显示器不一致，会遇到无法显示完整窗口的问题，可通过按`super`或者`alt`加鼠标拖动的方式解决。

之后正常安装即可，安装模式我选择了最小模式。  
注意这里选最小模式可能是之后electron-ssr/shadowsocks-qt不能直接正常运行的原因（猜测是缺少依赖库？）。具体表现为，系统代理配置为automatic模式，configuration URL = http://127.0.0.1:2333/proxy.pac，在firefox下试图走代理显示`Proxy Refused Connection`。  
但在我装了一些常用网络工具（及其依赖库）+重启之后，莫名其妙地恢复正常了（。

在EasyBCD环境下，Linux的boot并不是开机默认的引导项。在安装Linux时把开机引导项配置为/boot所在分区即可！（为了防止误操作留个mark）。

安装结束后启动系统时，仍然需要修改`quiet splash nomodeset`。将N卡切换到第三方后就不再需要该操作了，而且分辨率会恢复正常。  
但此时会遇到屏幕显示tearing的问题（无法垂直同步）。通过[这里](https://www.cmscritic.com/stop-screen-tearing-with-optimus-laptops-using-nvidia-drivers-in-linux/)的方法可以解决：

```bash
sudo nano /etc/modprobe.d/zz-nvidia-modeset.conf
```

然后添加

```text
options nvidia_375_drm modeset=1
```

保存后更新配置

```bash
sudo update-initramfs -u
```

重启即可。（重启可能会先黑屏一次orz，再次重启即可。）

