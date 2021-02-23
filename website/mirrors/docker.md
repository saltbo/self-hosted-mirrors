## Docker Registry Mirror

## 简介
Docker镜像加速器，代理并缓存Docker镜像。你可以利用该代理来避免DNS污染导致的模块拉取缓慢或失败的问题，加速你的构建


## 地址
https://mirrors.saltbo.cn/docker


## 使用帮助
针对Docker客户端版本大于 1.10.0 的用户

您可以通过修改daemon配置文件/etc/docker/daemon.json来使用加速器

```bash
sudo mkdir -p /etc/docker
sudo tee /etc/docker/daemon.json <<-'EOF'
{
  "registry-mirrors": ["https://mirrors.saltbo.cn/docker"]
}
EOF
sudo systemctl daemon-reload
sudo systemctl restart docker
```