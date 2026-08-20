[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **Transformez vos photos en œuvres d'art. 10 compétences IA créatives pour les designers, photographes et créateurs.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ Présentation

10 compétences IA qui transforment des photos en œuvres d'art — affiches de cinéma, pochettes d'album, logos, émulation de pellicule, et plus encore. Chaque compétence fournit à votre assistant IA des prompts précis, des palettes de couleurs et des instructions pas à pas.

Inspiré par [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) et [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), mais couvrant un éventail créatif plus large.

## 🖼️ Avant / Après

```
Photo brute → Affiche de film rétro     Photo brute → Affiche de voyage vintage
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ╔══════════╗ │    │          │   │  ╔════════╗  │
│  📷      │ → │ ║ 🎬 HERO  ║ │    │  📷      │ → │  ║ PARIS  ║  │
│  selfie  │   │ ║  MOVIE   ║ │    │  landmark │   │  ║ TRAVEL ║  │
│          │   │ ╚══════════╝ │    │          │   │  ╚════════╝  │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘

Photo brute → Pochette d'album          Photo brute → Logo de marque
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ┌──────────┐ │    │          │   │              │
│  📷      │ → │ │  ♪ ALBUM │ │    │  📷      │ → │    [LOGO]    │
│  portrait │   │ │   ART    │ │    │  sketch  │   │              │
│          │   │ └──────────┘ │    │          │   │              │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘
```

---

## 🎯 Compétences

| # | Catégorie | Compétence | Description |
|---|----------|-------|-------------|
| 1 | 🎬 Affiches | [Affiche de film rétro](skills/海报设计/retro-movie-poster.md) | Esthétique des affiches des années 70-80, aérographe, éclairage dramatique |
| 2 | 🎬 Affiches | [Affiche de voyage vintage](skills/海报设计/travel-poster.md) | Affiches de voyage Art déco et ère WPA, formes géométriques audacieuses |
| 3 | 🎬 Affiches | [Pochette d'album musical](skills/海报设计/music-album-cover.md) | Pochettes par genre : hip-hop, électro, jazz, rock, classique |
| 4 | 📸 Retouche photo | [Émulation de pellicule](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerréotype |
| 5 | 📸 Retouche photo | [Étalonnage cinématographique](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, looks à la Amélie |
| 6 | 📸 Retouche photo | [Peinture lumineuse](skills/摄影后期/light-painting.md) | Traînées de lumière, filé d'étoiles, laine d'acier, effets néon |
| 7 | 🎨 Identité visuelle | [Génération de logo](skills/品牌设计/logo-generation.md) | Logos minimalistes, géométriques, typographiques, figuratifs, abstraits |
| 8 | 🎨 Identité visuelle | [Charte graphique complète](skills/品牌设计/brand-identity.md) | Systèmes visuels complets : couleurs, typographies, motifs, applications |
| 9 | 📱 Réseaux sociaux | [Pack créateur de contenu](skills/社交媒体/content-creator-pack.md) | Designs pour Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ Illustration | [Design de personnage](skills/插画创作/character-design.md) | Anime, cartoon, pixel art, réaliste, chibi, mascotte, avatars VTuber |

---

## 🚀 Démarrage rapide

### Cursor

Copiez un fichier de compétence dans le répertoire `.cursor/rules/` de votre projet :

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Puis référencez-le dans votre conversation avec l'assistant IA de Cursor.

### Claude Code

Ajoutez une compétence au `CLAUDE.md` de votre projet ou copiez dans `.claude/` :

```bash
# Ajouter à CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# Ou référencer directement
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Copiez les fichiers de compétence dans votre projet et référencez-les :

```bash
# Copier dans le projet
cp -r skills/ .kimi/skills/

# Ou utiliser la compétence directement dans la conversation :
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Tout assistant IA

Chaque fichier de compétence est un document Markdown autonome. Vous pouvez :

1. **Coller la compétence entière** dans votre conversation comme contexte
2. **Référencer des sections spécifiques** (modèles de prompts, guides de style)
3. **Combiner plusieurs compétences** pour des projets complexes

---

## 📁 Structure du projet

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Design d'affiches
│   │   ├── retro-movie-poster.md   # Style affiche de film des années 70-80
│   │   ├── travel-poster.md        # Affiches de voyage Art déco & WPA
│   │   └── music-album-cover.md    # Pochettes d'album multi-genres
│   ├── 摄影后期/                    # Retouche photo
│   │   ├── film-emulation.md       # Émulation de pellicule argentique
│   │   ├── cinematic-grade.md      # Étalonnage Hollywoodien
│   │   └── light-painting.md       # Effets lumineux de pose longue
│   ├── 品牌设计/                    # Identité visuelle
│   │   ├── logo-generation.md      # Création de logos multi-styles
│   │   └── brand-identity.md       # Systèmes d'identité complets
│   ├── 社交媒体/                    # Réseaux sociaux
│   │   └── content-creator-pack.md # Design de contenu multi-plateforme
│   └── 插画创作/                    # Illustration
│       └── character-design.md     # Design de personnages et avatars
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

## 🎨 Approfondissement des compétences

Chaque fichier de compétence suit une structure cohérente :

- **Quand l'utiliser** — Déclencheurs clairs pour l'application de la compétence
- **Philosophie du design** — Principes fondamentaux et décisions esthétiques
- **Priorités de décision** — Liste ordonnée des priorités créatives
- **Instructions pour l'assistant IA** — Workflow pas à pas
- **Modèles de prompts** — Prompts prêts à l'emploi avec variables personnalisables
- **Références de style** — Palettes de couleurs, typographies, guides de composition
- **Motifs courants** — Approches fréquemment utilisées
- **Écueils à éviter** — Erreurs courantes et comment les éviter

### Exemple d'utilisation

```
Vous : « Transforme cette photo de vacances en affiche WPA de parc national »

IA (avec la compétence travel-poster) :
→ Identifie le monument et le paysage
→ Sélectionne le style ère WPA avec texture d'impression en bloc
→ Applique une palette de tons terreux adaptée à la région
→ Ajoute une typographie fidèle à l'époque
→ Génère une affiche de voyage vintage
```

---

## 🔗 Voir aussi

Projets connexes dans l'écosystème des compétences IA :

| Projet | Description |
|---------|-------------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | Collection de compétences IA polyvalentes |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | Compétences IA pour le montage et la production vidéo |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Règles et configurations IA soigneusement sélectionnées |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | Validez et testez vos configurations de compétences IA |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | Génération de messages de commit par IA |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | Collection de serveurs MCP pour outils IA |

---

## 🤝 Contribuer

Nous accueillons les contributions ! Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour les directives.

Vous souhaitez ajouter une nouvelle compétence créative ? Ouvrez une [issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) ou soumettez une PR.

---

## 📄 Licence

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
