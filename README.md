<div align="center">

<image src="https://github.com/user-attachments/assets/9e91bfd4-4448-4668-bede-6eafb0b42888" height="86"/>

# USEF 架构 1

The Universal Schedule Sheet Exchange Format Schema V1

通用日程计划表交换格式架构

</div>

## 简介

USEFS 是一个由 [思锐工作室](https://github.com/SRInternet-Studio) 主办，SRON 团队研发的一种**适用于日程表、提醒事项、辅助计划和电子课程表等时间管理类产品**的交换格式，最终目的是统一此类产品的市场生态，旨在使用户能在不同的同类产品中快速迁移个人配置，提升使用效率。

## 为什么选择我们的 USEFS

**更灵活、更强大的组织能力，可扩展性，以及规则性**

- **广泛兼容性**: USEFS 具有丰富的标准参数，无论您的产品处在中低端或高端，拥有丰富的功能，USEFS 都能尽可能的满足你的产品需要。
- **简明易读性**: USEFS 的标准参数关键词均为日常生活中的通俗用语，简单易懂。
- **格式多样性**: USEFS 兼容 JSON，Yaml 和 Toml 配置文件格式，且在 Python 和 .NET Framework 下均有官方包可用，大幅提升使用效率。

| 特性           | USEFS 标准                                    | ICS 标准 或 其他通用交换格式        | 
| -------------- | --------------------------------------- | ----------------------------------------- |
| **组织**       | **集合 (Collections)：日程分组管理**          | 单一列表：难以组织，查找效率低                  |
| **规则**       | **RRULE + 灵活 Enable：精确控制**           | 有限属性和规则：难以表达复杂需求                    |
| **信息**       | **自定义属性：无限可能**                | 有限的标准属性：信息记录受限                      |
| **数据格式**       | **JSON/YAML/TOML：与各种工具无缝集成**                | 仅限 iCalendar格式或其他单一格式：拓展性差    |

## 生态

[USEFS_Python](https://github.com/SRON-org/USEFS_Python)：在 Python 上提供对使用 USEF 架构 格式的文件的进行访问、修改、增添、删除等高级管理功能。

[USEFS_ICS](https://github.com/SRON-org/USEFS_ICS)：将使用 USEFS（通用日程计划表交换格式架构） 的 YAML、TOML 或 JSON 格式文件转换为标准 iCalendar (.ics) 格式的日历文件

USEFS.Sharp（在建）：在 .NET Framework 和 C Language 上提供对使用 USEF 架构 格式的文件的进行访问、修改、增添、删除等高级管理功能。

## 代码补全

你可以通过引入 [Schema 文件（在建）]()，
并进行以下配置来启用 Yaml 代码的自动补全。

- [VS Code](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [JetBrains IDE](https://www.jetbrains.com/help/idea/yaml.html#use-schema-keyword)
- [Zed Editor](https://zed.dev/docs/languages/yaml#schemas)

## 标准和示例

编码: UTF-8

参考：[example.yaml（包含注解）](./example.yaml)、[example.json](./example.json)、[example.toml](./example.toml)、

## 开放

我们时刻欢迎各位开发者完善和更新协议，欢迎提交 Pull Request 来改进 USEFS ！

## 协议

[MIT](./LICENSE)

