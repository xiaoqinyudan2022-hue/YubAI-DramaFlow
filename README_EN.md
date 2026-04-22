# 🎬 YubAI-DramaFlow

<h3 align="center">AI Drama Production Workflow | AI漫剧工作流</h3>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Video-ff6b6b?style=flat-square" alt="AI Video">
  <img src="https://img.shields.io/badge/License-MIT-33d1cc?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Version-1.0-ffd93d?style=flat-square" alt="Version">
</p>

<p align="center">
  📖 From story outline to video storyboard | 🎯 Boost your AI video generation success rate
</p>

<p align="center">
  <b>中文版</b> | <a href="./README_EN.md">English</a>
</p>

<p align="center">
  <img src="./assets/preview.png" alt="YubAI-DramaFlow Preview" width="100%">
</p>

---

## ✨ One-Line Introduction

**Get started with AI drama production quickly!** A proven 5-stage workflow that helps you systematically create AI dramas from scratch.

---

## 🎯 Core Pain Points & Solutions

**AI drama production is complex and you don't know where to start?** This workflow helps you get organized!

| Pain Point | Symptoms | Solution |
|:---:|----------|---------|
| 😵 **Don't know where to start** | Have ideas but don't know the first step | 5-stage workflow + Entry guide |
| 😫 **Inconsistent characters** | Same character looks different across shots | Style anchoring prompts + Reference images |
| 🎨 **Style inconsistency** | Different shots have mismatched styles | Style definition template + Style anchoring |
| 📝 **Unstable prompt quality** | Same description, different results | Standardized templates + Terminology library |
| ❓ **Don't know AI limitations** | Designed shots AI can't produce | AI generation difficulty assessment |
| 🔍 **Problems found too late** | Issues discovered in late stages | 5-stage self-check system |

---

## 🚀 Quick Start

### 1️⃣ Get the Project

**Option 1: Clone (Recommended)**

```bash
git clone https://github.com/your-username/YubAI-DramaFlow.git
cd YubAI-DramaFlow
```

**Option 2: Direct Download**

Click `Code` → `Download ZIP` in the top right corner, extract and use.

**What is this?**
- A **methodology toolkit** containing templates, guides, and examples
- No dependencies to install, download and use
- Works with your favorite AI agents (OpenClaw, Hermes Agent, Claude Code, etc.)

### 2️⃣ Where Should I Start?

```
┌─────────────────────────────────────────────────────────────────┐
│                    Choose Your Entry Point                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  📖 Have a story/novel to adapt?                                │
│     → [Web Novel Adaptation Guide](./references/网文改写指南.md)  │
│     → [Adaptation Template](./templates/网文改写模板.md)          │
│                                                                 │
│  🎨 Have a script, ready to produce?                            │
│     → [Style Definition Template](./templates/风格定义模板.md) 👈 Must do first! │
│     → [AI Feasibility Assessment](./templates/AI可行性评估模板.md)│
│     → [Character Design Template](./templates/人物设计模板.md)    │
│     → [Storyboard Template](./templates/分镜表模板.md)            │
│                                                                 │
│  🎬 Starting from scratch?                                      │
│     → [Quick Start Guide](./docs/快速开始.md)                    │
│     → [Story Outline Template](./templates/故事大纲模板.md)       │
│     → [Style Definition Template](./templates/风格定义模板.md)    │
│                                                                 │
│  ⚠️ First time, worried about pitfalls?                         │
│     → [Beginner's Guide](./docs/新手避坑指南.md) 👈 Must read!    │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

**💡 Key Tip: Style definition is the first step to ensure visual consistency!**
Don't skip the "Style Definition" phase, or you'll face serious style inconsistency issues later.

### 3️⃣ Core Workflow Overview

```
┌─────────────────────────────────────────────────────────────┐
│                AI Drama Production 5-Stage Workflow          │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  📚 【Stage 1: Story Layer】                                │
│     Story outline → Novel text → Professional script → AI feasibility │
│                                                             │
│  🎨 【Stage 2: Style Layer】                                │
│     Style definition → Style anchoring prompts → Reference images │
│                                                             │
│  ✏️  【Stage 3: Design Layer】                              │
│     Character design → Scene design → Asset library setup   │
│                                                             │
│  🎬  【Stage 4: Storyboard Layer】                          │
│     Storyboard script → Storyboard table → Static frame generation │
│                                                             │
│  🎥  【Stage 5: Video Layer】                               │
│     Video prompts → Video storyboard library → Final output │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Recommended Tools

