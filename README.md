# Linux-Docker Examples
### 2019.11.16-01 - Virtual Machine
下载最新版VirtualBox  
创建一个1GB内存+动态15GB磁盘(实际不会占这么大)，名为CentOS7的虚拟机。注意，放在合适的位置  
虚拟机网络，桥接模式。桥接，默认的网络地址转换(NAT)的区别？ 
桥接，可以最真实模拟远程服务器  

https://opsx.alibaba.com/mirror  
下载CentOS7.1908，DVD iso版，4.34GB  
在虚拟机光驱，引入CentOS镜像   
从虚拟机切出鼠标/键盘的控制的快捷键？  

运行虚拟机，进入centos安装模式    
打开网络功能，默认的自动分配IP  
安装位置，无需分区  
安装minimal版，后续软件包可以再添加  
安装过程中，设置root账号密码，创建一个普通用户账号  
安装时，查找资料了解root/普通用户，Linux系统操作权限管理    
安装完毕，光驱卸载iso，重启  

### 2019.11.16-02 - CentOS
初学者可以直接以root账号登录  
因为网络使用的是桥接模式，电脑必须连接一个路由节点，比如手机热点，才能与虚拟机互交。为什么？   
ping通百度  
停止执行的操作快捷键？  
自动补全快捷键？  
查看自动分配的ipv4地址   

### 2019.11.16-03 - SSH
在win10上，安装OpenSSH Server  
Win7安装Bitvise SSH Client或其他SSH客户端。什么是SSH？   
通过控制台，虚拟机ip，以root登录远程服务器  
为什么通过ssh连接服务器，而不直接在虚拟机中操作？   

如果能够正确进入服务器，则可以在virtualbox中为虚拟机创建一个系统快照作为基础镜像，
后续操作出问题，可以回滚到当前版本。当入删了虚拟机重来也很方便  

### 2019.11.16-04 - Don’t Be Scared of the Terminal
基本命令  
清屏，进入/退出目录，根目录，home目录，创建/删除目录，查看系统版本，系统内核，cpu/内存占用，磁盘占用。要使用自动补全  
