# 记录日常学习和工作中有关Docker的知识

<p align="center">
  <a>
   <img alt="Framework" src="../ECHILS.PNG">
  </a>
</p>

## CentOS 7安装Docker
1、关闭防火墙

`systemctl stop firewalld && systemctl disable firewalld`

2、关闭SELINUX

`sed -i 's/SELINUX=enforcing/SELINUX=disabled/g' /etc/selinux/config`

3、安装工具

`yum install -y yum-utils device-mapper-persistent-data lvm2`

<p align="center">
  <a>
   <img alt="Framework" src="./source/1.png">
  </a>
</p>