# 赛事女孩生图提示词模板

每张图单独生成。生成时优先把 `assets/character-reference/01-canonical-full-body.jpg` 作为角色参考；研究主题可追加 `02-market-research.jpg`，赛事引导主题可追加 `03-event-guide.jpg`。

```text
Generate one standalone Chinese hand-drawn explanatory illustration. Use the selected document placement and requested aspect ratio (default 16:9; 9:16 for a vertical poster).

Character identity:
The recurring competition girl has long black hair with soft wispy bangs, vivid clear blue eyes, a calm intelligent confident expression, a white high-collar futuristic student uniform, deep navy structural panels, a small cyan circular shoulder badge, and restrained cyan circuit-like accents. Use the supplied canonical character reference for identity. She must be the active subject performing the conceptual action.

Visual DNA (for document mode, leave reserved areas for exact diagrams and text to be composited with deterministic layout):
Pure white background. Minimalist black hand-drawn ink line art. Slightly wobbly pen lines. Cute but restrained editorial character proportions. Sparse flat white, deep navy and cyan color. Generous blank space. The finished composition must contain readable Chinese and/or English text: one clear title and short explanatory blocks. Use black text with orange underlines/arrows and occasional blue or red callouts. Do not use gibberish, fake symbols or pseudo-text. Accurate charts, timelines and process connections will be composited separately when needed. Avoid noisy backgrounds, realistic UI and childish mascot substitutes.

Theme:
{正文配图主题}

Structure type:
{Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的唯一核心意思}

Composition:
{赛事女孩在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3}

Text blocks to render exactly:
{title}
{section 1 label + one-line explanation}
{section 2 label + one-line explanation}
{section 3 label + one-line explanation}
{optional section 4-6}

Text handling:
Extract the most useful wording from the source text and place it visibly in the image. Keep each explanation to one concise line. Preserve user-provided names and fixed phrases exactly. Use ordinary handwritten Chinese or English, not decorative marks. If the source contains too much text, select the most important 3-6 blocks and report the omitted details outside the image.

Constraints:
One image explains only one core structure. Keep at least 20-35% blank white space while reserving enough room for readable text. Keep the girl visually integrated into the core action. Use deep navy and cyan sparingly. Use orange for a main path or underline, red for a warning or result, and blue for a secondary note. Do not include the old 小黑 character. Do not copy prior examples; use the attached visual examples only to match the text-rich hand-drawn explanatory layout, then invent a fresh physical metaphor for this article.
```

## 单人资产提示词

```text
Create one standalone full-body reference of the same competition girl. Preserve long black hair, soft bangs, vivid blue eyes, white high-collar futuristic student uniform, deep navy structural panels, cyan circular shoulder badge and restrained cyan accents. Pure white background, thin slightly wobbly black ink outlines, flat sparse color, minimal shading, generous white space. One person only, head to shoes visible, no text, logo, watermark, scenery or extra people.
```
