# Valkey for LoongArch (loong64)

<p align="center"><a href="README.md">English</a> | <a href="README-zh.md">中文</a></p>

[Valkey](https://valkey.io/) Docker container images ported to the **LoongArch (loong64)** architecture.

This repository builds and publishes Valkey container images for LoongArch by applying minimal patches to the upstream
[valkey-io/valkey-container](https://github.com/valkey-io/valkey-container) to support alternative base images.

## Docker Images

Images are published to Docker Hub under
[`kubernetesloong64/valkey-loong64`](https://hub.docker.com/r/kubernetesloong64/valkey-loong64).

- [![kubernetesloong64/valkey-loong64](https://img.shields.io/docker/v/kubernetesloong64/valkey-loong64?arch=loong64&logo=docker&label=kubernetesloong64%2Fvalkey-loong64&sort=semver)](https://hub.docker.com/r/kubernetesloong64/valkey-loong64/tags)

Two base image variants are provided per version:

- **debian** — based on `lcr.loongnix.cn/debian:14`
- **debian-slim** — based on `lcr.loongnix.cn/debian:14-slim`

### Pull Images

```shell
docker pull kubernetesloong64/valkey-loong64:9.1.1-debian-slim
docker pull kubernetesloong64/valkey-loong64:9.0.5-debian-slim
docker pull kubernetesloong64/valkey-loong64:8.1.9-debian-slim
```

## License

[Apache License 2.0](LICENSE)
