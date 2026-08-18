# Cinematic Color Grading

> Category: 摄影后期 (Photo Post-processing) | Style: Hollywood Film Color Grading | Last updated: 2026

## When to Use

Apply Hollywood-quality cinematic color grading to photographs, transforming them with the color language of cinema. Perfect for:

- Portrait sessions wanting a filmic, editorial look
- Wedding photography with cinematic atmosphere
- Travel photography transformed into movie stills
- Fashion and editorial photography
- Social media content with professional film aesthetics
- Cinematic series projects with consistent look

## Design Philosophy

Cinematic color grading is the art of using color to tell a story. Every major film has a deliberate color palette that guides emotion:

- **Color as narrative** — Warm tones for safety, cool tones for isolation, green for the artificial
- **Complementary contrast** — Push shadows and highlights toward opposite colors
- **Selective desaturation** — Remove distracting colors, enhance important ones
- **Tonal separation** — Shadows, midtones, and highlights each carry different color information
- **Filmic response** — Compressed highlights and lifted shadows create the "film look"
- **Consistency** — A grade should work across an entire series, not just one frame

## Decision Priority

1. **Identify the mood** — What emotion should the image evoke?
2. **Select reference film** — Which movie's color language matches?
3. **Apply the grade** — Shift colors in shadows, midtones, highlights
4. **Balance shadows and highlights** — Ensure the grade enhances, not destroys, detail
5. **Final polish** — Vignette, halation, grain, letterbox if needed

## Instructions for AI Assistant

### Step 1: Analyze the Source Image
- Identify the mood and subject
- Note existing lighting and color temperature
- Determine the narrative potential

### Step 2: Select Reference Film
Use the Film Color Palettes section below to find the right cinematic look.

### Step 3: Construct the Grading Prompt
```
Base: "Cinematic color grading inspired by [FILM/SHOW], apply [SHADOW TINT]
in shadows, [HIGHLIGHT TINT] in highlights, [MIDTONE SHIFT], overall contrast
[LEVEL], saturation [DIRECTION], [SPECIAL EFFECTS], [ASPECT RATIO/FORMAT],
filmic quality with [HIGHLIGHT/SHADOW] rolloff"
```

### Step 4: Software Instructions
Provide specific steps for the user's editing software.

## Prompt Templates

### Teal & Orange (Hollywood Standard)

```
Apply Hollywood Teal & Orange cinematic color grading. Push shadows toward
teal-blue (hue ~190°), push highlights toward warm orange-amber (hue ~30°),
maintain natural skin tones in midtones, slightly desaturate blues and greens
while boosting warm tones, add gentle S-curve for contrast, lift blacks
slightly (fade to ~5% not pure black), compress highlights softly, add subtle
vignette, maintain detail in both shadow and highlight regions. The result
should look like a Michael Bay or Transformers-era action film — punchy,
cinematic, with complementary color contrast.
```

**Software Instructions (DaVinci Resolve):**
1. In Color page, add a serial node
2. Lift shadows: push toward blue-green (B slightly up, R slightly down)
3. Gain highlights: push toward orange (R up, B slightly down)
4. Add curve node: gentle S-curve, lift black point slightly
5. Add HSL node: desaturate blues slightly, boost warm tones
6. Optional: add vignette in Power Window

**Software Instructions (Photoshop):**
1. Add Curves adjustment: Blue channel — lift shadows, lower highlights
2. Add Color Balance: Shadows → Cyan +5, Blue +3; Highlights → Red +5, Yellow +3
3. Add Curves: gentle S-curve, lift black output to 10-15
4. Add Hue/Saturation: reduce Blue saturation -15
5. Add Lens Correction vignette or Camera Raw post-crop vignette

### Bleach Bypass

```
Apply Bleach Bypass cinematic color grading — a technique that skips the
bleaching step in film processing, retaining silver in the emulsion. Result:
desaturated colors with extremely high contrast, metallic sheen in highlights,
crushed rich blacks, grain made more prominent, overall harsh but beautiful
industrial quality. Reduce overall saturation by 40-60%, increase contrast
dramatically with steep S-curve, maintain color information but suppress
vibrancy, add visible grain texture, metallic quality to highlights.
Inspired by Saving Private Ryan, Se7en, and Three Kings.
```

**Software Instructions (DaVinci Resolve):**
1. Create parallel node blending color and desaturated layers
2. In layer node: desaturate 40-60% while maintaining color
3. Add steep S-curve for high contrast
4. Crush blacks, but keep slight detail
5. Boost highlight detail/sharpness
6. Add film grain (size: small-medium, intensity: medium-high)

