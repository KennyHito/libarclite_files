iOS 低版本升级Xcode14.3后会报错：File not found: .../lib/arc/libarclite_iphoneos.a

解决方法：

1、下载arc文件，或者拷贝低版本Xcode的arc源文件。

2、进入目录/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib下,创建arc文件夹,并将下载的所有.a文件复制到文件夹中。

3、clean一下,之后重新运行Xcode即可。
