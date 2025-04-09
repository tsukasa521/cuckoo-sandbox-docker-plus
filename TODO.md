# Todo list
- dockerfile中没有安装tcpdump，这个是用来检测网络流量变化的

# 使用步骤

## 定位到根目录

```bash
# 发起服务
docker-compose -p kk up -d
# 关闭服务
docker-compose -p kk down

```
## 启动 VirtualBox Web Service 服务

安装的VirtualBox版本是6.1.50
```bash
.\VBoxWebSrv.exe --host 0.0.0.0 -v
```

