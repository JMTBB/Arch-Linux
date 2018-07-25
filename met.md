 遇到的一些问题
=========

----------------
## 2018/7/25 ##
使用`nano /etc/pacman.d/mirrorlist`修改源，尝试添加一些国内源。

任然出现`failed retrieving file`的问题

[Arch提供的mirror list](https://www.archlinux.org/mirrors/ "以country排序方便寻找")

-----------------
## 2018/7/23 ##

`error: falied retrieving 'binutils-2.30-5-x86_64.tar.xz' form xxxxxx`

**binutils-2.30-5-x86_64.tar.xz**无法安装

![错误截图](https://github.com/JMTBB/Arch-Linux/blob/master/screenshots/Snipaste_2018-07-23_19-51-29.png "已更改mirrorlist")

*7/23终止，还没解决这个问题，试试centos*

---------------------
## 2018/7/1x ##

### 无法联网

[archlinux无法联网解决方法](https://blog.csdn.net/killzero/article/details/8857224)

可能原因 ：

未执行 [ArchLinux安装图文教程](https://blog.csdn.net/r8l8q8/article/details/76516523) 中的第**11**步（网络配置）

### 首次重启登陆

未设置用户名时，首次登陆的用户名为` root `

密码为使用` passwd `所设定的密码

***此次虚拟机密码为 7890***

**安装kde过程出现空间不足的问题，于是`删除虚拟机`重新安装**
