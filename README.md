# OpenCode — 终端优先的开源 AI 编程代理

这是 [OpenCode](https://opencode.ai) 官方中文落地页的源代码。

## 项目简介

OpenCode 是一个开源的 AI 编程代理，模型无关，原生 LSP，专为终端与严肃开发工作流设计。本项目是其展示主页，采用极简主义设计风格，旨在提供流畅的跨设备浏览体验和快速的安装指南。

### 核心特性

- **终端优先**：为严肃开发者打造，快速、可脚本化、可组合。
- **模型无关**：自由切换 Claude, OpenAI, Google 或本地模型 (如 Ollama)。
- **原生 LSP**：内置语言服务器协议支持，提供精准的代码补全、跳转和诊断。
- **客户端/服务器架构**：支持远程控制，可在电脑上运行服务，通过移动端或桌面端作为“遥控器”。
- **双代理模式**：`build` 负责执行与开发，`plan` 负责推演与规划。

## 网页开发

本项目是一个单页面应用 (SPA)，基于以下技术构建：

- **HTML5/CSS3**：使用原生 CSS 变量、Clamp 流体响应式设计。
- **Vanilla JavaScript**：无框架依赖，实现轻量级的交互（剪贴板、FAQ、导航切换）。
- **设计系统**：采用 "Intentional Minimalism" 设计理念，配合 LXGW WenKai 和 IBM Plex Mono 字体。

### 本地查看

直接在浏览器中打开 `index.html` 即可预览网页。

## 关于 OpenCode 工具

如果您想安装并使用 OpenCode AI 编程工具，可以使用以下命令之一：

```bash
# YOLO 安装 (推荐)
curl -fsSL https://opencode.ai/install | bash

# 使用 npm
npm i -g opencode-ai@latest

# 使用 Homebrew
brew install opencode
```

更多安装方式和详细文档请访问 [opencode.ai/docs](https://opencode.ai/docs)。

## 开源协议

本项目基于开源协议分发。OpenCode 工具核心仓库请参考 [sst/opencode](https://github.com/sst/opencode)。

---

© 2024 OpenCode.
