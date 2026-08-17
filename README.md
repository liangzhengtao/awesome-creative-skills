# Awesome Creative Skills 🎨

> **Transform photos into art. 10 creative AI skills for designers, photographers, and creators.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

> **将照片变成艺术。10个创意AI技能，为设计师、摄影师和创作者打造。**

[中文版本](#中文版本)

---

## ✨ What This Is

A curated collection of AI creative design skills that transform ordinary photos into stunning artistic creations. Each skill provides detailed instructions, prompt templates, style references, and best practices for AI assistants to produce professional-quality creative work.

Like [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) and [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), these skills focus on **photo-to-art transformation** — but across a much broader creative spectrum.

## 🖼️ Before & After

```
Raw photo → Retro Movie Poster     Raw photo → Vintage Travel Poster
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ╔══════════╗ │    │          │   │  ╔════════╗  │
│  📷      │ → │ ║ 🎬 HERO  ║ │    │  📷      │ → │  ║ PARIS  ║  │
│  selfie  │   │ ║  MOVIE   ║ │    │  landmark │   │  ║ TRAVEL ║  │
│          │   │ ╚══════════╝ │    │          │   │  ╚════════╝  │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘

Raw photo → Album Cover            Raw photo → Brand Logo
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ┌──────────┐ │    │          │   │              │
│  📷      │ → │ │  ♪ ALBUM │ │    │  📷      │ → │    [LOGO]    │
│  portrait │   │ │   ART    │ │    │  sketch  │   │              │
│          │   │ └──────────┘ │    │          │   │              │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘
```

---

## 🎯 Skills

| # | Category | Skill | Description |
|---|----------|-------|-------------|
| 1 | 🎬 海报设计 | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | 1970s-80s movie poster aesthetic with airbrushed, dramatic lighting |
| 2 | 🎬 海报设计 | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | Art Deco, WPA-era travel posters with bold geometric shapes |
| 3 | 🎬 海报设计 | [Music Album Cover](skills/海报设计/music-album-cover.md) | Genre-specific album art: hip-hop, electronic, jazz, rock, classical |
| 4 | 📸 摄影后期 | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 摄影后期 | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie looks |
| 6 | 📸 摄影后期 | [Light Painting](skills/摄影后期/light-painting.md) | Light trails, star trails, steel wool, neon effects |
| 7 | 🎨 品牌设计 | [Logo Generation](skills/品牌设计/logo-generation.md) | Minimal, geometric, wordmark, pictorial, abstract logos |
| 8 | 🎨 品牌设计 | [Brand Identity](skills/品牌设计/brand-identity.md) | Complete visual systems: colors, fonts, patterns, applications |
| 9 | 📱 社交媒体 | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest designs |
| 10 | ✏️ 插画创作 | [Character Design](skills/插画创作/character-design.md) | Anime, cartoon, pixel art, realistic, chibi, mascot, VTuber avatars |

---

## 🚀 Quick Start

### Cursor

Copy any skill file to your project's `.cursor/rules/` directory:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Then reference it in your conversation with Cursor's AI assistant.

### Claude Code

Add a skill to your project's `CLAUDE.md` or copy to `.claude/`:

```bash
# Add to CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# Or reference directly
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Copy skill files to your project and reference them:

```bash
# Copy to project
cp -r skills/ .kimi/skills/

# Or use the skill directly in conversation:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Any AI Assistant

Each skill file is a self-contained markdown document. You can:

1. **Paste the entire skill** into your conversation as context
2. **Reference specific sections** (prompt templates, style guides)
3. **Combine multiple skills** for complex projects

---

## 📁 Project Structure

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Poster Design
│   │   ├── retro-movie-poster.md   # 1970s-80s movie poster style
│   │   ├── travel-poster.md        # Art Deco & WPA travel posters
│   │   └── music-album-cover.md    # Multi-genre album art
│   ├── 摄影后期/                    # Photo Post-processing
│   │   ├── film-emulation.md       # Analog film stock emulation
│   │   ├── cinematic-grade.md      # Hollywood color grading
│   │   └── light-painting.md       # Long exposure light effects
│   ├── 品牌设计/                    # Brand Design
│   │   ├── logo-generation.md      # Logo creation across styles
│   │   └── brand-identity.md       # Complete identity systems
│   ├── 社交媒体/                    # Social Media
│   │   └── content-creator-pack.md # Multi-platform content design
│   └── 插画创作/                    # Illustration
│       └── character-design.md     # Character & avatar design
├── .github/
│   ├── workflows/ci.yml
│   ├── ISSUE_TEMPLATE/
│   │   └── request_skill.md
│   └── pull_request_template.md
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
├── LICENSE
└── .gitignore
```

---

## 🎨 Skill Deep Dive

Each skill file follows a consistent structure:

- **When to Use** — Clear triggers for when the skill applies
- **Design Philosophy** — Core principles and aesthetic decisions
- **Decision Priority** — Ordered list of creative priorities
- **Instructions for AI Assistant** — Step-by-step workflow
- **Prompt Templates** — Ready-to-use prompts with customizable variables
- **Style Reference** — Color palettes, typography, composition guides
- **Common Patterns** — Frequently used approaches
- **Pitfalls to Avoid** — Common mistakes and how to avoid them

### Example Usage

```
You: "Transform this vacation photo into a WPA National Park poster"

AI (using travel-poster skill):
→ Identifies the landmark and landscape
→ Selects WPA-era style with block print texture
→ Applies region-appropriate earth tone palette
→ Adds period-correct typography
→ Outputs a vintage travel poster
```

---

## 🔗 See Also

Related projects in the AI skills ecosystem:

| Project | Description |
|---------|-------------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | A collection of general-purpose AI skills |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | AI skills for video editing and production |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Curated AI rules and configurations |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | Validate and test your AI skill setups |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | AI-powered commit message generation |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | MCP server collection for AI tools |

---

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Want to add a new creative skill? Open an [issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) or submit a PR.

---

## 📄 License

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---

---

# 中文版本

> **将照片变成艺术。10个创意AI技能，为设计师、摄影师和创作者打造。**

## ✨ 这是什么

一个精心策划的AI创意设计技能合集，能将普通照片转化为令人惊叹的艺术作品。每个技能都提供详细的指令、提示词模板、风格参考和最佳实践，帮助AI助手创作出专业品质的创意作品。

与 [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) 和 [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine) 类似，这些技能专注于**照片到艺术的转化** —— 但覆盖更广泛的创意领域。

## 🎯 技能列表

| # | 分类 | 技能 | 描述 |
|---|------|------|------|
| 1 | 🎬 海报设计 | [复古电影海报](skills/海报设计/retro-movie-poster.md) | 70-80年代电影海报美学，喷绘风格，戏剧性光影 |
| 2 | 🎬 海报设计 | [复古旅行海报](skills/海报设计/travel-poster.md) | 装饰艺术、WPA时代旅行海报，大胆几何图形 |
| 3 | 🎬 海报设计 | [音乐专辑封面](skills/海报设计/music-album-cover.md) | 多风格专辑封面：嘻哈、电子、爵士、摇滚、古典 |
| 4 | 📸 摄影后期 | [胶片模拟](skills/摄影后期/film-emulation.md) | 柯达Portra、富士Velvia、伊尔福HP5、宝丽来 |
| 5 | 📸 摄影后期 | [电影调色](skills/摄影后期/cinematic-grade.md) | 青橙色调、漂白旁路、银翼杀手2049、天使爱美丽 |
| 6 | 📸 摄影后期 | [光绘摄影](skills/摄影后期/light-painting.md) | 光轨、星轨、钢丝棉、霓虹效果 |
| 7 | 🎨 品牌设计 | [Logo生成](skills/品牌设计/logo-generation.md) | 极简、几何、文字标、图形标、抽象Logo |
| 8 | 🎨 品牌设计 | [品牌视觉系统](skills/品牌设计/brand-identity.md) | 完整视觉系统：色彩、字体、图案、应用 |
| 9 | 📱 社交媒体 | [内容创作者套装](skills/社交媒体/content-creator-pack.md) | Instagram、YouTube、微博、小红书等平台设计 |
| 10 | ✏️ 插画创作 | [角色设计](skills/插画创作/character-design.md) | 动漫、卡通、像素画、写实、Q版、吉祥物、VTuber |

## 🚀 快速开始

### 在 Cursor 中使用

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

### 在 Claude Code 中使用

```bash
cat skills/摄影后期/film-emulation.md >> CLAUDE.md
```

### 在 Kimi Code 中使用

```bash
cp -r skills/ .kimi/skills/
```

### 在任何AI助手中使用

每个技能文件都是独立的Markdown文档，你可以：

1. **将整个技能粘贴到对话中**作为上下文
2. **引用特定章节**（提示词模板、风格指南）
3. **组合多个技能**来完成复杂项目

## 🤝 参与贡献

欢迎贡献！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解贡献指南。

想要添加新的创意技能？请提交 [Issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) 或 PR。

## 📄 许可证

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)
