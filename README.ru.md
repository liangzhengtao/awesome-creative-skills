[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **Превратите фотографии в искусство. 10 креативных ИИ-навыков для дизайнеров, фотографов и творцов.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ Что это такое

10 ИИ-навыков, превращающих фотографии в искусство — постеры фильмов, обложки альбомов, логотипы, эмуляция плёнки и многое другое. Каждый навык предоставляет вашему ИИ-ассистенту точные промпты, палитры цветов и пошаговые инструкции.

Вдохновлено [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) и [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), но охватывает более широкий творческий диапазон.

## 🖼️ До и После

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

## 🎯 Навыки

| # | Категория | Навык | Описание |
|---|-----------|-------|----------|
| 1 | 🎬 Постеры | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | Эстетика постеров 70-80-х с аэрографией и драматичным освещением |
| 2 | 🎬 Постеры | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | Путеводные постеры в стиле Art Deco и WPA с геометрическими формами |
| 3 | 🎬 Постеры | [Music Album Cover](skills/海报设计/music-album-cover.md) | Обложки альбомов по жанрам: хип-хоп, электроника, джаз, рок, классика |
| 4 | 📸 Обработка фото | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 Обработка фото | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie |
| 6 | 📸 Обработка фото | [Light Painting](skills/摄影后期/light-painting.md) | Световые следы, звёздные тропы, стальная вата, неоновые эффекты |
| 7 | 🎨 Бренд-дизайн | [Logo Generation](skills/品牌设计/logo-generation.md) | Минималистичные, геометрические, текстовые, образные, абстрактные логотипы |
| 8 | 🎨 Бренд-дизайн | [Brand Identity](skills/品牌设计/brand-identity.md) | Полные визуальные системы: цвета, шрифты, паттерны, применения |
| 9 | 📱 Соцсети | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | Дизайн для Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ Иллюстрация | [Character Design](skills/插画创作/character-design.md) | Аниме, мультфильмы, пиксель-арт, реализм, чиби, маскоты, VTuber аватары |

---

## 🚀 Быстрый старт

### Cursor

Скопируйте файл навыка в директорию `.cursor/rules/` вашего проекта:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Затем укажите его в разговоре с ИИ-ассистентом Cursor.

### Claude Code

Добавьте навык в `CLAUDE.md` вашего проекта или скопируйте в `.claude/`:

```bash
# Добавить в CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# Или указать напрямую
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Скопируйте файлы навыков в проект и ссылайтесь на них:

```bash
# Скопировать в проект
cp -r skills/ .kimi/skills/

# Или использовать навык напрямую в разговоре:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Любой ИИ-ассистент

Каждый файл навыка — самостоятельный документ Markdown. Вы можете:

1. **Вставить весь навык** как контекст в разговор
2. **Ссылаться на конкретные разделы** (шаблоны промптов, стилевые гайды)
3. **Комбинировать несколько навыков** для сложных проектов

---

## 📁 Структура проекта

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Постеры
│   │   ├── retro-movie-poster.md
│   │   ├── travel-poster.md
│   │   └── music-album-cover.md
│   ├── 摄影后期/                    # Обработка фото
│   │   ├── film-emulation.md
│   │   ├── cinematic-grade.md
│   │   └── light-painting.md
│   ├── 品牌设计/                    # Бренд-дизайн
│   │   ├── logo-generation.md
│   │   └── brand-identity.md
│   ├── 社交媒体/                    # Соцсети
│   │   └── content-creator-pack.md
│   └── 插画创作/                    # Иллюстрация
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

## 🎨 Подробнее о навыках

Каждый файл навыка следует единообразной структуре:

- **Когда использовать** — Чёткие триггеры применения навыка
- **Философия дизайна** — Ключевые принципы и эстетические решения
- **Приоритеты решений** — Упорядоченный список творческих приоритетов
- **Инструкции для ИИ-ассистента** — Пошаговый рабочий процесс
- **Шаблоны промптов** — Готовые к использованию промпты с настраиваемыми переменными
- **Стилевая справка** — Палитры цветов, типографика, композиционные гайды
- **Типичные паттерны** — Часто используемые подходы
- **Подводные камни** — Типичные ошибки и как их избежать

### Пример использования

```
Вы: "Превратите этот отпускной снимок в постер национального парка в стиле WPA"

ИИ (используя навык travel-poster):
→ Определяет достопримечательность и ландшафт
→ Выбирает стиль эпохи WPA с текстурой блочной печати
→ Применяет подходящую земляную палитру
→ Добавляет типографику соответствующей эпохи
→ Выдаёт винтажный путеводный постер
```

---

## 🔗 Смотрите также

Связанные проекты в экосистеме ИИ-навыков:

| Проект | Описание |
|--------|----------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | Коллекция универсальных ИИ-навыков |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | ИИ-навыки для видеомонтажа и продакшена |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Избранные ИИ-правила и конфигурации |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | Проверка и тестирование ваших ИИ-навыков |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | Генерация сообщений коммитов с помощью ИИ |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | Коллекция MCP-серверов для ИИ-инструментов |

---

## 🤝 Участие в проекте

Приветствуются вклады! См. [CONTRIBUTING.md](CONTRIBUTING.md) для рекомендаций.

Хотите добавить новый креативный навык? Откройте [issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) или отправьте PR.

---

## 📄 Лицензия

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
