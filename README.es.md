[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **Transforma tus fotos en arte. 10 habilidades IA creativas para diseñadores, fotógrafos y creadores.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ ¿Qué es esto?

10 habilidades IA que convierten fotos en arte: carteles de cine, portadas de discos, logos, emulación de película y más. Cada habilidad proporciona a tu asistente IA prompts precisos, paletas de color e instrucciones paso a paso.

Inspirado en [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) y [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), pero abarcando un rango creativo más amplio.

## 🖼️ Antes y Después

```
Foto original → Cartel de cine retro     Foto original → Cartel de viaje vintage
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ╔══════════╗ │    │          │   │  ╔════════╗  │
│  📷      │ → │ ║ 🎬 HERO  ║ │    │  📷      │ → │  ║ PARIS  ║  │
│  selfie  │   │ ║  MOVIE   ║ │    │  landmark │   │  ║ TRAVEL ║  │
│          │   │ ╚══════════╝ │    │          │   │  ╚════════╝  │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘

Foto original → Portada de álbum         Foto original → Logo de marca
┌──────────┐   ┌──────────────┐    ┌──────────┐   ┌──────────────┐
│          │   │ ┌──────────┐ │    │          │   │              │
│  📷      │ → │ │  ♪ ALBUM │ │    │  📷      │ → │    [LOGO]    │
│  portrait │   │ │   ART    │ │    │  sketch  │   │              │
│          │   │ └──────────┘ │    │          │   │              │
└──────────┘   └──────────────┘    └──────────┘   └──────────────┘
```

---

## 🎯 Habilidades

| # | Categoría | Habilidad | Descripción |
|---|----------|-------|-------------|
| 1 | 🎬 Carteles | [Cartel de cine retro](skills/海报设计/retro-movie-poster.md) | Estética de carteles de los años 70-80, aerógrafo, iluminación dramática |
| 2 | 🎬 Carteles | [Cartel de viaje vintage](skills/海报设计/travel-poster.md) | Carteles de viaje Art Déco y era WPA con formas geométricas audaces |
| 3 | 🎬 Carteles | [Portada de álbum musical](skills/海报设计/music-album-cover.md) | Arte de portada por género: hip-hop, electrónica, jazz, rock, clásica |
| 4 | 📸 Edición fotográfica | [Emulación de película](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerrotipo |
| 5 | 📸 Edición fotográfica | [Etalaje cinematográfico](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, estilos à la Amélie |
| 6 | 📸 Edición fotográfica | [Pintura de luz](skills/摄影后期/light-painting.md) | Estelas de luz, estelas de estrellas, lana de acero, efectos de neón |
| 7 | 🎨 Diseño de marca | [Generación de logo](skills/品牌设计/logo-generation.md) | Logos minimalistas, geométricos, tipográficos, pictóricos, abstractos |
| 8 | 🎨 Diseño de marca | [Identidad de marca](skills/品牌设计/brand-identity.md) | Sistemas visuales completos: colores, fuentes, patrones, aplicaciones |
| 9 | 📱 Redes sociales | [Pack de creador de contenido](skills/社交媒体/content-creator-pack.md) | Diseños para Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ Ilustración | [Diseño de personajes](skills/插画创作/character-design.md) | Anime, cartoon, pixel art, realista, chibi, mascota, avatares VTuber |

---

## 🚀 Inicio rápido

### Cursor

Copia un archivo de habilidad al directorio `.cursor/rules/` de tu proyecto:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Luego haz referencia a él en tu conversación con el asistente IA de Cursor.

### Claude Code

Añade una habilidad al `CLAUDE.md` de tu proyecto o cópiala a `.claude/`:

```bash
# Añadir a CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# O hacer referencia directamente
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Copia los archivos de habilidad a tu proyecto y haz referencia a ellos:

```bash
# Copiar al proyecto
cp -r skills/ .kimi/skills/

# O usar la habilidad directamente en la conversación:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Cualquier asistente IA

Cada archivo de habilidad es un documento Markdown independiente. Puedes:

1. **Pegar la habilidad completa** en tu conversación como contexto
2. **Referenciar secciones específicas** (plantillas de prompts, guías de estilo)
3. **Combinar múltiples habilidades** para proyectos complejos

---

## 📁 Estructura del proyecto

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Diseño de carteles
│   │   ├── retro-movie-poster.md   # Estilo cartel de cine de los 70-80
│   │   ├── travel-poster.md        # Carteles de viaje Art Déco y WPA
│   │   └── music-album-cover.md    # Portadas de álbum multi-género
│   ├── 摄影后期/                    # Edición fotográfica
│   │   ├── film-emulation.md       # Emulación de película analógica
│   │   ├── cinematic-grade.md      # Etalaje de color hollywoodense
│   │   └── light-painting.md       # Efectos de luz de exposición larga
│   ├── 品牌设计/                    # Diseño de marca
│   │   ├── logo-generation.md      # Creación de logos multi-estilo
│   │   └── brand-identity.md       # Sistemas de identidad completos
│   ├── 社交媒体/                    # Redes sociales
│   │   └── content-creator-pack.md # Diseño de contenido multi-plataforma
│   └── 插画创作/                    # Ilustración
│       └── character-design.md     # Diseño de personajes y avatares
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

## 🎨 Análisis de habilidades

Cada archivo de habilidad sigue una estructura coherente:

- **Cuándo usarla** — Desencadenantes claros para su aplicación
- **Filosofía de diseño** — Principios fundamentales y decisiones estéticas
- **Prioridades de decisión** — Lista ordenada de prioridades creativas
- **Instrucciones para el asistente IA** — Flujo de trabajo paso a paso
- **Plantillas de prompts** — Prompts listos para usar con variables personalizables
- **Referencias de estilo** — Paletas de colores, tipografía, guías de composición
- **Patrones comunes** — Enfoques frecuentemente utilizados
- **Errores comunes** — Errores habituales y cómo evitarlos

### Ejemplo de uso

```
Tú: "Transforma esta foto de vacaciones en un cartel WPA de parque nacional"

IA (usando la habilidad travel-poster):
→ Identifica el monumento y el paisaje
→ Selecciona el estilo era WPA con textura de impresión en bloque
→ Aplica una paleta de tonos tierra apropiada para la región
→ Añade tipografía fiel a la época
→ Genera un cartel de viaje vintage
```

---

## 🔗 Ver también

Proyectos relacionados en el ecosistema de habilidades IA:

| Proyecto | Descripción |
|---------|-------------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | Colección de habilidades IA de propósito general |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | Habilidades IA para edición y producción de vídeo |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Reglas y configuraciones IA seleccionadas |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | Valida y prueba tus configuraciones de habilidades IA |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | Generación de mensajes de commit con IA |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | Colección de servidores MCP para herramientas IA |

---

## 🤝 Contribuir

¡Aceptamos contribuciones! Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para las directrices.

¿Quieres añadir una nueva habilidad creativa? Abre un [issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) o envía un PR.

---

## 📄 Licencia

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
