# Self-hosted mirrors

> Helps own your multi mirrors quickly.

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
docker-compose up -d
```

## License
This repo is under the MIT license. See the [LICENSE](/LICENSE) file for details.