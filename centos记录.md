### Centos 7 关闭报警音
#### 关闭命令行报警音
`vi /etc/inputrc `

将第二行 set bell-style none 前的#号去掉，重启生效 （centos 7）

#### 关闭vi编辑器报警音
root用户`vi ~/.bashrc` 写入 setterm -blength 0 重启生效（centos 7）

### 安装虚拟机时忘记开启网络
![开启网络](https://i.loli.net/2021/09/30/h15cDuyRBeXK4HA.png)

`systemctl restart network`

### 无线网络虚拟机桥接没有网络
![](https://i.loli.net/2021/09/30/rbmfUY6qyVzHNi7.png)

更改桥接设备，不要选择自动
连上网线之后，再改为自动