### Day for Night

```
Apply Day for Night cinematic color grading — the classic technique of shooting
daytime footage and grading it to appear as moonlit night. Dramatically reduce
overall exposure (1-2 stops), cool color temperature significantly toward blue
(~7000K → ~12000K), desaturate overall but maintain subtle blue tint, crush
shadows to near-black, preserve specular highlights but cool them blue,
add strong blue tint to sky areas, maintain some warm detail in practical
light sources (windows, lamps), overall mysterious and moody atmosphere.
Inspired by Mad Max: Fury Road night sequences.
```

### Blade Runner 2049 (Roger Deakins)

```
Apply Blade Runner 2049 cinematic color grading inspired by Roger Deakins'
cinematography. Create extreme color contrast through environment — amber/orange
desert tones (highlights and midtones pushed warm), contrasting with cold
blue-gray shadows, heavy atmospheric haze and dust in midtones, muted
desaturation with selective color pops (neon pink, electric blue), extreme
contrast between warm and cool regions, cinematic 2.39:1 aspect ratio feel,
volumetric light effects, overall futuristic dystopian atmosphere with
surprising warmth.
```

**Color zones:**
- Shadows: `#1A237E` Deep Blue-Black
- Midtones: `#FF8F00` Amber (in warm zones) / `#455A64` Blue-Gray (in cool zones)
- Highlights: `#FFE082` Warm Gold
- Accents: `#E91E63` Neon Pink, `#00BCD4` Electric Cyan

### Mad Max: Fury Road

```
Apply Mad Max: Fury Road cinematic color grading. Extreme teal and orange
taken to the maximum — orange/amber dominates the desert scenes with heavily
pushed warm tones, teal-blue reserved for sky and shadow areas, extremely
high contrast and saturation (more than typical Hollywood grade), golden
hour warmth amplified to almost surreal levels, deep rich shadows with blue
push, sand and skin tones burning orange, sky intensely blue, overall feeling
of scorching heat and desolation. Inspired by cinematographer John Seale.
```

### The Matrix (Green Tint)

```
Apply The Matrix digital world color grading. Strong green tint across the
entire image — shadows, midtones, and highlights all shifted toward
matrix-green (#00FF41), slight yellow-green cast in highlights, deep
green-black in shadows, reduced red channel, desaturated except for the
green channel, CRT monitor quality with slight scan line suggestion,
overall artificial and digital feeling, as if viewed through green-tinted
glass. For the blue-pill world (real world): cold steel blue, desaturated,
harsh fluorescent lighting quality.
```

### Amélie (Jean-Pierre Jeunet)

```
Apply Amélie cinematic color grading — the warm, saturated, fairy-tale look
of Paris as imagined by Jean-Pierre Jeunet. Strong green-yellow tint in
shadows (not the typical teal), warm golden-amber highlights, boosted reds
and greens while suppressing blues, overall warm and romantic feeling,
slightly elevated contrast but not harsh, rich saturated colors especially
reds, greens, and golds, nostalgic storybook quality, dreamy but detailed,
as if Paris exists in a perpetual golden autumn afternoon.
```

**Color zones:**
- Shadows: `#4E342E` Warm Brown with green tint
- Midtones: `#FFA726` Warm Amber
- Highlights: `#FFF176` Golden Yellow
- Suppressed: Blues significantly reduced
- Enhanced: Reds, Greens, Golds

### Additional Film References

| Film | Director/DP | Signature Look |
|------|-------------|----------------|
| Moonlight | Barry Jenkins | Deep blue-purple night, warm golden interior |
| The Grand Budapest Hotel | Wes Anderson | Pastel pinks and purples, symmetrical, storybook |
| Sicario | Roger Deakins | Hot desert amber, cold indoor green-gray |
| Her | Spike Jonze | Warm reds and pinks, soft pastel futurism |
| John Wick | — | Neon-soaked, high contrast, amber and teal |
| Parasite | — | Natural warm interior, cool green basement |

## Style Reference

### Color Temperature Guide

| Look | Shadows | Midtones | Highlights |
|------|---------|----------|------------|
| Teal & Orange | Teal #004D40 | Natural | Orange #FF8F00 |
| Bleach Bypass | Neutral Dark | Desaturated | Metallic Gray |
| Day for Night | Deep Blue #0D47A1 | Cool Blue #90CAF9 | Blue-White #E3F2FD |
| Warm Golden | Brown #4E342E | Amber #FFA726 | Gold #FFF176 |
| Cool Noir | Blue-Black #1A237E | Gray #78909C | Blue-White #ECEFF1 |

