[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **Verwandeln Sie Fotos in Kunst. 10 kreative KI-Fähigkeiten für Designer, Fotografen und Kreative.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ Was das ist

10 KI-Fähigkeiten, die Fotos in Kunst verwandeln — Filmplakate, Albumcover, Logos, Filmemulation und mehr. Jede Fähigkeit liefert Ihrem KI-Assistenten präzise Prompts, Farbpaletten und Schritt-für-Schritt-Anleitungen.

Inspiriert von [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) und [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), aber mit einem breiteren kreativen Spektrum.

## 🖼️ Vorher & Nachher

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

## 🎯 Fähigkeiten

| # | Kategorie | Fähigkeit | Beschreibung |
|---|-----------|----------|-------------|
| 1 | 🎬 Plakatgestaltung | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | Filmplakat-Ästhetik der 70er-80er mit Airbrush und dramatischer Beleuchtung |
| 2 | 🎬 Plakatgestaltung | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | Art-Deco- und WPA-Reiseplakate mit kräftigen geometrischen Formen |
| 3 | 🎬 Plakatgestaltung | [Music Album Cover](skills/海报设计/music-album-cover.md) | Genre-spezifische Albumcover: Hip-Hop, Elektronik, Jazz, Rock, Klassik |
| 4 | 📸 Nachbearbeitung | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 Nachbearbeitung | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie Looks |
| 6 | 📸 Nachbearbeitung | [Light Painting](skills/摄影后期/light-painting.md) | Lichtspuren, Sternspuren, Stahlwolle, Neon-Effekte |
| 7 | 🎨 Markendesign | [Logo Generation](skills/品牌设计/logo-generation.md) | Minimalistische, geometrische, Wort-, Bild- und abstrakte Logos |
| 8 | 🎨 Markendesign | [Brand Identity](skills/品牌设计/brand-identity.md) | Vollständige visuelle Systeme: Farben, Schriften, Muster, Anwendungen |
| 9 | 📱 Soziale Medien | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | Designs für Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ Illustration | [Character Design](skills/插画创作/character-design.md) | Anime, Cartoon, Pixel-Art, Realistisch, Chibi, Maskottchen, VTuber-Avatare |

---

## 🚀 Schnellstart

### Cursor

Kopieren Sie eine Fähigkeitsdatei in das `.cursor/rules/`-Verzeichnis Ihres Projekts:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Verweisen Sie dann in Ihrem Gespräch mit dem KI-Assistenten von Cursor darauf.

### Claude Code

Fügen Sie eine Fähigkeit zu Ihrer `CLAUDE.md` hinzu oder kopieren Sie sie nach `.claude/`:

```bash
# Zu CLAUDE.md hinzufügen
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# Oder direkt referenzieren
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Kopieren Sie Fähigkeitsdateien in Ihr Projekt und referenzieren Sie diese:

```bash
# In Projekt kopieren
cp -r skills/ .kimi/skills/

# Oder direkt im Gespräch nutzen:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Jeder KI-Assistent

Jede Fähigkeitsdatei ist ein eigenständiges Markdown-Dokument. Sie können:

1. **Die gesamte Fähigkeit** als Kontext in Ihr Gespräch einfügen
2. **Bestimmte Abschnitte referenzieren** (Prompt-Templates, Style-Guides)
3. **Mehrere Fähigkeiten kombinieren** für komplexe Projekte

---

## 📁 Projektstruktur

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Plakatgestaltung
│   │   ├── retro-movie-poster.md
│   │   ├── travel-poster.md
│   │   └── music-album-cover.md
│   ├── 摄影后期/                    # Nachbearbeitung
│   │   ├── film-emulation.md
│   │   ├── cinematic-grade.md
│   │   └── light-painting.md
│   ├── 品牌设计/                    # Markendesign
│   │   ├── logo-generation.md
│   │   └── brand-identity.md
│   ├── 社交媒体/                    # Soziale Medien
│   │   └── content-creator-pack.md
│   └── 插画创作/                    # Illustration
│       └── character-design.md
├── .github/
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
├── LICENSE
└── .gitignore
```

---

## 🎨 Fähigkeiten im Detail

Jede Fähigkeitsdatei folgt einer einheitlichen Struktur:

- **Wann verwenden** — Klare Auslöser für die Anwendung der Fähigkeit
- **Designphilosophie** — Kernprinzipien und ästhetische Entscheidungen
- **Entscheidungsprioritäten** — Geordnete Liste kreativer Prioritäten
- **Anweisungen für den KI-Assistenten** — Schritt-für-Schritt-Workflow
- **Prompt-Templates** — Sofort einsetzbare Prompts mit anpassbaren Variablen
- **Stilreferenz** — Farbpaletten, Typografie, Kompositionsguides
- **Häufige Muster** — Oft verwendete Ansätze
- **Fallstricke vermeiden** — Häufige Fehler und wie man sie vermeidet

### Beispiel-Nutzung

```
Sie: "Verwandeln Sie dieses Urlaubsfoto in ein WPA-Nationalpark-Plakat"

KI (mit travel-poster Fähigkeit):
→ Identifiziert das Wahrzeichen und die Landschaft
→ Wählt WPA-Stil mit Blockdrucktextur
→ Wendet regionale Erdtöne an
→ Fügt zeitgenössische Typografie hinzu
→ Erstellt ein Vintage-Reiseplakat
```

---

## 🔗 Siehe auch

Verwandte Projekte im KI-Fähigkeiten-Ökosystem:

| Projekt | Beschreibung |
|---------|-------------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | Sammlung allgemeiner KI-Fähigkeiten |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | KI-Fähigkeiten für Videoschnitt und Produktion |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Kuratierte KI-Regeln und Konfigurationen |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | KI-Fähigkeits-Setup validieren und testen |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | KI-gestützte Commit-Message-Generierung |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | MCP-Server-Sammlung für KI-Tools |

---

## 🤝 Mitwirken

Wir freuen uns über Beiträge! Siehe [CONTRIBUTING.md](CONTRIBUTING.md) für Richtlinien.

Möchten Sie eine neue kreative Fähigkeit hinzufügen? Öffnen Sie ein [Issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) oder senden Sie einen PR.

---

## 📄 Lizenz

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
