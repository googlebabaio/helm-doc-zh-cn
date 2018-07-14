# Chart 模板开发人员指南

本指南介绍了 Helm 的 chart 模板，重点介绍模板语言。

模板生成 manifest 文件，它们是 Kubernetes 可以识别的 YAML 格式的资源描述。我们将了解模板的结构，如何使用，如何编写 Go 模板以及如何调试。

本指南着重介绍以下概念：

- Helm 模板语言
- 使用 values
- 使用模板的技巧

本指南面向学习Helm模板语言的细节的人。其他指南提供介绍性材料，示例和最佳实践。