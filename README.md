# TG开车

使用Nodejs简单实现TG开车的功能，支持群组和个人开车。

主人将TG中的视频（或自行上传的视频）发送给机器人，机器人即可收录该视频ID到数据库中。

/kc是开车命令，默认十分钟一发车。/zt是暂停命令，会停止发车。

## 系统需要安装模块

1、安装node-telegram-bot-api模块

npm install node-telegram-bot-api

2、安装mysql模块

npm install mysql

## 修改配置信息

导入datas.sql文件到数据库中，自行修改kc.js或kc2.js中机器人的API TOKEN和数据库信息。

## 运行和命令

安装到Nodejs、所需模块和导入sql文件后，在kc.js和kc2.js所在目录下，输入node kc.js/kc2.js即可运行。

/kc是开车命令，默认十分钟一发车。/zt是暂停命令，会停止发车。
