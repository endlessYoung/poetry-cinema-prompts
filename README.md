# Poetry Cinema Prompts

**Turn classical Chinese poetry into cinematic AI video concepts, storyboards, and shot-by-shot prompts.**

Poetry Cinema Prompts is a reusable directing workflow for adapting Chinese poetry into moving images. It is not a one-style-fits-all “Chinese aesthetic” filter. Each poem should determine its own visual language, pacing, camera movement, and sound design.

[中文说明](#中文说明) · [Universal prompt](PROMPT.md) · [Storyboard guide](docs/storyboard-guide.md) · [Examples](#examples)

## Quick Start

1. Open [PROMPT.md](PROMPT.md) and copy the reusable director prompt.
2. Add the complete poem, author, known context, target duration, aspect ratio, and intended video tool.
3. Generate the poem analysis, visual concept, and storyboard first. Review them before generating shot-by-shot prompts.
4. Generate shots individually when the video tool has limited duration or weak continuity control.
5. Review literary accuracy, visual continuity, camera movement, sound, and editing before assembling the final video.

## Workflow

**Read the poem → Find its cinematic idea → Design the visual language → Plan the rhythm → Build the storyboard → Write shot prompts → Check continuity → Edit image and sound**

## Design Principles

- **Interpret before illustrating.** A poem is not a checklist of nouns to turn into images.
- **Let the poem choose the style.** Do not force every work into misty mountains, teal-green grading, slow motion, and ornate costumes.
- **Give every shot a purpose.** A shot should reveal information, shape space, shift attention, or change the emotional rhythm.
- **Respect the source text.** Do not import lines, characters, or plot points from another poem.
- **Make prompts actionable.** Describe observable composition, movement, light, texture, and sound rather than relying on vague words such as “beautiful” or “cinematic.”
- **Treat sound as storytelling.** Ambient sound, off-screen sound, music, and silence can carry meaning as strongly as images.
- **Keep creative additions distinguishable from facts.** Do not invent historical context and present it as established fact.

## Repository Structure

- [PROMPT.md](PROMPT.md) — reusable director prompt for poetry-to-cinema adaptations.
- [docs/storyboard-guide.md](docs/storyboard-guide.md) — practical guide to shot size, camera movement, composition, timing, transitions, sound, and continuity.
- [examples/访戴天山道士不遇.md](examples/%E8%AE%BF%E6%88%B4%E5%A4%A9%E5%B1%B1%E9%81%93%E5%A3%AB%E4%B8%8D%E9%81%87.md) — a restrained, realistic mountain-journey adaptation of Li Bai.
- [examples/将进酒.md](examples/%E5%B0%86%E8%BF%9B%E9%85%92.md) — a kinetic, banquet-centered interpretation of Li Bai.
- [examples/春江花月夜.md](examples/%E6%98%A5%E6%B1%9F%E8%8A%B1%E6%9C%88%E5%A4%9C.md) — a lyrical, time-and-space-driven visual poem.
- [examples/登高.md](examples/%E7%99%BB%E9%AB%98.md) — an austere autumn landscape shaped by distance, weather, and physical effort.

## Examples

The examples explore different cinematic approaches instead of repeating one visual template:

| Poem | Cinematic approach | Core visual idea |
|---|---|---|
| Li Bai — *Visiting the Daoist Priest on Daitian Mountain, but Not Finding Him* | Realist landscape film | A journey gradually resolves into absence |
| Li Bai — *Bring in the Wine* (将进酒) | Kinetic dramatic sequence | A banquet's energy clashes with mortality and defiance |
| Zhang Ruoxu — *A Moonlit Night on the Spring River* (春江花月夜) | Lyrical visual poem | Moonlight links river, sky, passing time, and human distance |
| Du Fu — *Ascending the Heights* (登高) | Austere naturalism | Wind, river, falling leaves, and a solitary figure embody hardship |

## Usage Notes

Different video-generation tools vary in prompt length, camera control, clip duration, character consistency, and support for negative prompts. Adapt each shot to the target tool instead of assuming every feature is supported. For accurate Chinese titles, poetry, or calligraphy, add typography during post-production rather than relying on generated text.

This repository currently has no license file. Unless a license is added, do not assume that the material may be freely redistributed or used commercially.

---

## 中文说明

将中国古典诗词转化为具有电影叙事、摄影语言与声音设计的 AI 视频方案。

这不是一套固定的“古风滤镜提示词”，而是一套可复用的导演工作流：先理解诗，再决定如何拍。每首诗都应根据意象、空间、叙事和情绪，形成独立的视觉方案。

### 快速开始

1. 复制 [通用导演 Prompt](PROMPT.md)。
2. 填入诗词原文、作者、已知背景、目标时长、画幅和目标视频工具。
3. 先生成诗意分析、视觉概念和分镜表，确认方向后再生成逐镜提示词。
4. 根据目标视频工具的能力调整镜头时长、运动幅度和提示词长度。
5. 检查诗意准确性、角色连续性、空间关系与声音设计。

### 核心原则

- 先读懂诗，再设计画面，不要逐字机械配图。
- 视觉风格由诗决定，不要让所有作品都变成青绿山水、薄雾和慢镜头。
- 每个镜头都应推进信息、空间或情绪。
- 尊重原诗，不混入其他作品的句子、人物和典故。
- 电影感来自构图、景别、运动、光线、声音和剪辑的共同作用。
- 提示词应当可执行，用具体可见、可听的描述代替空泛形容词。

完整流程为：诗意分析 → 视觉概念 → 整片节奏 → 分镜表 → 逐镜视频提示词 → 连贯性检查 → 后期与声音建议。