### DaVinci Resolve Node Structure

```
┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
│ Primary  │──▶│  Color  │──▶│ Contrast│──▶│  Final  │
│ Balance  │   │  Split  │   │  Curve  │   │  Polish │
└─────────┘   └─────────┘   └─────────┘   └─────────┘
  Exposure      Shadow/       S-curve +     Vignette +
  & White       Highlight     Lifted        Grain +
  Balance       Tint          Blacks        Halation
```

## Common Patterns

1. **Complementary push** — Shadows and highlights toward opposite colors (Teal & Orange)
2. **Monochromatic wash** — Single color tint over the entire image (The Matrix)
3. **Selective desaturation** — Keep one color, mute everything else (Sin City effect)
4. **Warm interior / Cool exterior** — Different color temperatures for inside vs. outside scenes
5. **Golden hour amplification** — Push already warm light into hyper-warm territory
6. **Shadow color richness** — Shadows carry color information, not just darkness

## Pitfalls to Avoid

- **Over-grading** — The best grades are subtle; if viewers notice the grade, it's too much
- **Destroying skin tones** — Always protect skin tones; they're the first thing viewers notice
- **Crushing shadows to pure black** — Keep shadow detail; film always retains some
- **Blowing highlights to white** — Soft rolloff, not clipping
- **Inconsistent grading** — A grade should work across multiple images in a series
- **Ignoring white balance** — Grade on top of correct white balance, not as a correction
- **Too much saturation** — Cinema is generally less saturated than consumer photography
- **Wrong reference for the subject** — A horror grade on a wedding doesn't work
- **Missing the letterbox** — Cinematic = 2.39:1 widescreen; add letterbox bars

---

## 中文版本

### 使用场景

适用于为照片添加好莱坞级电影色彩调色效果：

- 人像摄影追求胶片/电影质感
- 婚礼摄影营造电影氛围
- 旅行摄影变身为电影剧照
- 时尚和编辑类摄影
- 社交媒体内容的电影美学
- 需要统一色调的系列拍摄项目

### 核心步骤

1. **分析源图** — 识别情绪、主体、现有光线和色温、叙事潜力
2. **选择参考电影** — 根据目标情绪匹配电影色彩风格（详见 Film Color Palettes 部分）
3. **构建调色 Prompt** — 组合参考电影/剧集、暗部色调、亮部色调、中间调偏移、对比度、饱和度、特殊效果、画幅比
4. **输出软件指令** — 针对 DaVinci Resolve 或 Photoshop 给出具体操作步骤

### 模板说明

| 模板 | 代表影片 | 风格特征 |
|------|---------|---------|
| **Teal & Orange** | 变形金刚系列 | 暗部偏蓝绿（~190°），亮部偏暖橙（~30°），好莱坞标配 |
| **Bleach Bypass** | 拯救大兵瑞恩、七宗罪 | 跳过漂白工艺，去饱和+高对比，金属质感 |
| **Day for Night** | 疯狂的迈克斯夜间段 | 降曝 1-2 档，大幅偏蓝，模拟月光效果 |
| **Blade Runner 2049** | 银翼杀手 2049 | 琥珀沙漠 vs 冷蓝阴影，霓虹粉/电光青点缀 |
| **Mad Max: Fury Road** | 疯狂的迈克斯 | 极致 Teal & Orange，超高对比与饱和度 |
| **The Matrix** | 黑客帝国 | 全画面绿色色调（#00FF41），CRT 显示器质感 |
| **Amélie** | 天使爱美丽 | 暗部偏绿黄+暖棕，亮部金琥珀，压蓝提红绿 |

每个模板附带 DaVinci Resolve 节点结构和 Photoshop 操作步骤。

### 常见陷阱

- **调色过度** — 最好的调色是观众感觉不到的；如果注意到了，说明过头了
- **破坏肤色** — 始终保护肤色，这是观众最先注意到的
- **暗部压到纯黑** — 保留暗部细节，胶片总会有细节
- **亮部过曝** — 要柔和过渡（rolloff），不要硬切（clipping）
- **调色不一致** — 同一项目内所有照片的调色风格应统一
- **忽略白平衡** — 调色应建立在正确白平衡之上，而非替代白平衡
- **饱和度过高** — 电影画面通常比消费级摄影饱和度更低
- **主题与风格错配** — 婚礼照片不适合恐怖片调色
- **忘记遮幅** — 电影感 = 2.39:1 宽银幕；应添加上下黑边（letterbox）
