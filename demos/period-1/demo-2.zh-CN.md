# Demo #2

> 收录于：第 2 期 | 2026年4月

---

## 🔧 TraeClaw

**作者**: [@firerlAGI](https://github.com/firerlAGI)

### 简介

让 OpenClaw 通过本地桥接服务把 Trae 桌面端当作 IDE 工具来调用，并提供面向 macOS 的可持续更新 npm 插件接入路径。

### 链接

- **GitHub 仓库**: https://github.com/firerlAGI/TraeClaw
- **在线演示**: _No response_

### 技术信息

| 属性 | 值 |
|------|-----|
| 类型 | 插件 / Extension |
| 技术栈 | JavaScript / TypeScript |

### 核心亮点

1. **打通调用链路** - 打通 OpenClaw -> trae_delegate -> TraeClaw -> Trae 桌面端 的本地调用链路，让 OpenClaw 可以把 Trae 当作 IDE 工具使用
2. **npm 分发** - 提供 `traeclaw` 的 npm 安装与更新路径，将 OpenClaw 插件和完整 runtime 一起分发，降低部署和升级成本
3. **完善的排障体系** - 内置 health、ready、chat 等排障入口，并配套安装指南、FAQ、OpenAPI 与集成文档，便于快速验证与定位问题

### 预览

<img width="800" alt="TraeClaw 界面展示" src="https://github.com/user-attachments/assets/ef9ac122-c405-4ae9-8c29-5646597d1517" />

### 本地运行方式

把下面这句话直接发给 OpenClaw 即可：

```
请先阅读 https://github.com/firerlAGI/TraeClaw 仓库里的 AGENTS.md 和 AI_INSTALL.zh-CN.md，然后在 macOS 上通过 npm 安装并启用 traeclaw，验证 openclaw plugins info traeclaw 和 openclaw config validate，提醒我重启 OpenClaw Gateway，再执行一次 trae_status，并告诉我接下来怎么用 trae_delegate。
```

### 其他补充信息

- **相关文章**: [微信公众号文章](https://mp.weixin.qq.com/s/WYOO8WOxX8i-r9lG6hLtAA)

---

[← 返回目录](../../README.zh-CN.md)
