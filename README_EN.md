<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# DeepVid (知影)

### Next-Generation AI Video Deep Reading & Interactive Mindmap Distillation Engine

[简体中文](README.md) • [English](README_EN.md) • [Download Releases](https://github.com/977star/DeepVid/releases) • [Community & Issues](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)
[![Engine](https://img.shields.io/badge/Engine-Tauri%202.0%20%7C%20FastAPI%20%7C%20React%2019-purple.svg?style=flat-square)](https://github.com/977star/DeepVid)

</div>

---

## Why DeepVid?

Traditional AI summaries often produce generic, robotic bullet points devoid of context and missing the most important aspect of video: **visual demonstrations, slides, and operational details**.

**DeepVid (知影)** is crafted specifically for deep learners, researchers, creators, and professionals to redefine the video reading experience into a magazine-grade illustrated digest:

* **Coherent Long-Form Notes**: One-pass stream produces cohesive, in-depth Markdown columns with solid arguments and structure.
* **Smart Illustrated Snapshots**: Millisecond-accurate snapshot extraction deeply aligned with respective chapters, automatically skipping black intro frames.
* **Obsidian-Grade Callouts**: Multi-colored alert cards, zebra-striped tables, and code syntax highlighting.
* **Interactive Vector Mindmaps**: Markmap tree hierarchy with drag/pan, zoom, branch collapsing, and SVG vector export.
* **Local Offline ASR Engine**: Built-in lightweight sherpa-onnx offline speech recognition with Silero VAD, requiring zero cloud upload.
* **Pinpoint AI Mentor**: Local RAG knowledge base for specific questions regarding timestamps, formulas, and code snippets.
* **Native Model Context Protocol (MCP)**: Embedded standard MCP server allowing IDEs and coding agents (Claude, Cursor, Windsurf) to query video transcripts and notes.
* **Dynamic Island Mini Player**: Pinned top video player with one-click collapse into a minimalist vibrating audio capsule, freeing 100% reading space.
* **LAN Cross-Device Sync**: Mobile QR scan reading and instant Markdown/illustrated multi-format export.

---

## Application Showcase

<div align="center">

| Illustrated Long-Form Digest | Interactive Vector Mindmap |
| :---: | :---: |
| *(Screenshot Showcase)* | *(Screenshot Showcase)* |

| Widescreen Dual-Pane Workspace | Pinpoint Video AI Mentor |
| :---: | :---: |
| *(Screenshot Showcase)* | *(Screenshot Showcase)* |

</div>

---

## Core Features

| Feature Module | Highlights |
| :--- | :--- |
| **Universal Media Parser** | Native support for YouTube, Bilibili, TikTok, Douyin, Xiaohongshu, and local MP4/MOV/MP3/M4A media files. |
| **Dual Distillation Pipelines** | Switch between **One-Pass Stream (Recommended)** and **Two-Step Modular Pipeline** for long videos, unleashing large context model capabilities. |
| **Offline Speech Recognition** | Integrated sherpa-onnx inference engine and Silero VAD segmentation for instant local audio-to-text extraction with complete privacy. |
| **Adaptive Keyframe Extraction** | Multi-tier adaptive snapshot extraction avoiding black intro frames for magazine-quality articles. |
| **Obsidian-Style Callouts** | Native support for Note, Tip, Important, Warning, Caution, and Danger callouts with adaptive styling. |
| **Interactive Mindmaps** | Clear hierarchical mindmaps with drag-and-drop panning, scroll wheel zooming, branch collapsing, and SVG export. |
| **Native MCP Server** | Built-in Model Context Protocol server enabling external AI coding tools and assistants to query local video knowledge. |
| **Single-Instance Guard** | Native single-instance daemon brings running windows to the foreground on duplicate launches. |
| **Multi-Mode Export** | Nested folder, unified image folder, same-name export, and pure text export formats for seamless Obsidian/Notion integration. |
| **100% Offline & Private** | Local storage for media and digests; supports local Ollama / LM Studio integration. |

---

## Downloads & Installation

Visit **[GitHub Releases Page](https://github.com/977star/DeepVid/releases)** for all official release packages:

| Platform | Architecture & Environment | Package Format | Direct Download |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | Apple Silicon Mac (M1 / M2 / M3 / M4, macOS 12.0+) | `.dmg` Drag-and-Drop Image | [Download macOS App](https://github.com/977star/DeepVid/releases/latest) |
| **Windows (64-bit)** | Windows 10 / 11 64-bit | `.exe` Standard Installer | [Download Windows App](https://github.com/977star/DeepVid/releases/latest) |

---

## First Launch Guide (System Security Prompts)

Since DeepVid is an open-source, community-distributed app without paid commercial signing certificates, system security features may prompt on first launch:

### macOS: "App is damaged and can't be opened"
> Apple Gatekeeper default protection for open-source applications. The app is 100% safe.

- **Option 1 (Recommended · Mouse only)**:  
  After dragging into Applications, **hold down the `Control` key, right-click the `DeepVid` icon ➔ click "Open" ➔ click "Open" again in the dialog** to permanently trust and open.
- **Option 2 (Terminal)**:  
  Run this command in Terminal:  
  ```bash
  sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
  ```

---

### Windows: "Windows protected your PC"
> Microsoft SmartScreen generic notification for new open-source executables.

- Click **"More info" ➔ click "Run anyway"** to launch immediately.

---

## License

Distributed under the [MIT License](LICENSE).
