# v2ray_client
## 简介

一个基于Web的v2ray客户端控制面板

![1](https://github.com/NoOne-hub/v2ray_client/blob/master/images/1.png
)
![2](https://github.com/NoOne-hub/v2ray_client/blob/master/images/2.png
)
![3](https://github.com/NoOne-hub/v2ray_client/blob/master/images/3.png
)
![4](https://github.com/NoOne-hub/v2ray_client/blob/master/images/4.png
)

这个项目借鉴了很多人的思想，有雨落无声大佬的v2ray.fun作为基础，还有github上很多开源项目的帮助，第一次做web项目，耗费时间一星期左右吧，基础功能试用成了，具体bug不清楚，待测试

## 使用方法
- **注意：root权限下运行，不然无法修改v2ray配置**
- **注意：root权限下运行，不然无法修改v2ray配置**
- **注意：root权限下运行，不然无法修改v2ray配置**


这边是个测试新安装脚本install_test.sh弄的分支。



1. 运行 sudo ./install_test.sh
2. 按照脚本操作后，将会部署到后台
3. 部署完成后访问http://127.0.0.1:8000


## 启动停止方法
1. 启动： supervisorctl -c config/supervisord.conf start v2rayClient
2. 停止: supervisortctl -c config/supervisord.conf stop v2rayClient




## 配置方法

具体写入的日志和配置文件在config.py里自行修改

