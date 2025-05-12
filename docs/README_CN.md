<h1 align="center">欢迎来到 Hulo-Postgres 👋</h1>
<center>

[![Hulo](https://img.shields.io/badge/Hulo-%238866E9.svg?logoColor=white&style=for-the-badge)](https://github.com/hulo-lang/hulo)

</center>

---

[English](../README.md) | 简体中文

> 本项目是一个实验性仓库，旨在使用 [Hulo](https://github.com/hulo-lang) 语言重写 [PostgreSQL](https://github.com/postgres/postgres) 中的传统批处理脚本（如 `.sh`、`.bat` 等）。  
> 通过将命令式脚本转换为声明式 Hulo 代码，本项目探索脚本语言的现代化表达方式与可维护性。

## 🚀 快速开始

::: warning
当前项目处于早期阶段，可能存在功能不完整、性能欠佳或平台兼容性不足的问题，不建议在生产环境中使用。
:::

### 克隆项目并构建

```sh
git clone https://github.com/hulo-lang/postgres.git

cd postgres

hulo build .
```

### 示例资源

项目中 `testdata` 目录包含原始 PostgreSQL 脚本文件的副本，作为 Hulo 重写的语义与行为参考。

## 🤝 如何贡献

我们欢迎任何形式的贡献，包括但不限于：

* 报告 bug
* 提交 issue 或 feature request
* 翻译或重构脚本
* 提交 Pull Request

请先查阅 [issues 页面](https://github.com/hulo-lang/postgres/issues) 并遵循社区贡献指南。

## 📝 协议

本项目采用与 PostgreSQL 相同的 [PostgreSQL License](https://opensource.org/license/postgresql)，详见 [LICENSE](LICENSE) 文件。