<div align="center">

# 📝 ynote-md

**有道云笔记 Markdown 输出规范 · AI Skill**

_让 AI 按有道云官方语法写作，并主动用上你不知道的隐藏能力_

![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-有道云笔记-2B7CE9)
![Format](https://img.shields.io/badge/format-Markdown-black)
![KaTeX](https://img.shields.io/badge/KaTeX-976%20个写法-8A2BE2)
![Mermaid](https://img.shields.io/badge/Mermaid-流程图%20·%20序列图%20·%20甘特图-FF6F61)
![Data Source](https://img.shields.io/badge/数据来源-官方帮助中心%202026--11-green)

</div>

---

## ✨ 这是什么

一个面向 AI 的 **Skill 规范**：让 AI 在生成「将要粘贴进有道云笔记」的 markdown 时——

1. ✅ **按官方语法输出** — 有道云特有写法优先于通用 markdown（`:::` 高亮块、` ```math ` 公式块等）
2. 💡 **主动建议特有能力** — 内容适合画成图、写成公式的，先建议再动笔，而不是等你提
3. 📌 **末尾自动附能力说明** — 每篇输出说明用了哪些能力、如何粘贴渲染，开箱即用

> 🎯 适用场景：写周报 / 学习笔记 / 清单 / 项目计划等一切要贴入有道云的内容。
> ❌ 不适用：普通 markdown 输出、存量笔记格式转换、其他笔记平台（腾讯文档 / Typora / Obsidian 等）。

## 🧩 13 类能力速查

| # | 能力 | 写法 | 典型场景 |
|---|------|------|---------|
| 1 | 标题 / 列表 / 引用 / 粗斜体 | 基础语法 | 一切文档的基础结构 |
| 2 | 表格（含对齐控制） | `\| :-- \| --: \| :-: \|` | 对比、数据罗列 |
| 3 | 待办清单 | `- [ ]` / `- [x]` | 计划、任务、清单 |
| 4 | **高亮块 `:::`** ⭐ | `success / info / warning / danger` | 结论强调、风险提示 |
| 5 | 多行公式 | ` ```math ` | 公式推导、定理呈现 |
| 6 | 行内公式 | `` `$E = mc^2$` `` | 文中变量、符号 |
| 7 | **流程图** ⭐ | `graph TB/BT/LR/RL` | 步骤、决策分支 |
| 8 | **序列图** ⭐ | `sequenceDiagram` | 接口调用、消息时序 |
| 9 | **甘特图** ⭐ | `gantt` | 项目排期、里程碑 |
| 10 | 数学符号全套 | 976 个写法全表 | 希腊字母、积分、求和 |
| 11 | mermaid 进阶 | 子图 / 样式 / 多种连线 | 复杂流程图 |
| 12 | 完整语法示例 | 含渲染效果对照 | 基础语法拿不准时 |
| 13 | **兼容黑名单** ⭐ | 实测维护 | 输出前规避不渲染写法 |

⭐ = 有道云特有 / 实测特有的能力，通用 markdown 里没有。

## 📂 目录结构

```
ynote-md/
├── SKILL.md                     # 触发词 + 核心语法速查 + 13 类能力卡 + 末附说明模板
├── README.md                    # 本文件
└── references/
    ├── syntax-full.md           # 完整语法（含渲染效果对照）
    ├── katex-symbols.md         # KaTeX 符号全表（20 类 · 976 个写法）
    ├── mermaid-flowchart.md     # Mermaid 流程图语法详解
    └── blacklist.md             # 兼容黑名单（实测维护）
```

## 🔗 数据来源（2026-11-19 采集）

- **语法知识**：有道云笔记官方帮助中心 advance_markdown 页全文 + 30 张配图识别
- **KaTeX**：官方 supported 文档解析，976 个写法
- **Mermaid**：官方 flowchart 语法文档集成
- **黑名单**：实测不渲染特性，持续回写维护

## 🔧 维护

- 有道云实测发现新不渲染特性 → 回写 `references/blacklist.md`
- 触发词命中率低 → 调整 `SKILL.md` frontmatter 的 `description`

## 📄 License

[MIT](LICENSE)
