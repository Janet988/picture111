# 小女孩手绘视觉 Skill

这是“广发证券 × 高顿模拟投资大赛”小女孩 IP 的跨平台手绘视觉 Skill，适用于 PPT、9:16 海报、网页插图、推文配图、赛事介绍、视频分镜和轻动效。

## Skill 入口

- `xiaogirl-visual-explainer/SKILL.md`
- 参考资料位于 `xiaogirl-visual-explainer/references/`
- 角色与风格参考图说明位于 `xiaogirl-visual-explainer/references/recovered-webbook-catalog.md`

## 安装方式

把 `xiaogirl-visual-explainer` 整个文件夹作为一个 Skill 安装，并让工具读取其中的 `SKILL.md`。

- DeepSeek Harness：在 Skills/工具目录中导入该文件夹。
- WorkBuddy：在自定义 Skill 中导入该文件夹，入口选择 `SKILL.md`。
- 豆包：在技能/提示词知识库中导入 `SKILL.md`，同时上传 `references/` 文件夹。

## 调用示例

> 使用小女孩手绘视觉 Skill，把下面内容做成 9:16 今日战报海报。保留白底黑线稿、橙色箭头、蓝色标签和固定小女孩 IP；先给图文结构，再生成图片。

> 使用小女孩手绘视觉 Skill，把这段投资规则做成 16:9 PPT 解析图，并给出可编辑文字层和网页 alt 文案。

> 使用小女孩手绘视觉 Skill，把这篇赛事内容拆成 6 镜头短视频分镜，保留手绘线稿风格，不要霓虹赛博背景。

## 1.1 文档自动配图

上传文档 → 识别适合时间轴、流程、概念拆解等可视化的位置 → 给出候选和推荐张数 → 用户选择张数 → 自动生成小女孩手绘配图 → 插入对应段落后的文档副本 → 打开检查并交付。

已有清晰图表默认保留。候选包含具体位置、图形类型和女孩动作；已给数量则直接执行，无需重复询问。支持Word、PPT、HTML、Markdown与PDF的对应处理策略；PDF仅有成品时在相关页后增加解释页。

调用：
> 使用小女孩PPT Skills给这份文档自动配图，先推荐位置并问我需要几张，我回答后生成并插回。

已导入旧版的宿主请更新整个Skill目录。Skill是工作规范，生图与文档编辑依赖宿主工具；没有相应能力时会明确说明未完成的步骤。各平台的导入入口随版本而异，本文不代表已在第三方平台实机安装或验证。
