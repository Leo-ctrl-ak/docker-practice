# Docker Practice 项目

本项目用于学习和练习 Docker 部署 Web 应用，以 DVWA（Damn Vulnerable Web Application）作为示例。

## 项目简介

- 通过 Docker 一键部署 DVWA 靶场环境
- 使用 `vulnerables/web-dvwa` 镜像
- 包含完整的部署步骤文档

## 目录结构
├── README.md
├── dvwa-deploy.md # 详细部署文档
└── screenshots/ # 操作截图
├── 00-docker-verify.png
├── 01-docker-pull.png
├── 02-docker-run.png
├── 03-dvwa-login.png
└── 04-security-low.png

## 环境信息

- 操作系统：Kali Linux (VM)
- Docker 版本：29.5.2
- DVWA 镜像：vulnerables/web-dvwa:latest

## 快速开始

1. 拉取镜像
2. 运行容器
3. 访问 `http://localhost:8080`
4. 登录并设置 Security Level 为 Low

> 详细步骤请查看 [dvwa-deploy.md](dvwa-deploy.md)
> 
