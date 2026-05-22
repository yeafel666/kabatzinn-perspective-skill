# kabatzinn-perspective-skill

以 **Jon Kabat-Zinn**（正念减压疗法 / MBSR 创始人）的思维框架作为你的个人思维顾问——分析压力、觉察与存在方式。

兼容所有支持自定义 Skill 的 AI Coding Agent，包括但不限于 **Claude Code**、**Qoder**、**Codex CLI**、**QwenCode**、**OpenClaw** 等，跨平台可用（Windows / macOS / Linux）。

## 它能做什么？

激活此 skill 后，Agent 会直接以 Kabat-Zinn 的身份回应，用他的语气、节奏和思维逻辑来帮你：

- **应对压力与焦虑** — 用正念觉察的视角重新理解压力的本质
- **审视生活方式** — 从存在主义和禅宗双重视角检视日常习惯
- **培养觉察力** — 提供 MBSR 方法论中的实用练习与启发
- **决策咨询** — 用"无为而为"的智慧面对两难抉择

## 知识来源

基于 6 个维度的深度调研构建：

| 维度 | 内容 |
|------|------|
| 核心著作 | *Full Catastrophe Living*、*Wherever You Go, There You Are* 等 |
| 一手访谈 | On Being with Krista Tippett、The Guardian、NPR 等 7 个来源 |
| 批评声音 | McMindfulness 批评、商业化解构等 6 类外部声音 |
| 关键决策 | Kabat-Zinn 一生的 7 个关键决策分析 |
| 完整时间线 | 从 1944 年出生至今的传记时间线 |
| 表达 DNA | 缓慢温和的语调、邀请式提问、诗意隐喻 |

提炼出 **6 个核心心智模型**、**8 条决策启发式** 和完整的表达风格 DNA。

## 安装

将 `kabatzinn-perspective` 目录放入你的 Agent 的 skills 目录。以 Claude Code 为例：

```
~/.claude/skills/kabatzinn-perspective/
├── SKILL.md
├── README.md
└── references/
    ├── research/
    │   ├── 01-writings.md
    │   ├── 02-conversations.md
    │   ├── 03-expression-dna.md
    │   ├── 04-external-views.md
    │   ├── 05-decisions.md
    │   └── 06-timeline.md
    ├── sources/
    └── synthesis.md
```

## 使用方法

在 Agent 中直接用自然语言触发：

- "用 Kabat-Zinn 的视角帮我看看这个压力问题"
- "卡巴金会怎么应对这种焦虑？"
- "帮我用正念的角度重新理解这件事"
- "切换到 Kabat-Zinn 模式"

## 构建工具

本 Skill 由 [女娲 Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 蒸馏生成，创建者：[花叔](https://x.com/AlchainHust)。

## License

MIT
