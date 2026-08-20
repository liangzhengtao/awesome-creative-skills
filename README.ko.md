[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **사진을 예술로 변환하세요. 디자이너, 사진작가, 크리에이터를 위한 10가지 창작 AI 스킬.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ 이것이 무엇인가

사진을 예술로 바꾸는 10가지 AI 스킬 — 영화 포스터, 앨범 커버, 로고, 필름 에뮬레이션 등. 각 스킬은 AI 어시스턴트에게 정확한 프롬프트, 컬러 팔레트, 단계별 지침을 제공합니다.

[gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine)과 [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine)에서 영감을 받았지만, 더 넓은 창작 범위를 다룹니다.

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

## 🎯 스킬

| # | 카테고리 | 스킬 | 설명 |
|---|---------|------|------|
| 1 | 🎬 포스터 디자인 | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | 1970-80년대 영화 포스터 미학, 에어브러시 및 극적인 조명 |
| 2 | 🎬 포스터 디자인 | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | Art Deco, WPA 시대의 대담한 기하학적 형태의 여행 포스터 |
| 3 | 🎬 포스터 디자인 | [Music Album Cover](skills/海报设计/music-album-cover.md) | 장르별 앨범 아트: 힙합, 일렉트로닉, 재즈, 록, 클래식 |
| 4 | 📸 사진 후보정 | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 사진 후보정 | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie 룩 |
| 6 | 📸 사진 후보정 | [Light Painting](skills/摄影后期/light-painting.md) | 라이트 트레일, 스타 트레일, 스틸울, 네온 효과 |
| 7 | 🎨 브랜드 디자인 | [Logo Generation](skills/品牌设计/logo-generation.md) | 미니멀, 기하학, 워드마크, 픽토리얼, 추상 로고 |
| 8 | 🎨 브랜드 디자인 | [Brand Identity](skills/品牌设计/brand-identity.md) | 완전한 비주얼 시스템: 색상, 폰트, 패턴, 응용 |
| 9 | 📱 소셜 미디어 | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest 디자인 |
| 10 | ✏️ 일러스트레이션 | [Character Design](skills/插画创作/character-design.md) | 애니메이션, 만화, 픽셀 아트, 사실적, 치비, 마스코트, VTuber 아바타 |

---

## 🚀 빠른 시작

### Cursor

프로젝트의 `.cursor/rules/` 디렉토리에 스킬 파일을 복사합니다:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

그런 다음 Cursor AI 어시스턴트와의 대화에서 참조하세요.

### Claude Code

프로젝트의 `CLAUDE.md`에 스킬을 추가하거나 `.claude/`에 복사합니다:

```bash
# CLAUDE.md에 추가
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# 또는 직접 참조
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

스킬 파일을 프로젝트에 복사하고 참조합니다:

```bash
# 프로젝트에 복사
cp -r skills/ .kimi/skills/

# 또는 대화에서 직접 사용:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### 모든 AI 어시스턴트

각 스킬 파일은 독립적인 마크다운 문서입니다:

1. **전체 스킬을 컨텍스트로 붙여넣기**
2. **특정 섹션 참조** (프롬프트 템플릿, 스타일 가이드)
3. **복잡한 프로젝트를 위해 여러 스킬 결합**

---

## 📁 프로젝트 구조

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # 포스터 디자인
│   │   ├── retro-movie-poster.md
│   │   ├── travel-poster.md
│   │   └── music-album-cover.md
│   ├── 摄影后期/                    # 사진 후보정
│   │   ├── film-emulation.md
│   │   ├── cinematic-grade.md
│   │   └── light-painting.md
│   ├── 品牌设计/                    # 브랜드 디자인
│   │   ├── logo-generation.md
│   │   └── brand-identity.md
│   ├── 社交媒体/                    # 소셜 미디어
│   │   └── content-creator-pack.md
│   └── 插画创作/                    # 일러스트레이션
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

## 🎨 스킬 심화 분석

각 스킬 파일은 일관된 구조를 따릅니다:

- **언제 사용하는가** — 스킬 적용 시점의 명확한 트리거
- **설계 철학** — 핵심 원칙과 미적 결정
- **의사결정 우선순위** — 정렬된 창작 우선순위 목록
- **AI 어시스턴트 지침** — 단계별 워크플로우
- **프롬프트 템플릿** — 커스터마이징 가능한 변수가 포함된 즉시 사용 가능한 프롬프트
- **스타일 참조** — 컬러 팔레트, 타이포그래피, 구도 가이드
- **일반 패턴** — 자주 사용되는 접근 방식
- **피해야 할 함정** — 일반적인 실수와 회피 방법

### 사용 예시

```
사용자: "이 휴가 사진을 WPA 국립공원 포스터로 변환해줘"

AI (travel-poster 스킬 사용):
→ 랜드마크와 풍경 식별
→ 블록 프린트 질감의 WPA 시대 스타일 선택
→ 지역에 맞는 어스 톤 팔레트 적용
→ 시대에 맞는 타이포그래피 추가
→ 빈티지 여행 포스터 출력
```

---

## 🔗 관련 프로젝트

AI 스킬 생태계의 관련 프로젝트:

| 프로젝트 | 설명 |
|---------|------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | 범용 AI 스킬 모음 |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | 비디오 편집 및 제작용 AI 스킬 |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | 엄선된 AI 규칙 및 설정 |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | AI 스킬 설정 검증 및 테스트 |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | AI 기반 커밋 메시지 생성 |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | AI 도구용 MCP 서버 모음 |

---

## 🤝 기여하기

기여를 환영합니다! 가이드라인은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하세요.

새로운 창작 스킬을 추가하고 싶으신가요? [이슈](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md)를 열거나 PR을 제출해 주세요.

---

## 📄 라이선스

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
