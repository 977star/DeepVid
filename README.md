<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# 知影 (DeepVid)

### 🎬 把长视频变成图文杂志与思维导图的 AI 精读神器
**告别枯燥流水账 · 保留关键画面演示 · 图文深度精读 · 跨平台支持**

[🇨🇳 简体中文](README.md) • [🇺🇸 English (Coming soon)](README.md) • [📥 立即下载客户端](https://github.com/977star/DeepVid/releases) • [💬 意见与反馈](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)

</div>

---

## 🌟 它能为你解决什么问题？

平时看 1 小时的技术教程、公开课、会议录播或长视频，总是遇到这些痛点：
- ❌ **纯文本 AI 总结太简略**：只有几句概括，遗漏了核心逻辑与推导过程；
- ❌ **丢失关键画面**：黑板上的公式、代码实操、PPT 架构图完全看不到；
- ❌ **重看视频太费时**：为了找某个知识点，反复拖动进度条。

**知影 (DeepVid)** 让你**「5 分钟读透 1 小时视频」**：
粘贴视频链接或拖入本地文件，自动生成**图文并茂的杂志级深度笔记、核心大纲时间轴、交互式思维导图与完整逐字稿**。

---

## 🖼️ 软件功能预览

<!-- 截图展示区预留 -->
<div align="center">

| 📖 图文并茂的深度专栏精读 | 🌳 交互式矢量思维导图 |
| :---: | :---: |
| *(软件实机截图位置 1)* | *(软件实机截图位置 2)* |

| 🎬 悬浮画中画与随时对照 | 💬 针对视频细节的 AI 深度追问 |
| :---: | :---: |
| *(软件实机截图位置 3)* | *(软件实机截图位置 4)* |

</div>

---

## ✨ 核心功能亮点

- **📸 实拍画面胶卷混排**：智能捕捉视频高光画面与操作截图，段落与实操画面一一对应，看笔记就像看专业图文专栏。
- **🌳 交互式思维导图**：自动生成层级分明的知识架构图，支持自由缩放、分支折叠与高清图片导出。
- **🎬 悬浮小窗随心对照**：下滑阅读笔记时，视频自动无缝贴边悬浮，随时对照画面与字幕。
- **💬 针对性 AI 追问抽屉**：对视频里的某行代码、某个参数或推导步骤有疑问？随时向 AI 追问。
- **🌈 现代化排版与导出**：支持重点彩色提示卡片、斑马纹表格与代码高亮，可一键导出 Markdown 或整套带图文档。
- **🎬 支持全平台音视频**：支持 YouTube、哔哩哔哩、抖音、TikTok、小红书以及本地 MP4 / MOV / MP3 等格式。
- **⚡ 免环境配置与在线更新**：无需安装 Python 或任何复杂环境，双击即可运行；软件内支持一键平滑自动更新。
- **🔒 隐私与本地数据安全**：笔记与媒体文件全部保存在你的电脑本地，支持对接 DeepSeek、硅基流动、Gemini 或本地离线大模型（Ollama）。

---

## 📥 客户端下载

前往 👉 **[GitHub Releases 最新版本下载页面](https://github.com/977star/DeepVid/releases)** 获取对应系统的安装包：

| 操作系统 | 下载文件 | 说明 |
| :--- | :--- | :--- |
| 🍏 **macOS (苹果芯片)** | `DeepVid_2.2.0_aarch64.dmg` | 适用于 M1 / M2 / M3 / M4 系列 Mac |
| 🪟 **Windows (64位)** | `DeepVid_2.2.0_x64-setup.exe` | 适用于 Windows 10 / 11 64位电脑 |

---

## 🚀 首次打开指南（超简单解决系统拦截）

由于知影是开源免签名应用，系统自带的安全防护机制可能会在首次打开时弹出提示，按照以下步骤即可 1 秒打开：

### 🍏 macOS 用户提示「已损坏」或「无法打开」：
> 💡 苹果 Gatekeeper 门禁对所有开源未签名软件的默认拦截，应用本身 100% 安全纯净。

- **最推荐（纯鼠标 0 命令）**：  
  安装后，**按住键盘 `Control` 键不放，鼠标右键点击知影图标 ➔ 点击「打开」➔ 在弹窗中再次点击「打开」**，即可永久信任正常启动！
- **一键终端命令**：  
  打开系统的「终端 (Terminal)」，粘贴并运行以下命令即可：
  ```bash
  sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
  ```
- **安装包内置修复**：  
  双击 DMG 安装镜像中自带的「损坏修复.command」一键工具。

---

### 🪟 Windows 用户提示「Windows 已保护你的电脑」：
> 💡 微软 SmartScreen 筛选器对新发布软件的通用安全提示。

- 遇到蓝底拦截弹窗时，只需点击弹窗上的 **「更多信息」 ➔ 点击「仍要运行」** 即可立即进入应用。

---

## 🔄 应用内一键升级

知影客户端内置了静默更新机制：
1. 当有新版本发布时，客户端顶部导航栏会自动亮起更新提示；
2. 点击【一键更新】，系统将在后台静默下载最新版本；
3. 下载完成后，根据你的空闲时间点击【重启更新】，即可无缝升级到最新版本，无需手动重新下载安装包。

---

## 📄 开源许可证

本项目基于 [MIT License](LICENSE) 协议发布，免费使用。
