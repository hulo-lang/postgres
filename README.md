<h1 align="center">Welcome to Hulo-Postgres 👋</h1>
<center>

[![Hulo](https://img.shields.io/badge/Hulo-%238866E9.svg?logoColor=white&style=for-the-badge)](https://github.com/hulo-lang/hulo)

</center>

---

English | [简体中文](docs/README_CN.md)

> This is an experimental project that aims to rewrite the original batch scripts (e.g., `.sh`, `.bat`) in the [PostgreSQL](https://github.com/postgres/postgres) source code using the [Hulo](https://github.com/hulo-lang) language.
> By transforming imperative shell scripts into declarative Hulo code, the project explores modern script practices and maintainability.

## 🚀 Getting Started

::: warning
This project is in an early stage and may have incomplete functionality, performance issues, or compatibility problems. It is not recommended for production use.
:::

### Clone and Build

```sh
git clone https://github.com/hulo-lang/postgres.git

cd postgres

hulo build .
```

### Test Data

The `testdata` directory contains original script files extracted from the PostgreSQL repository, serving as translation references for Hulo.

## 🤝 Contributing

We welcome all kinds of contributions, including but not limited to:

* Reporting bugs
* Submitting issues or feature requests
* Translating or rewriting scripts
* Sending pull requests

Please check the [issues page](https://github.com/hulo-lang/postgres/issues) and follow the contribution guidelines.

## 📝 License

This project is licensed under the [PostgreSQL License](https://opensource.org/license/postgresql), consistent with the upstream PostgreSQL repository. See [LICENSE](LICENSE) for details.