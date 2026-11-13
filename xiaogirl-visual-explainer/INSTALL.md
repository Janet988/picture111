# 跨平台安装与调用

## DeepSeek Harness

下载仓库后，把 xiaogirl-visual-explainer/ 作为一个 Skill 导入，入口选择 SKILL.md。如果 Harness 支持资产目录，保持 assets/ 与 references/ 的相对路径不变。

## WorkBuddy

在自定义 Skill / 技能管理中导入整个 xiaogirl-visual-explainer/ 文件夹，入口选择 SKILL.md。生成前让它读取 references/recovered-webbook-catalog.md 和 references/style-reference-links.md。

## 豆包

如果支持文件夹导入，直接导入整个文件夹；如果只支持提示词，把 SKILL.md 作为系统提示词，并同时上传 references/ 与 assets/character-reference/。

## 通用调用模板

使用“小女孩手绘视觉 Skill”，把以下内容转成【目标载体】。先输出信息结构与画面分区，再生成；保留白底黑线稿、橙色箭头、蓝色标签、红色警示和固定黑长发蓝眼睛小女孩。精确日期、金额、Logo、二维码和长中文文字放在可编辑文字层，不要让生图模型猜字。画幅：【16:9 / 9:16】。内容：……