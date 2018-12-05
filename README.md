# AutoMigrate
> 一款适用于laravel和lumen迁移文件自动同步的Composer插件<br>Composer plugin for auto run migration files with laravel and lumen





补充：
MacOs上因无法使用--full-time修饰命令将导致如下错误提示：
``` rubi
ls: illegal option -- -
usage: ls [-ABCFGHLOPRSTUWabcdefghiklmnopqrstuwx1] [file ...]
```

如果你在OS X上，你可以安装coreutils来获得GNU版本的ls ，其中包括--time-style选项：
```
brew install coreutils 
```
请注意，默认情况下安装的实用程序将以g为前缀，所以ls变成gls 。

完成这些操作之后，将已安装在.git/hook/post-merge中代码处 ls 改为 gls 即可。
