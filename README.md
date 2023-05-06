# xray配置文件（gRPC+vless fallback everything）
使用Docker-compose启动xray grpc+vless服务

## 安装步骤
### 一、创建目录
```shell
$ mkdir /etc/xray
$ mkdir /etc/caddy
```
### 二、写配置文件
1. 将`config`目录下的`config.json`和`config1.json`复制到`/etc/xray`中，根据需要修改`config.json`和`config1.json`
2. 将`xray_grpc`目录下的`Caddyfile`复制到`/etc/caddy`中，并根据需要修改文件
3. 将`docker-compose.yml`复制到指定目录下，并根据需要做出修改
### 三、启动服务
``` bash
$ docker compose up -d
```
