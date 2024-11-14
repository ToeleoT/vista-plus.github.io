# Docker安装

docker pull ubuntu:22.04

# 启动环境

docker run -it ubuntu:22.04 /bin/bash

## REF website

https://www.runoob.com/docker/docker-container-usage.html

# 安装前都需要apt update

## 安装python3并指定为python3命令

https://linux.cn/article-15230-1.html

安装pip：apt install python3-pip

## 安装GCC

```bash
apt install build-essential
```

```
docker run -it nvidia/cuda:11.8.0-runtime-ubuntu22.04
```