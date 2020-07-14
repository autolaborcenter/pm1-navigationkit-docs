# 连接设备

## 远程连接

得到机器人的远程连接地址后，可使用远程桌面软件 或 SSH ，进行远程连接。

### 远程桌面

远程桌面使用的是 NoMachine，这是一个多平台的远程桌面访问工具，图形化操作界面，支持 Windows/Mac/Linux，同一时间仅限 1 人连接（可理解为teamviewer）。

#### 下载

[NoMachine](https://www.nomachine.com/download)

#### 安装

![](imgs/network-16.png)
![](imgs/network-17.png)

####　启动

打开 NoMachine 软件，会弹出引导页面，点击 `continue`

![](imgs/network-18.png)

##### 内网访问

NoMachine 会将同一局域网中所有设备的列出，与机器人在同一网络时，可直接看到机器人设备，右键点击设置图标，选择 `Edit Connection` 按钮。

![](imgs/network-19.png)

默认IP 为 `192.168.188.1`，端口为4000。如设置中设备与下图不符，请对应修改，否则则无法连接。

![](imgs/network-20.png)

点击 `OK` `continue`，开始连接

![](imgs/network-21.png)

输入 

用户名： autolabor

密码： autolabor

![](imgs/network-22.png)

点击 `OK`，成功连接到机器人上。此时桌面上弹出了一个对话框，是设置远程桌面软件，点击`OK`。

![](imgs/network-24.png)

***

##### 外网访问

拿到上一步得到的外网访问-远程桌面地址：`cloud.autolabor.com.cn:40011`












