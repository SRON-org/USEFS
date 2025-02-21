<div align="center">

<image src="https://github.com/user-attachments/assets/9e91bfd4-4448-4668-bede-6eafb0b42888" height="86"/>

# USEF 架构 1

The Universal Schedule Sheet Exchange Format Schema V1

通用日程计划表交换格式架构

</div>

## 简介

USEFS 是一个由 [思锐工作室](https://github.com/SRInternet-Studio) 主办，SRON 团队研发的一种**适用于日程表、提醒事项、辅助计划和电子课程表等时间管理类产品**的交换格式，最终目的是统一此类产品的市场生态，旨在使用户能在不同的同类产品中快速迁移个人配置，提升使用效率。

## 特点

- **广泛兼容性**: USEFS 具有丰富的标准参数，无论您的产品处在中低端或高端，拥有丰富的功能，USEFS 都能尽可能的满足你的产品需要。
- **简明易读性**: USEFS 的标准参数关键词均为日常生活中的通俗用语，简单易懂。
- **格式多样性**: USEFS 兼容 JSON，Yaml 和 Toml 配置文件格式，且在 Python 和 .NET Framework 下均有官方包可用，大幅提升使用效率。

## 代码补全

你可以通过引入 [Schema 文件（在建）]()，
并进行以下配置来启用 Yaml 代码的自动补全。

- [VS Code](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [JetBrains IDE](https://www.jetbrains.com/help/idea/yaml.html#use-schema-keyword)
- [Zed Editor](https://zed.dev/docs/languages/yaml#schemas)

## 要求

编码: UTF-8

## 示例

见 [example.yaml（包含注解）](./example.yaml)、[example.json](./example.json)、[example.toml](./example.toml)、

## 开放

USEFS 时刻欢迎各位开发者完善和更新协议。

## 协议

[MIT](./LICENSE)

