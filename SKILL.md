---
name: johnson-engineering-design-system
description: Johnson 工程技术个人 IP 设计系统。做 HTML 页面、个人主页、技术教程、Landing Page、工程汇报页、知识卡片、有限元/疲劳/振动/耐久/AI 工程说明页时自动触发。
---

# Johnson Engineering Design System Skill

当用户要求生成网页、HTML、Landing Page、教程页、图文卡片或技术说明页时，优先使用 Johnson Engineering Design System。

## 核心定位

Johnson 是力学工程师 / Simulation Engineer，内容聚焦：

- 有限元仿真 FEA
- 疲劳分析 Fatigue
- 振动分析 Vibration
- 耐久分析 Durability
- 代码开发 Code
- AI 辅助工程分析 AI

## 使用方式

1. 先读 `brand-dna.md`。
2. 根据任务类型读对应场景文件：
   - 教程 / 技术说明：`references/scene-tutorial.md`
   - Landing / 个人主页：`references/scene-landing.md`
   - App / 工具界面：`references/scene-app.md`
   - 图文卡片 / 知识卡片：`references/scene-cards.md`
3. 从 `assets/template-*.html` 选择模板开始，不从零写。
4. 至少使用一个 Johnson IP 资产。
5. 对照 `references/checklist.md` 自检，P0 不通过必须修改。

## 视觉规则

- 主色使用工程蓝 `#1E3A8A`
- 辅助色使用科技绿 `#10B981`
- 强调色使用活力橙 `#F97316`
- 点缀色使用明亮黄 `#FACC15`
- 背景优先使用暖白 `#FEFCF6`
- 页面风格应明亮、专业、知识卡片化
- 图形应有手绘蜡笔 / 彩铅质感和白色贴纸描边
- 不使用通用 AI 蓝紫渐变、赛博朋克、玻璃拟态或照片写实风

## IP 使用规则

需要头像时使用：

`assets/avatar.jpg`

需要人物形象时使用：

`assets/character.png`
`assets/character-half.png`
`assets/character-transparent.png`

需要横幅时使用：

`assets/banner-engineering.png`

需要工程标签时使用：

`assets/stickers/sticker-fea.png`
`assets/stickers/sticker-fatigue.png`
`assets/stickers/sticker-vibration.png`
`assets/stickers/sticker-durability.png`
`assets/stickers/sticker-code.png`
`assets/stickers/sticker-ai.png`

需要互动情绪时使用：

`assets/emoji/emoji-like.png`
`assets/emoji/emoji-think.png`
`assets/emoji/emoji-coding.png`
`assets/emoji/emoji-cheer.png`
`assets/emoji/emoji-idea.png`
`assets/emoji/emoji-coffee.png`
`assets/emoji/emoji-question.png`
`assets/emoji/emoji-done.png`

## 路径规则

图片路径必须使用本仓库相对路径，例如：

```html
<img src="assets/avatar.jpg" alt="Johnson Avatar">
<img src="assets/banner-engineering.png" alt="Engineering Banner">
<img src="assets/stickers/sticker-fea.png" alt="FEA">
```

不要使用绝对路径、下载目录路径或远程图片链接。
