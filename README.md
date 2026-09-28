<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# 知影 (DeepVid)

### 全能音视频深度精读与思维导图提炼工作台
**Next-Generation AI Video Deep Reading & Interactive Mindmap Distillation Engine**

[简体中文](README.md) • [English](README_EN.md) • [下载最新版 Releases](https://github.com/977star/DeepVid/releases) • [问题反馈 Issues](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)
[![Engine](https://img.shields.io/badge/Engine-Tauri%202.0%20%7C%20FastAPI%20%7C%20React%2019-purple.svg?style=flat-square)](https://github.com/977star/DeepVid)

</div>

---

## 为什么选择知影？

传统的 AI 视频摘要往往只给出泛泛而谈的几句纯文本，缺少上下文逻辑，更丢失了视频中最关键的**画面细节、板书演示与操作过程**。

**知影 (DeepVid)** 专为深度学习、课程消化、研报拆解与专业知识萃取而生，打造杂志级图文并茂的音视频精读工作台：

* **告别碎片化速览**：长上下文单轮直出万字深度长文专栏，章节结构连贯，论据扎实；
* **关键帧实拍混排**：毫秒级精准自适应抽帧，段落观点与实拍画面深度呼应，自动避开片头黑屏；
* **Obsidian 级高保真排版**：原生渲染多色 Callout 提示框、斑马纹数据表格与代码高亮块；
* **交互式矢量思维导图**：Markmap 树状导图，支持自由平移缩放、节点收起展开与 SVG 矢量导出；
* **本地离线语音识别 (ASR)**：内置轻量高效的 sherpa-onnx 离线语音引擎，零上传、无门槛转写本地或无字幕音视频；
* **全文细节 AI 深度追问**：基于全片字幕与深度笔记的局部 RAG 追问导师，随时解答公式、代码与参数疑问；
* **原生 MCP 知识库支持**：内嵌 Model Context Protocol 标准服务，为 Cursor、Windsurf、Claude 等外部 Agent 提供本地音视频资产与精读笔记检索调度能力；
* **灵动音频胶囊播放器**：页面下滑吸顶播放，可一键收拢为极简音频胶囊，阅读空间 100% 释放；
* **局域网跨端无缝协同**：手机端扫码免开即读，支持富文本、独立文件夹归档与多格式 Markdown 导出。

---

## 软件实机预览

<div align="center">

| 深度图文精读专栏 | 交互式矢量思维导图 |
| :---: | :---: |
| *(实机截图展示区)* | *(实机截图展示区)* |

| 宽屏双栏阅读工作台 | 针对视频细节的精准 AI 追问 |
| :---: | :---: |
| *(实机截图展示区)* | *(实机截图展示区)* |

</div>

---

## 核心特性

| 功能模块 | 亮点解析 |
| :--- | :--- |
| **多源媒体解析** | 原生支持 YouTube、哔哩哔哩 (Bilibili)、TikTok、抖音、小红书，以及本地 MP4、MOV、MP3、M4A 等音视频文件的拖拽极速提炼。 |
| **双管线精读引擎** | **全局连贯精读 (One-Pass Stream)** 与 **超长视频分步提炼 (Two-Step Modular)** 自由切换，深度释放大模型超长上下文能力。 |
| **离线 ASR 语音识别** | 集成 sherpa-onnx 离线推理引擎与 Silero VAD 语音断句，纯本地毫秒级提取音轨文本，隐私绝对安全。 |
| **多阶自适应抽帧** | 根据视频时长自适应阶梯采样，智能跳过黑屏片头，呈现专栏杂志级图文质感。 |
| **Obsidian 规范 Callout** | 原生解析展示 Note、Tip、Important、Warning、Caution、Danger 等多色卡片。 |
| **交互式矢量思维导图** | 自动提炼层级分明的交互式思维导图，支持平移、滚轮缩放、节点收展及矢量 SVG / Markdown 导出。 |
| **原生 MCP 知识库** | 遵循开放 Model Context Protocol 协议，支持作为外部 AI 编程工具与知识助手的本地数据底座。 |
| **单实例进程守护** | 原生 Single-Instance 窗口守护，防多开与托盘堆叠，重复启动时平滑唤醒置顶已有窗口。 |
| **多样化知识导出** | 支持独立嵌套文件夹、图片统一归档、同名导出及纯文本模式，零秒复制或分享至本地知识库。 |
| **本地隐私与离线兼容** | 媒体切片与精读成果 100% 存储于本机；支持直连 Ollama、LM Studio 等私有化本地大模型。 |

---

## 下载与安装

前往 **[GitHub Releases 最新发布页](https://github.com/977star/DeepVid/releases)** 获取对应系统的官方安装包：

| 操作系统 | 适用架构与环境 | 安装包格式 | 获取方式 |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | M1 / M2 / M3 / M4 系列芯片 (macOS 12.0+) | `.dmg` 拖拽安装镜像 | [下载 macOS 客户端](https://github.com/977star/DeepVid/releases/latest) |
| **Windows (64位)** | Windows 10 / 11 64位系统 | `.exe` 标准安装包 | [下载 Windows 客户端](https://github.com/977star/DeepVid/releases/latest) |

---

## 首次打开说明 (系统安全提示处理)

知影是开源免费分发的客户端，未购买商业开发者证书，部分操作系统在首次启动时可能会弹出安全拦截提示，可通过以下方法快速打开：

### macOS 提示「已损坏」或「无法打开」
> 苹果 Gatekeeper 门禁对所有开源未签名应用的通用机制，应用本身安全纯净。

- **方法一（推荐 · 纯鼠标操作）**：  
  将应用拖入「应用程序」后，按住键盘 **Control** 键不放，鼠标右键点击 **DeepVid** 图标，在菜单中点击 **打开**，随后在确认弹窗中再次点击 **打开** 即可完成永久信任。
- **方法二（终端一键解除隔离）**：  
  打开系统的「终端 (Terminal)」，执行以下命令：
  ```bash
  sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
  ```

---

### Windows 提示「Windows 已保护你的电脑」
> 微软 SmartScreen 筛选器对新发布开源软件的通用保护提示。

- 点击弹窗中的 **更多信息**，随后点击 **仍要运行** 即可正常进入应用。

---

## 开源协议

本项目遵循 [MIT License](LICENSE) 开源协议。
