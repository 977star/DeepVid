<div align="center">

<img src="assets/logo.png" width="120" height="120" alt="DeepVid Logo" style="border-radius: 26px; box-shadow: 0 8px 24px rgba(0,0,0,0.12);" />

# DeepVid (知影)

### Next-Generation AI Video Deep Reading & Interactive Mindmap Distillation App
**Read Videos Like Magazine Columns · Illustrated Snapshots · Interactive Mindmaps · Offline ASR**

[简体中文](README.md) • [English](README_EN.md) • [Download Releases (v2.8.11)](https://github.com/977star/DeepVid/releases/latest) • [Feedback & Issues](https://github.com/977star/DeepVid/issues)

<br/>

[![Release](https://img.shields.io/github/v/release/977star/DeepVid?style=flat-square&color=blue)](https://github.com/977star/DeepVid/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-orange.svg?style=flat-square)](https://github.com/977star/DeepVid/releases)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local--First-brightgreen.svg?style=flat-square)](https://github.com/977star/DeepVid)

</div>

---

## Why DeepVid?

Have you ever struggled with video-based learning and research?

- **Long videos take too much time**: 1-2 hour lectures, conferences, and tutorials are hard to watch from start to finish;
- **Generic AI summaries are superficial**: Typical AI summaries provide only a few generic bullet points, stripping away code walk-throughs, slides, formulas, and operational details;
- **Unsubtitled videos are difficult to follow**: Foreign-language or unsubtitled content requires manual transcription or third-party tools;
- **Easy to forget, hard to retrieve**: You remember learning something useful, but cannot locate the exact timestamp or diagram days later.

**DeepVid (知影)** redefines video consumption. It is not just an AI text summarizer, but a dedicated **Illustrated Deep Reading Workspace**:

* **Read Videos Like Magazine Columns**: Generates structured, comprehensive long-form articles with snapshot frames embedded right next to relevant arguments, eliminating plain text boredom;
* **Bird's-Eye View Mindmaps**: Automatically distills hierarchical tree mindmaps with zoom, pan, branch collapse/expansion, and SVG export;
* **100% Offline Local Speech Recognition**: Built-in offline ASR engine transcribes audio on your local machine with zero cloud upload and complete data privacy;
* **In-Depth AI Mentor**: Have questions about a specific formula, code snippet, or argument? Ask the AI mentor on the fly with video context awareness;
* **Dynamic Island Audio Capsule**: Video pins to top during scrolling and collapses into a compact 44px vibrating audio capsule with a single tap, dedicating 100% screen space to reading;
* **Seamless Mobile Sync & Flexible Export**: Scan the QR code from your phone to read on mobile without installing an app; export full Markdown packages with high-res images directly into Obsidian or Notion.

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

| Feature | What It Does for You |
| :--- | :--- |
| **Universal Media Input** | Supports YouTube, Bilibili, TikTok, Douyin, Xiaohongshu links, or drag-and-drop local MP4, MOV videos, and MP3, M4A, WAV audio files. |
| **Smart Snapshot Layout** | Automatically captures key visual moments (slides, code, diagrams) and interweaves them into notes, skipping black intro frames. |
| **Interactive Mindmaps** | Clear hierarchical mindmaps with drag-and-drop panning, zooming, branch collapsing, and vector SVG export. |
| **Offline Local ASR** | Integrated local speech recognition models transcribe audio entirely on your device with complete privacy. |
| **Dual Distillation Modes** | Choose between full one-pass stream for cohesive essays or multi-step breakdown for multi-hour lectures. |
| **Obsidian-Grade Callouts** | Native support for Tips, Insights, Warnings, Cautions, and Danger cards alongside zebra tables and syntax-highlighted code. |
| **Pinpoint AI Mentor** | Ask specific questions regarding timestamps, parameters, or technical steps directly from the reading pane. |
| **Dynamic Audio Capsule** | Video automatically pins upon scroll; collapse it into a minimal audio capsule to maximize reading focus. |
| **Cross-Device & Export** | Read on mobile via LAN QR code; export to clipboard or save as Markdown folders with asset images for Obsidian and Notion. |
| **Connect AI Coding Agents** | Built-in standard Model Context Protocol support allows Cursor, Claude Code, and Windsurf to query video transcripts and notes directly. |

---

## Downloads & Installation

Visit the **[GitHub Releases Page](https://github.com/977star/DeepVid/releases/latest)** to download the latest official packages:

| Platform | Recommended Device | Package Format | Direct Link |
| :--- | :--- | :--- | :--- |
| **macOS (Apple Silicon)** | Apple Silicon Mac (M1 / M2 / M3 / M4, macOS 12.0+) | `.dmg` Drag-and-Drop Image | [Download macOS App](https://github.com/977star/DeepVid/releases/latest) |
| **Windows (64-bit)** | Windows 10 / 11 64-bit | `.exe` Standard Installer | [Download Windows App](https://github.com/977star/DeepVid/releases/latest) |

---

## First Launch Guide (System Security Prompts)

DeepVid is a free and open-source project without a paid corporate certificate. Operating systems may show a security prompt upon first launch. Follow these simple steps:

### macOS: "App is damaged and can't be opened"

This is Apple Gatekeeper's standard notice for unnotarized open-source applications. The app is completely safe.

Open **Terminal**, paste and run this single command:

```bash
sudo xattr -rd com.apple.quarantine /Applications/DeepVid.app
```
*(Press Enter, type your Mac password, and open the app normally)*

---

### Windows: "Windows protected your PC"

This is Microsoft SmartScreen's default notice for new open-source executables.

In the prompt dialog, click **"More info"** ➔ click **"Run anyway"** to launch immediately.

---

## License

Distributed under the [MIT License](LICENSE).
