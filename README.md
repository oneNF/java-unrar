# java-unrar

RAR压缩算法是不公开的，所以这方面的开源项目不多

幸好有一个叫unrar的开源项目支持RAR的解压，但不能压缩RAR文件

不过，直接使用unrar却不能支持带密码的RAR文件解压，经过多方查找，终于在Google Code上面找到一个支持密码的unrar版本，下载地址：http://code.google.com/p/java-unrar/

该项目依赖Jar包：

commons-logging.jar  比较常用，可以到Apache官网下载

gnu-crypto.jar  可以在http://www.gnu.org/software/gnu-crypto/下载
