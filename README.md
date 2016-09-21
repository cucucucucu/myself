#info
* 姓  名：胡小岸       性  别：男                
* 学  历：本科         专  业：微电子科学与工程           
* 电子邮件：401538557@qq.com
* 联系电话：18408280613

## 一，在校课程设计项目，基于DDS的波形发生器：
* 个人负责模块描述：
	AD9833驱动程序和串口中断处理。
* 项目描述：
	该系统以低功耗为出发点，用超低功耗单片机STC15F2K60S2作为主控芯片,选用低功耗芯片AD9833为信号产生芯片，采用了数字电位器MAX5487和高速运放THS3001实现幅度控制，使用触摸屏进行显示，通过串口与上位机进行通讯方便进行控制。且使用DDS器件，具有体积很小，电路简单的优点，整个系统可以做得很小，甚至可以作为手持设备使用，这就正好满足了当前技术的需要。
* 代码链接https://github.com/cucucucucu/myself/blob/master/dds.md

## 二， Linux下TCP多人在线聊天室项目：
* 个人负责描述：
	独立完成。
* 项目描述：
	该项目基于Linux下使用，实现多用户群体聊天功能，每个人所发送的消息其他用户均可以收到。用户可以随意的加入或退出（推出以字符串“bye”实现），服务器也可以进行关闭。
* 代码链接：https://github.com/cucucucucu/myself/blob/master/tcp_chat

## 三，linux下命令行的在线英语小词典项目：
* 个人负责描述：
	全部独立完成。
* 项目描述：
	该项目基于Linux下C语言编写，使用TCP协议，采用sqlite3作数据库，分客户端、服务器端两部分。用sqlite3操作命令建立数据库。客户端注册、登陆，服务器端检验合法性。 登陆成功后可以查询单词，查询历史记录，返回注册登陆界面，可以退出。
* 代码链接：https://github.com/cucucucucu/myself/blob/master/dictionary

## 四，Andriod环境下实现简易App项目：
 * 个人负责描述：
 	全部独立完成。
 * 项目描述:
	该App具有图片查看器，简易计算器，音乐媒体播放器以及跑马灯。
	图片查看器可以实现图片滑动查看以及缩放效果，还有水波纹功能实现。简易计算器可进行12位十进制简单计算，音乐播放器可以读取手机内部音乐，后台播放音乐，监听系统广播等功能。
* 代码链接：https://github.com/cucucucucu/myself/blob/master/Andriod_App

## 五，基于Exynos-4412开发板的嵌入式系统移植以及PWM,LCD驱动开发：
* 个人负责描述：
	参照Exynos手册与华清远见驱动实验手册独立完成。
* 项目介绍：
	该项目包括u-boot移植，kernel的裁剪和移植，PWM，LCD，串口驱动均是字符驱动， 设备驱动中引入platform 概念，隔离BSP和驱动。在BSP中定义platform设备和设备使用的资源、设备的具体匹配信息，而在驱动中，只需要通过API去获取资源和数据，做到了板相关代码和驱动代码的分离，使得驱动具有更好的可扩展性和跨平台性。
* 相关Exynos手册请参照CSDN博客：http://blog.csdn.net/zqixiao_09?viewmode=contents	