> See [Tool Selection Guide](./docs/工具选择指南.md) for detailed comparison

### AI Script Writing (Top 3)

| Model | Strengths | Use Cases |
|------|------|----------|
| **Claude Opus 4.7** | Precise instruction following, rigorous logic | Script writing, dialogue design |
| **GPT-6** | 2M token context | Long stories, rapid iteration |
| **Gemini 3.1 Pro** | Strong reasoning, multimodal | Complex stories, novel adaptation |

### Text-to-Image Tools

| Priority | Tool | Strengths |
|--------|------|------|
| First choice | **GPT-Image-2** | Best prompt understanding, stable style |
| Second choice | **NanoBanana Series** | Photorealistic, good text rendering |
| Alternative | **Midjourney** | Artistic, diverse styles |
| Open source | **Flux** | Good hand rendering, customizable |

### Image-to-Video Tools

| Priority | Tool | Strengths |
|--------|------|------|
| Anticipated | **HappyHorse** | Next-gen model (upcoming) |
| First choice | **Seedance 2.0** | Stable output, comprehensive features |
| Second choice | **Kling O3** | 7-in-1 features, 4K output, native audio |
| Fast generation | **Vidu 2.0** | Ultra-fast, strong anime style |
| Action scenes | **Hailuo** | Good complex action handling |

---

## 📁 Project Structure

```
YubAI-DramaFlow/
├── 📄 README.md                    # Project description (Chinese)
├── 📄 README_EN.md                 # Project description (English)
├── 📜 LICENSE                      # MIT License
├── 🤝 CONTRIBUTING.md              # Contribution guide
├── 📚 docs/                        # Documentation
│   ├── 快速开始.md
│   ├── Quick_Start.md              # English version
│   ├── 工具选择指南.md
│   ├── 新手避坑指南.md
│   ├── 常见问题.md
│   └── 更新日志.md
├── 📋 templates/                   # Templates
│   ├── 风格定义模板.md              👈 Start here!
│   ├── 故事大纲模板.md
│   ├── 剧本格式模板.md
│   └── ... (9 templates total)
├── 📖 references/                  # Reference docs (10 docs)
├── 💡 examples/                    # Example project
│   └── 获得异能的那一天，我和校花成为了同桌/
│       ├── 故事大纲.md
│       ├── 剧本.md
│       ├── 风格定义.md
│       ├── 人物设计.md
│       ├── 场景设计.md
│       └── 分镜表.md
└── 🎨 assets/                      # Resources
    ├── logo.png
    ├── preview.png
    └── qrcode.jpg
```

---

## 🤝 Contributing

We welcome all contributions! See [Contributing Guide](./CONTRIBUTING.md).

**Ways to contribute:**
- 🐛 Submit Issues for bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🌐 Help with translations
- 🔧 Submit Pull Requests

---

## 📄 License

This project uses [MIT License](./LICENSE) - Free for commercial use, no authorization needed, just keep attribution.

---

## 👋 About the Author

> Created by **鱼摆摆 (YubAI)**, sharing AI video creation tips and tricks!

### 📺 Bilibili

[**@鱼摆摆喂**](https://space.bilibili.com/299467431) - AI content creator, sharing AI tools, video creation, and productivity tips

### 📱 WeChat Official Account

**「鱼摆摆喂」** - AI video creation tutorials, tool reviews, and practical case studies

<p align="left">
  <img src="./assets/qrcode.jpg" alt="WeChat QR Code" width="140">
</p>

> Scan to follow for more AI creation tips!

---

<p align="center">
  <sub>Made with ❤️ for AI Video Creators</sub>
</p>
