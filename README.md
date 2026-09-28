<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# 知影 (DeepVid)

### 新一代音视频深度精读与思维导图提炼工作台
**像读杂志专栏一样读视频 · 图文并茂 · 交互导图 · 本地离线转写**

[下载客户端](https://github.com/977star/DeepVid/releases/latest) • [问题反馈](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local--First-brightgreen.svg?style=flat-square)](https://github.com/977star/DeepVid)

</div>

---

## 为什么选择知影？

传统的 AI 视频总结往往只有几句泛泛而谈的纯文本，丢失了最关键的**板书演示、推导过程与操作细节**。

知影专为深度学习与知识萃取而生，打造杂志级图文并茂的音视频精读工作台：

* **像读杂志专栏一样读视频**：万字连贯图文笔记，观点讲到哪里，当下的操作实拍与板书关键帧就穿插在哪里；
* **结构一目了然的思维导图**：自动提炼交互式树状导图，支持自由缩放、分支折叠与矢量 SVG 导出；
* **生肉/无字幕视频秒变文字**：内置完全离线的本地语音识别引擎，电脑本地直接转写，无需联网、零额外花费，100% 保护隐私；
* **遇到不懂随时深度追问**：读笔记时有疑惑？直接在右侧向 AI 导师提问，结合视频细节为你精准解答；
* **灵动轻巧的音频胶囊**：长文下滑时视频自动吸顶；一键收缩为 44px 极简音频胶囊在后台播放，阅读视野 100% 释放。

---

## 核心功能概览

知影的所有能力均围绕“完成一次高质量精读”与“沉淀你的个人知识库”深度打造：

* **模型与转写自由配置**：
  * 支持各大主流云端大模型（DeepSeek、Gemini、SiliconFlow）及任意自定义 OpenAI 兼容接口；
  * 支持本地私有大模型（Ollama、LM Studio），数据不出电脑；
  * 内置开箱即用的离线语音识别 (ASR)，无需配置 API 即可转写无字幕音视频。
* **灵活定制的精读策略**：
  * **连贯长文 vs 分步精炼**：短视频一气呵成直出杂志专栏，超长课程逐段分层精酿；
  * 支持开启深度思考（Reasoning）模式；
  * 毫秒级自适应抽帧，智能跳过黑屏片头，关键帧与段落完美互为呼应。
* **无缝导出与本地归档**：
  * 自定义本地存储目录，支持导出独立文件夹（含高清配图）、纯文本或统一图库；
  * 原生兼容 Obsidian、Notion、Logseq 等主流双链笔记工具。
* **局域网跨端与 AI 助手互联**：
  * **手机扫码即读**：局域网内手机无需安装 App，扫码即在移动端舒适阅读；
  * **原生内嵌 MCP 服务**：支持在 Cursor、Claude Code、Windsurf 等 AI 客户端中直接检索本地视频音轨与精读笔记。
* **纯粹本地与安全管理**：
  * 音视频切片与精读成果 100% 存储于本地磁盘；
  * 内置一键缓存清理（安全保护加星收藏的笔记），轻松释放存储空间。

---

## 软件实机预览

<div align="center">

| 图文并茂的深度专栏 | 交互式矢量思维导图 |
| :---: | :---: |
| *(实机截图展示区)* | *(实机截图展示区)* |

| 宽屏双栏阅读工作台 | 针对视频细节的精准 AI 追问 |
| :---: | :---: |
| *(实机截图展示区)* | *(实机截图展示区)* |

</div>

---

## 首次打开指南

### macOS 提示「已损坏」或「无法打开」

打开系统 **「终端 (Terminal)」**，复制并运行以下命令：

```bash
sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
```
*(粘贴后按回车，输入电脑密码即可正常秒开)*

<sub>*注：苹果 Gatekeeper 门禁对所有开源未签名应用的通用拦截，应用本身安全纯净。*</sub>

---

### Windows 提示「Windows 已保护你的电脑」

在弹出的窗口中点击 **「更多信息」** ➔ 点击 **「仍要运行」** 即可一秒进入。

<sub>*注：微软 SmartScreen 筛选器对新发布开源软件的通用保护提示。*</sub>

---

## 开源协议

本项目遵循 [MIT License](LICENSE) 开源协议。
