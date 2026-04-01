# Demo #2

> Issue: #2 | April 2026

---

## 🔧 TraeClaw

**Author**: [@firerlAGI](https://github.com/firerlAGI)

### Introduction

Enables OpenClaw to use Trae desktop as an IDE tool via local bridge service, and provides a sustainable update path for macOS npm plugin integration.

### Links

- **GitHub Repo**: https://github.com/firerlAGI/TraeClaw
- **Live Demo**: _No response_

### Tech Info

| Property | Value |
|----------|-------|
| Type | Plugin / Extension |
| Tech Stack | JavaScript / TypeScript |

### Core Highlights

1. **Integrated Call Chain** - Establishes the local call chain: OpenClaw → trae_delegate → TraeClaw → Trae Desktop, enabling OpenClaw to use Trae as an IDE tool
2. **npm Distribution** - Provides npm installation and update path for `traeclaw`, distributing OpenClaw plugin with complete runtime to reduce deployment and upgrade costs
3. **Comprehensive Troubleshooting** - Built-in health, ready, chat troubleshooting endpoints, with installation guide, FAQ, OpenAPI and integration documentation for quick verification and diagnosis

### Preview

<img width="800" alt="TraeClaw Interface" src="https://github.com/user-attachments/assets/ef9ac122-c405-4ae9-8c29-5646597d1517" />

### Local Setup

Send the following message directly to OpenClaw:

```
Please read AGENTS.md and AI_INSTALL.zh-CN.md in https://github.com/firerlAGI/TraeClaw repository, then install and enable traeclaw via npm on macOS, verify with `openclaw plugins info traeclaw` and `openclaw config validate`, remind me to restart OpenClaw Gateway, then run `trae_status` once more and tell me how to use trae_delegate next.
```

### Additional Information

- **Related Article**: [WeChat Official Account Article](https://mp.weixin.qq.com/s/WYOO8WOxX8i-r9lG6hLtAA)

---

[← Back to Index](../../README.md)
