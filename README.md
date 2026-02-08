# 🚀 Shannon AI Pentester

[![Stars](https://img.shields.io/github/stars/KeygraphHQ/shannon?logo=github&style=for-the-badge)](https://github.com/KeygraphHQ/shannon/stargazers)
[![Forks](https://img.shields.io/github/forks/KeygraphHQ/shannon?logo=github&style=for-the-badge)](https://github.com/KeygraphHQ/shannon/network/members)
[![TypeScript](https://img.shields.io/github/languages/top/KeygraphHQ/shannon?logo=typescript&style=for-the-badge)](https://github.com/KeygraphHQ/shannon)
[![Adadsws Fork](https://img.shields.io/badge/%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB%20ADADSWS%20Fork-🔥-red?style=for-the-badge)](https://github.com/adadsws/shannon)

<div align="center">
<img src="./assets/shannon-screen.png?v=2" alt="Shannon Screen" width="100%">

# Shannon is your fully autonomous AI pentester. ⚡

Shannon's job is simple: break your web app before anyone else does. <br />
The Red Team to your vibe-coding Blue team. <br />
Every Claude (coder) deserves their Shannon. 🛡️

---

[🌐 Website](https://keygraph.io) • [💬 Discord](https://discord.gg/KAqzSHHpRt) • [📊 Benchmark Results](https://github.com/KeygraphHQ/shannon/tree/main/xben-benchmark-results/README.md)
</div>

## 🎯 What is Shannon?

Shannon is an AI pentester that delivers **actual exploits, not just alerts**. It's the security partner your fast-moving development team deserves.

### The Problem We Solve

Your team ships code at lightning speed with tools like Claude Code and Cursor, but your penetration test happens once a year. That's 364 days of unknown vulnerabilities potentially shipping to production. 😱

Shannon closes this gap by acting as your **on-demand whitebox pentester**. It doesn't just find potential issues—it executes real exploits, providing concrete proof of vulnerabilities so you can ship with confidence.

### Keygraph Platform Integration

Shannon is a core component of the **Keygraph Security and Compliance Platform**. While Shannon automates penetration testing, our broader platform automates your entire compliance journey—from evidence collection to audit readiness. We're building the "Rippling for Cybersecurity," a single platform to manage your security posture and streamline compliance frameworks like SOC 2 and HIPAA.

➡️ **[Learn more about the Keygraph Platform](https://keygraph.io)**

## 🎬 See Shannon in Action

**Real Results**: Shannon discovered 20+ critical vulnerabilities in OWASP Juice Shop, including complete auth bypass and database exfiltration. [See full report →](sample-reports/shannon-report-juice-shop.md)

![Demo](assets/shannon-action.gif)

## ✨ Features

- **Fully Autonomous Operation**: Launch with a single command. The AI handles everything from advanced 2FA/TOTP logins (including sign in with Google) to final report generation.
- **Pentester-Grade Reports**: Delivers reproducible exploits with concrete proof of vulnerabilities.
- **VS Code Integration**: This fork adds seamless integration with VS Code for enhanced developer experience.

## ⚡ Quick Start

```bash
npm install -g @keygraphhq/shannon
shannon scan https://your-web-app.com
```

## 🏆 Why This Fork? (by adadsws)

This fork enhances the original Shannon with **VS Code integration**, making it even easier to incorporate autonomous pentesting into your development workflow. Get security insights directly in your editor!

## 📋 Core Capabilities

| Feature | Description |
|---------|-------------|
| **Autonomous Scanning** | Zero intervention required from start to finish |
| **Real Exploits** | Not just findings—actual working exploits |
| **Browser-Based Testing** | Uses real browser automation for accurate results |
| **Advanced Auth Handling** | Supports 2FA, TOTP, and OAuth flows |
| **Comprehensive Reporting** | Detailed reports with reproducible steps |

## 🚀 Performance

Shannon achieves a **96.15% success rate** on the hint-free, source-aware XBOW benchmark, making it one of the most effective autonomous pentesters available.

## 🤝 Contributing

We welcome contributions! Check out our [contributing guidelines](CONTRIBUTING.md) to get started.

## 📄 License

Shannon is released under the [MIT License](LICENSE). Enjoy the freedom to use, modify, and distribute!

---

<div align="center">
Built with ❤️ by <a href="https://keygraph.io">Keygraph</a> • <a href="https://github.com/adadsws">Fork by adadsws</a>
</div>
