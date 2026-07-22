# Valkey for LoongArch (loong64)

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

[Valkey](https://valkey.io/) Docker 容器镜像，移植到 **LoongArch (loong64)** 架构。

本仓库通过向上游 [valkey-io/valkey-container](https://github.com/valkey-io/valkey-container) 应用最小化补丁以支持替代基础镜像，
构建并发布适用于 LoongArch 的 Valkey 容器镜像。

## Docker 镜像

镜像发布在 Docker Hub 上：
[`kubernetesloong64/valkey-loong64`](https://hub.docker.com/r/kubernetesloong64/valkey-loong64)。

- [![kubernetesloong64/valkey-loong64](https://img.shields.io/docker/v/kubernetesloong64/valkey-loong64?arch=loong64&logo=docker&label=kubernetesloong64%2Fvalkey-loong64&sort=semver)](https://hub.docker.com/r/kubernetesloong64/valkey-loong64/tags)

每个版本提供两种基础镜像变体：

- **debian** — 基于 `lcr.loongnix.cn/debian:14`
- **debian-slim** — 基于 `lcr.loongnix.cn/debian:14-slim`

### 拉取镜像

```shell
docker pull kubernetesloong64/valkey-loong64:9.1.1-debian-slim
```

## 许可证

[Apache License 2.0](LICENSE)
