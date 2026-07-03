# Johnson Engineering Design System

一套给 AI 使用的工程技术个人 IP 设计系统，聚焦有限元仿真、疲劳分析、振动分析、耐久分析、代码开发和 AI 辅助工程分析。

![Johnson Engineering Banner](assets/banner-engineering.png)

![Johnson Avatar](assets/avatar.jpg)

![Johnson Character](assets/character.png)

## 定位

Johnson Engineering Design System 用于生成明亮、专业、有工程可信感的网页、教程页、知识卡片、PPT 插图和技术说明页。

核心职业标签：

- 力学工程师
- 有限元仿真 FEA
- 疲劳分析 Fatigue
- 振动分析 Vibration
- 耐久分析 Durability
- 代码开发 Code
- AI 辅助工程分析 AI

## 适用场景

- 技术教程页
- 工程汇报页
- Landing Page
- 个人主页
- 知识卡片
- 有限元仿真报告
- 疲劳 / 振动 / 耐久分析说明
- AI + 工程工具介绍
- PPT / 文档插图

## 品牌色

| 角色 | 色值 | 用途 |
|---|---|---|
| 主色 工程蓝 | `#1E3A8A` | 标题、按钮、图标、主线条 |
| 辅助 科技绿 | `#10B981` | AI、耐久、通过、正向结果 |
| 强调 活力橙 | `#F97316` | 风险、疲劳、重点提示 |
| 点缀 明亮黄 | `#FACC15` | 背景氛围、贴纸、强调块 |
| 中性 深灰 | `#333333` | 正文、说明文字 |
| 背景 暖白 | `#FEFCF6` | 页面背景 |

## 文件结构

```text
johnson-design-system/
├── SKILL.md
├── brand-dna.md
├── assets/
│   ├── avatar.jpg
│   ├── avatar-circle-*.png
│   ├── avatar-square-*.png
│   ├── character.png
│   ├── character-half.png
│   ├── character-transparent.png
│   ├── banner-engineering.png
│   ├── business-card.png
│   ├── avatar-dark.png
│   ├── emoji/
│   ├── stickers/
│   ├── outline/
│   └── template-*.html
└── references/
    ├── checklist.md
    ├── scene-tutorial.md
    ├── scene-landing.md
    ├── scene-app.md
    └── scene-cards.md
```

## 核心资产

- `assets/avatar.jpg`：主头像，个人主页、作者头像、社交账号
- `assets/character.png`：全身 IP 形象，首页、Landing、封面
- `assets/character-half.png`：半身 IP 形象，教程页、介绍卡片
- `assets/character-transparent.png`：透明背景人物，灵活拼版
- `assets/banner-engineering.png`：首页 Banner、README 顶图、文章封面
- `assets/business-card.png`：名片 / 个人介绍图
- `assets/avatar-dark.png`：深色模式头像

## 工程贴纸

- `assets/stickers/sticker-fea.png`
- `assets/stickers/sticker-fatigue.png`
- `assets/stickers/sticker-vibration.png`
- `assets/stickers/sticker-durability.png`
- `assets/stickers/sticker-code.png`
- `assets/stickers/sticker-ai.png`

## 表情反馈

- `assets/emoji/emoji-like.png`
- `assets/emoji/emoji-think.png`
- `assets/emoji/emoji-coding.png`
- `assets/emoji/emoji-cheer.png`
- `assets/emoji/emoji-idea.png`
- `assets/emoji/emoji-coffee.png`
- `assets/emoji/emoji-question.png`
- `assets/emoji/emoji-done.png`

## 怎么用

1. 让 AI 先读取 `SKILL.md`、`brand-dna.md` 和对应场景文件。
2. 从 `assets/template-tutorial.html`、`assets/template-landing.html`、`assets/template-app.html` 或 `assets/template-cards.html` 开始。
3. 页面至少使用一个 Johnson IP 资产。
4. 对照 `references/checklist.md` 自检后再交付。

## 本地预览

```bash
python3 -m http.server 8765
```

然后打开：

```text
http://localhost:8765/demo-landing.html
http://localhost:8765/components-preview.html
```

## GitHub Pages 部署

1. 推送仓库到 GitHub。
2. 打开仓库 `Settings`。
3. 进入 `Pages`。
4. `Source` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 生成访问地址。
