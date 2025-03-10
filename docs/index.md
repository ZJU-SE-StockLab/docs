# 写在前面

你好 👋！

本实验文档仅适用于 2024-2025 春夏学期《软件工程》林海老师班第 C 大组。

本文档包含我们组课程项目的开发指导与规范，强烈建议您在上手开发前阅读本文档，并根据您贡献的代码更新文档中的相关内容。

## 项目结构

按照课程要求，我们将开发一个 **股票交易系统** 的软件工程项目，包括 [客户端](https://github.com/ZJU-SE-StockLab/client)（包括 Web 端和通过 Electron 封装的桌面端）与 [服务端](https://github.com/ZJU-SE-StockLab/server)。

我们采取 Schema-First 的设计模式，使用基于 OpenAPI 规范定义的 API 接口约束前后端开发，并将通过代码实现与框架约束实践这一点。

```bash
StockLab
├── client: 客户端代码
├── server: 服务端代码
└── docs: 实验文档
```

## 开发规范
