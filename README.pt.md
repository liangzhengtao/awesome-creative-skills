[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Creative Skills 🎨

> **Transforme fotos em arte. 10 habilidades de IA criativa para designers, fotógrafos e criadores.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/skills-10-orange.svg)](#skills)

---



## ✨ O Que Isto É

10 habilidades de IA que transformam fotos em arte — pôsteres de filmes, capas de álbuns, logotipos, emulação de filme e mais. Cada habilidade fornece ao seu assistente de IA prompts exatos, paletas de cores e instruções passo a passo.

Inspirado por [gathered-scenes-zine](https://github.com/nicholasgriffintn/gathered-scenes-zine) e [scene-distillation-zine](https://github.com/nicholasgriffintn/scene-distillation-zine), mas cobrindo uma gama criativa mais ampla.

## 🖼️ Antes & Depois

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

## 🎯 Habilidades

| # | Categoria | Habilidade | Descrição |
|---|----------|------------|-----------|
| 1 | 🎬 Design de Pôsteres | [Retro Movie Poster](skills/海报设计/retro-movie-poster.md) | Estética de pôsteres dos anos 70-80 com aerógrafo e iluminação dramática |
| 2 | 🎬 Design de Pôsteres | [Vintage Travel Poster](skills/海报设计/travel-poster.md) | Pôsteres de viagem Art Deco e era WPA com formas geométricas ousadas |
| 3 | 🎬 Design de Pôsteres | [Music Album Cover](skills/海报设计/music-album-cover.md) | Arte de capa por gênero: hip-hop, eletrônico, jazz, rock, clássico |
| 4 | 📸 Pós-processamento | [Film Emulation](skills/摄影后期/film-emulation.md) | Kodak Portra, Fuji Velvia, Ilford HP5, Polaroid, Daguerreotype |
| 5 | 📸 Pós-processamento | [Cinematic Grade](skills/摄影后期/cinematic-grade.md) | Teal & Orange, Bleach Bypass, Blade Runner 2049, Amélie |
| 6 | 📸 Pós-processamento | [Light Painting](skills/摄影后期/light-painting.md) | Trilhas de luz, trilhas de estrelas, lã de aço, efeitos de neon |
| 7 | 🎨 Design de Marca | [Logo Generation](skills/品牌设计/logo-generation.md) | Logos minimalistas, geométricos, wordmark, pictóricos, abstratos |
| 8 | 🎨 Design de Marca | [Brand Identity](skills/品牌设计/brand-identity.md) | Sistemas visuais completos: cores, fontes, padrões, aplicações |
| 9 | 📱 Redes Sociais | [Content Creator Pack](skills/社交媒体/content-creator-pack.md) | Designs para Instagram, YouTube, Twitter, LinkedIn, TikTok, Pinterest |
| 10 | ✏️ Ilustração | [Character Design](skills/插画创作/character-design.md) | Anime, cartoon, pixel art, realista, chibi, mascote, avatares VTuber |

---

## 🚀 Início Rápido

### Cursor

Copie qualquer arquivo de habilidade para o diretório `.cursor/rules/` do seu projeto:

```bash
cp skills/海报设计/retro-movie-poster.md .cursor/rules/
```

Então referencie na sua conversa com o assistente de IA do Cursor.

### Claude Code

Adicione uma habilidade ao `CLAUDE.md` do seu projeto ou copie para `.claude/`:

```bash
# Adicionar ao CLAUDE.md
cat skills/摄影后期/film-emulation.md >> CLAUDE.md

# Ou referenciar diretamente
# "Using the film-emulation skill, apply Kodak Portra 400 look to this photo"
```

### Kimi Code

Copie os arquivos de habilidade para o seu projeto e referencie-os:

```bash
# Copiar para o projeto
cp -r skills/ .kimi/skills/

# Ou usar a habilidade diretamente na conversa:
# "Apply the retro-movie-poster skill to transform this photo into a 1980s sci-fi poster"
```

### Qualquer Assistente de IA

Cada arquivo de habilidade é um documento markdown autônomo. Você pode:

1. **Colar a habilidade inteira** como contexto na sua conversa
2. **Referenciar seções específicas** (templates de prompts, guias de estilo)
3. **Combinar múltiplas habilidades** para projetos complexos

---

## 📁 Estrutura do Projeto

```
awesome-creative-skills/
├── skills/
│   ├── 海报设计/                    # Design de Pôsteres
│   │   ├── retro-movie-poster.md
│   │   ├── travel-poster.md
│   │   └── music-album-cover.md
│   ├── 摄影后期/                    # Pós-processamento
│   │   ├── film-emulation.md
│   │   ├── cinematic-grade.md
│   │   └── light-painting.md
│   ├── 品牌设计/                    # Design de Marca
│   │   ├── logo-generation.md
│   │   └── brand-identity.md
│   ├── 社交媒体/                    # Redes Sociais
│   │   └── content-creator-pack.md
│   └── 插画创作/                    # Ilustração
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

## 🎨 Aprofundamento nas Habilidades

Cada arquivo de habilidade segue uma estrutura consistente:

- **Quando Usar** — Gatilhos claros para quando a habilidade se aplica
- **Filosofia de Design** — Princípios fundamentais e decisões estéticas
- **Prioridades de Decisão** — Lista ordenada de prioridades criativas
- **Instruções para o Assistente de IA** — Fluxo de trabalho passo a passo
- **Templates de Prompts** — Prompts prontos com variáveis personalizáveis
- **Referência de Estilo** — Paletas de cores, tipografia, guias de composição
- **Padrões Comuns** — Abordagens frequentemente usadas
- **Armadilhas a Evitar** — Erros comuns e como evitá-los

### Exemplo de Uso

```
Você: "Transforme esta foto de férias em um pôster WPA de parque nacional"

IA (usando habilidade travel-poster):
→ Identifica o monumento e a paisagem
→ Seleciona estilo da era WPA com textura de impressão em bloco
→ Aplica paleta de tons terrosos apropriada para a região
→ Adiciona tipografia correta para o período
→ Produz um pôster de viagem vintage
```

---

## 🔗 Veja Também

Projetos relacionados no ecossistema de habilidades de IA:

| Projeto | Descrição |
|---------|-----------|
| [awesome-skills](https://github.com/nicholasgriffintn/awesome-skills) | Coleção de habilidades de IA de uso geral |
| [awesome-video-skills](https://github.com/nicholasgriffintn/awesome-video-skills) | Habilidades de IA para edição e produção de vídeo |
| [awesome-ai-rules](https://github.com/nicholasgriffintn/awesome-ai-rules) | Regras e configurações de IA curadas |
| [vibe-check](https://github.com/nicholasgriffintn/vibe-check) | Valide e teste suas configurações de habilidades IA |
| [commit-ai](https://github.com/nicholasgriffintn/commit-ai) | Geração de mensagens de commit com IA |
| [awesome-mcp-servers](https://github.com/nicholasgriffintn/awesome-mcp-servers) | Coleção de servidores MCP para ferramentas de IA |

---

## 🤝 Contribuição

Aceitamos contribuições! Consulte [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes.

Quer adicionar uma nova habilidade criativa? Abra uma [issue](https://github.com/liangzhengtao/awesome-creative-skills/issues/new?template=request_skill.md) ou envie um PR.

---

## 📄 Licença

[MIT](LICENSE) © [liangzhengtao](https://github.com/liangzhengtao)

---
