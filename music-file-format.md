# 关于音乐格式整理

[http://bbs.big-cd.com/simple/?t21360.html](http://bbs.big-cd.com/simple/?t21360.html) 论整轨+CUE的优越性（关于音质的部分论点存疑



最近重新整理无损曲库，在PC端用foobar 2000进行整理+播放。

遇到的问题是，从网上搜集到的资源组织格式不一。主要是整轨+cue、分轨+cue、仅分轨这几类。考虑用cue文件做foobar和本地曲库的接口。

但是foobar对于cue文件的格式有严格的要求（见[Cue sheet wiki](http://wiki.hydrogenaud.io/index.php?title=Cuesheet#Multiple_files_with_gaps_.28Noncompliant.29)）。然而我有很多noncomplaint的cue，这些cue文件完整保存了gap信息，有保留价值（不过我直接保存分轨文件本身的话也没什么损失，只要gap信息也保存在分轨文件中）。但是为了兼容foobar，拟重新生成“**Multiple files with corrected gaps”**格式的cue。

