# v2ray_client
## 这边是个测试安装脚本install_test.sh弄的分支.

一个基于Web的v2ray客户端控制面板

![1](https://github.com/NoOne-hub/v2ray_client/blob/master/images/1.png
)





### 一键安装脚本，会自动安装环境，两个都一样的，下载方式不同而已.

```
wget -c https://github.com/NoOne-hub/v2ray_client/archive/master.tar.gz && tar xzf master.tar.gz && cd v2ray_client-master && ./install_test.sh
```

```
git clone https://github.com/NoOne-hub/v2ray_client.git && cd /v2ray_client && ./install_test.sh
```




## 启动停止方法
1. 启动： `supervisorctl -c config/supervisord.conf start v2rayClient`
2. 停止： `supervisorctl -c config/supervisord.conf stop v2rayClient`
