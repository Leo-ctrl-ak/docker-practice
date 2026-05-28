# DVWA Docker 部署详细指南

## 1. 环境准备

- Docker 已安装并能正常运行 (`docker run hello-world`)
- 用户已加入 `docker` 组（解决权限问题）

## 2. 拉取镜像

```bash
# 从 Docker Hub 拉取 DVWA 镜像
docker pull vulnerables/web-dvwa