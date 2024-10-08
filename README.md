# ClusterChatServer
A cluster chat server based on muduo, redis, which can work on nginx, tcp environment


####编译和运行

**需要nginx tcp负载均衡模块**
**需要运行在Linux环境**

>1、编译
```shell
// 直接运行autobuild.sh文件
./autobuild.sh
```

>2、打开服务器
```shell
cd bin
./ChatServer xxx.xxx.xxx.xxx xxxx // ip和port，在nginx配置文件中进行配置
```

>3、打开客户端
```shell
// 打开一个新的客户端
cd bin
./ChatClient xxx.xxx.xxx.xxx xxxx // ip和nginx端口号，默认8000
```
