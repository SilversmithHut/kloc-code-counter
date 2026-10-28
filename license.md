# 📊 Kloc Code Counter

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,16,28&height=210&section=header&text=Kloc%20Code%20Counter&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Measure%20Your%20Code.%20Understand%20Your%20Project.&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.5.1-7B2CBF?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Languages](https://img.shields.io/badge/100%2B%20languages-5A189A?style=for-the-badge&logo=codeforces&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-FF8500?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Speed](https://img.shields.io/badge/speed-%3C1s%20%2F%201M%20LOC-9D4EDD?style=for-the-badge&logo=speedtest&logoColor=white)](https://github.com)

<br/>

### 🔢 A blazing-fast CLI & library to count lines of code across 100+ languages

*⚡ Ultra Fast • 🎯 Accurate • 📈 Beautiful Reports • 🔍 Deep Insights*

<br/>

<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/📥_INSTALL-7B2CBF?style=for-the-badge&logo=download&logoColor=white&labelColor=4C1D7A" alt="Install" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-5A189A?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=3A0F66" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/📚_DOCS-FF8500?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=B85E00" alt="Docs" height="45"/>
</a>

</div>

<img width="1672" height="941" alt="3e572608-191a-4bba-aae6-fc94a156aacd" src="https://github.com/user-attachments/assets/3f092a3e-9dc6-4191-b345-b67fc3aa7884" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Kloc Code Counter** is a fast, lightweight, and developer-friendly tool for measuring the **size and complexity of your codebase**. It scans your projects, counts lines of code (LOC), comments, blanks, and delivers detailed, visual reports — all in seconds.

Whether you're a solo dev tracking project growth, a team lead auditing legacy code, or a researcher comparing languages — Kloc gives you **clean, actionable numbers** without any setup headaches.

> 💡 **Kloc** = **Kilo Lines of Code** (1,000 lines). The name says it all — it's built to count fast, at scale.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| ⚡ **Blazing Fast** | 🧠 **100+ Languages** | 📊 **Rich Reports** |
|:---:|:---:|:---:|
| Processes 1M LOC<br/>in under 1 second | Python, JS, Rust, Go,<br/>Java, C++ & more | Terminal, JSON,<br/>HTML & CSV |

| 🔍 **Smart Filters** | 📈 **Diff Mode** | 🎨 **Visual Charts** |
|:---:|:---:|:---:|
| Ignore files via<br/>`.gitignore` & globs | Compare branches<br/>or commits | ASCII bars,<br/>pie charts & graphs |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why Use Kloc

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🚀 **Ridiculously Fast** | Multi-threaded engine scans millions of lines in seconds — even huge monorepos |
| 🎯 **Language-Aware** | Properly parses comments, strings, and nested blocks per language — no fake numbers |
| 📦 **Zero Dependencies** | Single binary, no runtime required, works on every OS |
| 📊 **Beautiful Output** | Gorgeous terminal tables, HTML reports & SVG charts out of the box |
| 🔄 **CI-Ready** | Perfect for GitHub Actions, GitLab CI & Jenkins — enforce LOC limits in PRs |
| 🛠️ **Extensible** | Add custom language definitions via a simple TOML config |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Sample Output

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════╗
║  📊  Kloc Code Counter  v3.5.1                           ║
╠══════════════════════════════════════════════════════════╣
║  Language       Files    Code    Comment    Blank   Total ║
║  ─────────────────────────────────────────────────────────║
║  🐍 Python        142   18,432     2,114    1,876   22,422 ║
║  🟨 JavaScript     87   12,108     1,202    1,014   14,324 ║
║  🦀 Rust           34    8,971       913      642   10,526 ║
║  🌐 TypeScript     56    6,442       712      508    7,662 ║
║  📄 Markdown       28    3,214         0      214    3,428 ║
║  ─────────────────────────────────────────────────────────║
║  📈 TOTAL         347   49,167     4,941    4,254   58,362 ║
╚══════════════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📊 kloc-code-counter/
├── 🎯 src/
│   ├── parser/                # Language parsers
│   ├── counter/               # LOC counting engine
│   ├── reporters/             # Output formats
│   └── cli/                   # Command-line interface
├── 🌐 languages/              # 100+ language definitions
│   ├── python.toml
│   ├── rust.toml
│   └── ...
├── 📊 reports/                # HTML / SVG generators
├── 🧪 tests/                  # Unit & integration tests
└── 📖 docs/                   # Usage & API docs
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-4E4E4E?style=for-the-badge&logo=gnometerminal&logoColor=white)
![TOML](https://img.shields.io/badge/TOML-9C4121?style=for-the-badge&logo=toml&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Missing a language? Want to contribute a reporter?

<div align="center">

<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-7B2CBF?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/QIwle00VhAuPh1ScF">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FF8500?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 📊 Made with 🔢 by the Kloc Team

*If Kloc saved you time measuring your codebase — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,16,28&height=120&section=footer" width="100%"/>

</div>

---
