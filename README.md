# ZMConfuse
ZMConfuse 是一个命令行脚本。用于对使用Objective-C为开发语言的应用进行代码混淆。混淆的内容包括文件名、类名、协议名、函数名。
混淆实际是对上述内容的关键字提取之后进行md5加密，使得工程的可读性降低，已达到增加应用安全性的目的。

欢迎联系交流
Email:zm53373581@163.com
QQGroup:175070221

混淆效果图：
![image](https://github.com/kongcup/ZMConfuse/raw/master/confuse.png)


1. 终端cd 到zmconfuse.sh文件 所在的文件夹内。
2. 再把你的工程文件拷贝到此文件夹内。
3. 打开zmconfuse.sh文件，把 ROOTFOLDER="shakefun" 的shakefun替换成你的工程文件名。
4. 添加排除的第三方库等。保存修改。
5. 直接把zmconfuse.sh文件，拖到终端内，ENTER。
