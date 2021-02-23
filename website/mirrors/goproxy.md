# Goproxy


## 简介
Go Module公共代理仓库，代理并缓存go模块。你可以利用该代理来避免DNS污染导致的模块拉取缓慢或失败的问题，加速你的构建


## 地址
https://mirrors.saltbo.cn/goproxy


## 使用帮助
1.使用go1.11以上版本并开启go module机制

2.导出GOPROXY环境变量

```bash
export GOPROXY=https://mirrors.saltbo.cn/goproxy,direct
```