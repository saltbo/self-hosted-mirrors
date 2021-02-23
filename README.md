# Self-hosted mirrors

![GitHub repo size](https://img.shields.io/github/repo-size/saltbo/self-hosted-mirrors)
[![License](https://img.shields.io/github/license/saltbo/self-hosted-mirrors.svg)](https://github.com/saltbo/self-hosted-mirrors/blob/master/LICENSE)

## Support Mirrors

- Go Module
- Npm Package
- Docker Registry

## Required

- Docker
- Docker Compose

## Quick start

1. 准备一个域名和一台国外的服务器
2. 将准备好的域名解析到该服务器
3. 确保防火墙放行80和443端口
4. 克隆本仓库，执行`docker-compose up -d`启动本项目即可

```bash
git clone https://github.com/saltbo/self-hosted-mirrors.git
cd self-hosted-mirrors
cp registry/config.example.yml registry/config.yml
vi registry/config.yml  #根据注释修改相关内容
docker-compose up -d
```

## License
This repo is under the MIT license. See the [LICENSE](/LICENSE) file for details.
