[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **حوّل الصور إلى فن. 10 مهارات ذكاء اصطناعي إبداعية للمصممين والمصورين والمبدعين.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ ما هذا

10 مهارات ذكاء اصطناعي تحول الصور إلى فن — ملصقات أفلام، أغلفة ألبومات، شعارات، محاكاة أفلام، والمزيد. كل مهارة تقدم لمساعدك الذكي أوامر مفصلة ولوحات ألوان وخطوات تفصيلية.

مستوحاة من [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) و [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine)، لكن تغطي نطاقاً إبداعياً أوسع.

## 🖼️ قبل وبعد

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

## 🎯 المهارات

| # | الفئة | المهارة | الوصف |
|---|-------|---------|-------|
| 1 | 🎬 تصميم الملصقات | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | جماليات ملصقات الأفلام من السبعينيات-الثمانينيات مع إضاءة درامية |
| 2 | 🎬 تصميم الملصقات | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | ملصقات سفر بأسلوب Art Deco و WPA مع أشكال هندسية جريئة |
| 3 | 🎬 تصميم الملصقات | [Music Album Cover](skills/海报设计/music-album-cover.md) | فن أغلفة ألبومات حسب النوع: هيب هوب، إلكتروني، جاز، روك، كلاسيكي |
| 4 | 📸 معالجة الصور | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 معالجة الصور | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie |
| 6 | 📸 معالجة الصور | [Light Painting](skills/摄影后期/light-painting.md) | خطوط ضوئية، مسارات نجوم، صوف فولاذي، تأثيرات نيون |
| 7 | 🎨 تصميم العلامات التجارية | [Logo Generation](skills/品牌设计/logo-generation.md) | شعارات بسيطة، هندسية، نصية، تصويرية، مجردية |
| 8 | 🎨 تصميم العلامات التجارية | [Brand Identity](skills/品牌设计/brand-identity.md) | أنظمة بصرية متكاملة: ألوان، خطوط، أنماط، تطبيقات |
| 9 | 📱 وسائل التواصل | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | تصاميم Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ الرسم التوضيحي | [Character Design](skills/插画创作/character-design.md) | أنمي، كرتون، بيكسل آرت، واقعي، تشيبи، ماسكوت، VTuber |

---

## 🚀 البدء السريع

### Cursor

انسخ أي ملف مهارة إلى دليل `.cursor/rules/` في مشروعك:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

ثم ارجع إليه في محادثتك مع مساعد Cursor الذكي.

### Claude Code

أضف مهارة إلى `CLAUDE.md` في مشروعك أو انسخ إلى `.claude/`:

```bash
# أضف إلى CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# أو ارجع مباشرة
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

انسخ ملفات المهارات إلى مشروعك وارجع إليها:

```bash
# انسخ إلى المشروع
cp -r skills/ .kimi/skills/

# أو استخدم المهارة مباشرة في المحادثة:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### أي مساعد ذكاء اصطناعي

كل ملف مهارة هو وثيقة markdown مستقلة. يمكنك:

1. **لصق المهارة بالكامل** كسياق في محادثتك
3. **الجمع بين عدة مهارات** للمشاريع المعقدة

---

## 📁 هيكل المشروع

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # تصميم الملصقات
│   │   ├── retro-movie-poster.md
│   │   ├── travel-poster.md
│   │   └── music-album-cover.md
│   ├── 摄影后期/                    # معالجة الصور
│   │   ├── film-emulation.md
│   │   ├── cinematic-grade.md
│   │   └── light-painting.md
│   ├── 品牌设计/                    # تصميم العلامات التجارية
│   │   ├── logo-generation.md
│   │   └── brand-identity.md
│   ├── 社交媒体/                    # وسائل التواصل
│   │   └── content-creator-pack.md
│   └── 插画创作/                    # الرسم التوضيحي
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

## 🎤 نظرة عميقة على المهارات

كل ملف مهارة يتبع بنية متسقة:

- **متى تُستخدم** — مشغلات واضحة لتحديد متى تُطبق المهارة
- **فلسفة التصميم** — المبادئ الأساسية والقرارات الجمالية
- **أولويات القرار** — قائمة مرتبة بالأولويات الإبداعية
- **تعليمات لمساعد الذكاء الاصطناعي** — سير عمل خطوة بخطوة
- **قوالب الأوامر** — أوامر جاهزة للاستخدام مع متغيرات قابلة للتخصيص
- **مرجع الأسلوب** — لوحات ألوان، طباغة، أدلة تركيب
- **الأنماط الشائعة** — نهج مستخدمة بشكل متكرر
- **أخطاء يجب تجنبها** — أخطاء شائعة وكيفية تجنبها

### مثال الاستخدام

```
أنت: "حوّل هذه الصورة من العطلة إلى ملصق حديقة وطنية بأسلوب WPA"

الذكاء الاصطناعي (باستخدام مهارة travel-poster):
→ يحدد المعلم والمناظر الطبيعية
→ يختار أسلوب حقبة WPA مع نسيج طباعة كتلي
→ يطبق لوحة ألوان ترابية مناسبة للمنطقة
→ يضيف طباعة مناسبة للفترة الزمنية
→ يُصدر ملصق سفر كلاسيكي
```

---

## 🔗 انظر أيضاً

مشاريع ذات صلة في منظومة مهارات الذكاء الاصطناعي:

| المشروع | الوصف |
|---------|-------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | مجموعة مهارات ذكاء اصطناعي متعددة الاستخدامات |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | مهارات ذكاء اصطناعي لتحرير وإنتاج الفيديو |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | قواعد وإعدادات ذكاء اصطناعي منتقاة |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | تحقق واختبر إعدادات مهاراتك |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | توليد رسائل ارتباط بالذكاء الاصطناعي |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | مجموعة خوادم MCP لأدوات الذكاء الاصطناعي |

---

## 🤝 المساهمة

نرحب بالمساهمات! انظر [CONTRIBUTING.md](CONTRIBUTING.md) للإرشادات.

هل تريد إضافة مهارة إبداعية جديدة؟ افتح [مشكلة](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) أو قدّم PR.

---

## 📄 الترخيص

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
