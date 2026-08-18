[中文版](README.zh.md)

# Awesome Creative Skills 🎨

> **Transform photos into art. 10 creative AI skills for designers, photographers, and creators.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ What This Is

10 AI skills that turn photos into art — movie posters, album covers, logos, film emulation, and more. Each skill gives your AI assistant exact prompts, color palettes, and step-by-step instructions.

Inspired by [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) and [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), but covering a wider creative range.

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
