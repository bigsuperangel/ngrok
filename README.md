### 使用方法

- 修改ngrok.cfg相应参数
- 先到www.ngrok.cc平台注册账号，添加需要绑定的信息
- subdomain或者remote_port重复可能会导致失败。
- 如果启动失败有可能是别人已经使用请更换再试。

#### Windows启动方式
```
1、双击 启动服务.bat
2、输入服务名称
3、启动单个服务输入 sunny
4、启动多个服务的时候输入 sunny web web1 ssh
```

#### linux启动方式
```
1、进入到ngrok和ngrok.cfg所在的目录
2、启动单个服务 ./ngrok -config ngrok.cfg start sunny
3、启动多个服务 ./ngrok -config ngrok.cfg start sunny web web1 ssh
4、后台运行可以使用 setsid ./ngrok -config ngrok.cfg start sunny
5、后台运行 ./start.sh 
```


