# repo-backend
postgresql 安装教程：
https://blog.csdn.net/rudy5348/article/details/79299162


# 此教程没有提到，远程连接数据库需要关闭防火墙
## 查看防火墙状态：
firewall-cmd --state
## 关闭防火墙：
systemctl stop firewalld.service
## 禁止防火墙开机启动：
systemctl disable firewalld.service 
