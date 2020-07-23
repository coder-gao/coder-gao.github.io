# network is unreachable
* 虚拟网络编辑器还原
* 手动设置DNS
	```
在/etc/resolvconf/resolv.conf.d/目录下一般情况下这个目录下有base和head两个文件
vim /etc/resolvconf/resolv.conf.d/base
nameserver 8.8.8.8
保存后执行
resolvconf -u

https://blog.csdn.net/YLMF_yyz/java/article/details/46646449
```
* 使用NAT连接, 以便使用 wireshark 进行抓包