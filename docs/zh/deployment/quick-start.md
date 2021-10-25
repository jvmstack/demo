为了让大家更快的上手了解Apollo配置中心，我们这里准备了一个Quick Start，能够在几分钟内在本地环境部署、启动Apollo配置中心。

考虑到Docker的便捷性，我们还提供了Quick Start的Docker版本，如果你对Docker比较熟悉的话，可以参考[Apollo Quick Start Docker部署](zh/deployment/quick-start-docker)通过Docker快速部署Apollo。

不过这里需要注意的是，Quick Start只针对本地测试使用，如果要部署到生产环境，还请另行参考[分布式部署指南](zh/deployment/distributed-deployment-guide)。

> 注：Quick Start需要有bash环境，Windows用户请安装[Git Bash](https://git-for-windows.github.io/)，建议使用最新版本，老版本可能会遇到未知问题。也可以直接通过IDE环境启动，详见[Apollo开发指南](zh/development/apollo-development-guide)。

# &nbsp;
# 一、准备工作
## 1.1 Java

* Apollo服务端：1.8+
* Apollo客户端：1.8+
    * 如需运行在 Java 1.7 运行时环境，请使用 1.x 版本的 apollo 客户端，如 1.9.1

在配置好后，可以通过如下命令检查：
```sh
java -version
```
