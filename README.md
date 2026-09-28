<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# 知影 (DeepVid)

### 像读专栏一样读视频 · 原生支持 MCP 与 Obsidian 的音视频深度精读工具
**不看原视频也能学透 · 图文笔记 · 思维导图 · 本地离线转写**

[下载客户端](https://github.com/977star/DeepVid/releases/latest) • [问题反馈](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local--First-brightgreen.svg?style=flat-square)](https://github.com/977star/DeepVid)

</div>

---

## 为什么选择知影？

传统的 AI 视频总结往往只有寥寥几句概括，丢掉了最核心的操作演示、PPT 板书与推导细节，看完依然一头雾水。

知影专为深度学习与知识沉淀打造，把长视频重构成真正能学到东西的**图文精读专栏**与**思维导图**：

* **直接让 AI 替你查视频 (MCP)**：原生支持 MCP 协议。你可以直接在 Cursor、Claude Code、Windsurf 等 AI 助手里向知影提问，AI 会自动翻找视频音轨与笔记给出答案，连原视频都不用你亲自打开；
* **一键导入 Obsidian 知识库**：原生支持 Obsidian 的高亮卡片与对比表格，导出时自动打包高清配图，笔记直接沉淀到你的第二大脑，拒绝看后即弃的信息孤岛；
* **不看原视频也能彻底学透**：单轮直出万字深度长文，关键结论讲到哪里，当下的操作实拍、板书图表就穿插在哪里，彻底告别枯燥纯文本；
* **一眼理清全片脉络的思维导图**：自动将长视频凝练为结构分明的树状导图，滚轮缩放、层级折叠，轻松把握全片知识框架；
* **无字幕视频本地直接转文字**：内置完全离线的本地语音识别，电脑本地直接转写，无需联网、无需配置 API，音视频文件不出电脑，100% 保护隐私；
* **手机扫码直接看**：电脑提炼完成，手机扫码即可直接阅读，碎片时间轻松复习。

---

## 核心功能

* **支持主流平台与本地文件**：
  * 支持粘贴 B站 (Bilibili)、YouTube、抖音、TikTok、小红书视频链接；
  * 支持直接拖拽本地 MP4、MOV 视频或 MP3、M4A 录音，秒级开始提炼。
* **模型与转写自由搭配**：
  * 支持直连云端主流模型（DeepSeek、Gemini、SiliconFlow）或任意 OpenAI 兼容接口；
  * 支持直连本地离线模型（Ollama、LM Studio），断网也能提炼；
  * 内置开箱即用的离线语音转写，无字幕视频也能一键转文字。
* **灵活的精读模式与思考深度**：
  * **连贯长文 vs 超长分段**：短视频一气呵成出专栏，超长讲座分段逐层剖析；
  * 支持开启深度思考（Reasoning）模式；
  * 毫秒级自适应抽帧，自动跳过片头黑屏，精准抓取演示画面。
* **无缝接入你的工作流**：
  * **MCP 智能检索**：作为外部 AI 助手的音视频知识库；
  * **Obsidian 归档**：导出含完整配图的独立文件夹；
  * **手机局域网阅读**：无需安装手机端 App，扫码即读。
* **本地存储与数据安全**：
  * 所有视频切片与精读成果 100% 保存在你的本地硬盘；
  * 内置一键缓存清理（安全保护加星收藏的笔记），随时为电脑腾出空间。

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

## 首次打开指南 (仅限测试版)

### macOS 提示「已损坏」或「无法打开」

打开系统 **「终端 (Terminal)」**，运行以下命令（需输入电脑密码）：

```bash
sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
```

<sub>*注：苹果 Gatekeeper 门禁对所有开源未签名应用的通用拦截，应用本身安全纯净。*</sub>

---

### Windows 提示「Windows 已保护你的电脑」

在弹出的窗口中点击 **「更多信息」** ➔ 点击 **「仍要运行」** 即可一秒进入。

<sub>*注：微软 SmartScreen 筛选器对新发布开源软件的通用保护提示。*</sub>

---

## 开源协议

本项目遵循 [MIT License](LICENSE) 开源协议。
