# 安装 Knative

!!! 注意
    请同时查看[Serving 架构](../serving/architecture.md)，其中解释了 Knative 组件和一般的网络概念。

您可以通过以下部署选项之一在集群上安装 Serving 组件、Eventing 组件或两者：

- 使用 [Knative Quickstart 插件](quickstart-install.md) 安装预配置的用于开发目的的本地 Knative 发行版。

- 使用基于 YAML 的安装来安装生产就绪的部署：
    - [使用 YAML 安装 Knative Serving](yaml-install/serving/install-serving-with-yaml.md)
    - [使用 YAML 安装 Knative Eventing](yaml-install/eventing/install-eventing-with-yaml.md)

- 使用 [Knative Operator](operator/knative-with-operators.md) 来安装和配置生产就绪的部署。

- 按照供应商管理的 [Knative 产品](knative-offerings.md)的文档进行操作。

您还可以[升级现有的 Knative 安装](upgrade/README.md)。

!!! 注意
    Knative 安装说明假设您正在运行 Mac 或 Linux，并使用 Bash shell。
<!-- TODO: 链接到高级安装的配置指南 -->
