# Sustainable Energy Advisor · 可持续精力顾问

> 先读懂你的精力模式，再找到一个真正值得尝试的下一步。

[![License: MIT](https://img.shields.io/badge/License-MIT-2f855a.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Standard-Agent%20Skills-2563eb.svg)](https://agentskills.io)
[![Hosts](https://img.shields.io/badge/Claude%20Code%20%7C%20Codex%20%7C%20Copilot-475569.svg)](#快速开始)

[English](README_en.md) · [快速开始](#快速开始) · [示例](#效果示例) · [适用范围](#适用范围)

---

Sustainable Energy Advisor 是一个面向日常工作与学习状态的 Agent Skill。它帮助你理解疲惫、注意力下降、AI 工具焦虑、动力不足和节律混乱背后的精力模式，并把下一步缩小为一个可以轻松开始、能够观察结果的小实验。

它不会在你说“最近很累”之后立刻列出早睡、运动、饮食和冥想清单。信息不够时，它会先问几个真正影响判断的问题；信息足够时，它会解释为什么会形成现在的状态，再和你一起选择一个最值得先验证的方向。

## 它能帮你做什么

- **看清问题发生在哪里。** 区分身体容量、情绪消耗、注意力碎片化和方向感缺失，而不是把所有问题都归结为自律。
- **理解建议背后的原因。** 先解释与你当前处境有关的机制，再讨论行动。
- **从一个小实验开始。** 不同时改变整套生活，先验证一个范围清楚、能够观察结果的方向。
- **根据反馈继续调整。** 有效就巩固，没用就检查阻力和原判断，不机械重复同一条建议。
- **在需要时给出阶段计划。** 当你明确想恢复长期节律时，把行动串成可以复盘的路线，而不是一张僵硬日程表。

## 适合在这些时候使用

- “我明明有时间，却一直进入不了学习状态。”
- “休息了两天还是不想开始，分不清是累还是在逃避。”
- “下午总是没精神，晚上反而能集中注意力。”
- “AI 让我做得更快，但也让我不断比较工具、担心落后。”
- “我想用一周或一个月慢慢恢复学习和运动节律。”
- “上次建议没有用，想重新看看问题出在哪里。”

自然描述你的情况即可。你不需要先理解精力模型，也不需要填写完整问卷。

## 快速开始

请安装整个仓库目录，以保留 `SKILL.md` 使用的参考文件。

### Claude Code

```bash
git clone https://github.com/hirovel/sustainable-energy-advisor.git \
  ~/.claude/skills/sustainable-energy-advisor
```

### Codex / GitHub Copilot CLI

```bash
mkdir -p ~/.agents/skills
git clone https://github.com/hirovel/sustainable-energy-advisor.git \
  ~/.agents/skills/sustainable-energy-advisor
```

如果宿主没有立即发现新技能，重启一次会话。不同宿主的目录和调用方式可能变化，请以官方文档为准：[Claude Code](https://docs.anthropic.com/en/docs/claude-code/skills) · [Codex](https://developers.openai.com/codex/skills) · [GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills)

## 效果示例

### 用户

> 我最近用 AI 写代码效率变高了，但每天更焦虑，老是刷新模型和工具，担心自己落后。今天还有 4 小时工作，但脑子很乱。

### 助手（节选）

> 你已经感受到一个很具体的矛盾：AI 确实提高了写代码的速度，但“还有没有更好的模型和工具”也成了一个始终开着的入口，不断把注意力从当前工作中拉走。从四个精力维度看，目前最清楚的是情绪和思维层面的变化；身体层面的信息还不够，所以暂时不在睡眠或体能上做判断。
>
> *工具越多，注意力越需要边界。持续更新的价值，最终要落回当前正在完成的事情。*
>
> 今天可以先拿出接下来的一小时，写下一句明确的交付结果，并继续使用已经打开的模型和工具。想刷新或比较新工具时，把它记进“稍后查看”列表，再回到当前代码。结束时看看交付结果推进了多少，以及脑子是否比开始时更容易回到同一个问题上。

示例展示的是判断顺序和回应深度，不是会被重复套用的固定话术。

## 它的方法有什么不同

### 对话先于框架

技能会在内部考虑体能、情绪、思维和意志四个精力维度，但不会每次把它们做成一张分析表。回复只呈现此刻真正能帮助你的部分。

### 恢复不是唯一答案

持续消耗又缺少恢复会让人枯竭，长期没有适量挑战也会让启动越来越困难。它会尝试区分你需要恢复、重新投入，还是先找回方向。

### 一次先验证一个主要方向

小实验可能持续 24–48 小时、3 天或 7 天。周期取决于现有信息和执行摩擦，不会默认给所有人同一份七天计划。

### 反馈比服从计划更重要

行动的目的不只是“坚持”，也是获得新的信息。你回来反馈之后，下一步会根据真实阻力重新判断。

## 适用范围

本技能面向非临床的工作与学习疲劳、注意力下降、AI 工具焦虑、恢复不足、动力和日常节律问题。

它不用于医学诊断、心理治疗、危机支持、严重或持续的睡眠与精神健康症状，也不替代普通日历和待办管理。出现超出范围的信号时，它会停止精力建议，并引导用户寻求适当支持。

想审阅技能本身的设计，可以直接查看 [`SKILL.md`](SKILL.md)、[方法契约](references/methodology-contract.md)和[安全边界](references/safety-boundaries.md)。

## 来源与原创性

项目受精力管理、表现心理学、行为设计、恢复感知工作与可持续知识工作等通用思想启发。所有流程、模板和示例均为原创表达，不复制或替代任何来源材料。

详见 [`NOTICE.md`](NOTICE.md) 与[延伸阅读](references/further-reading.md)。

## License

[MIT](LICENSE) © [hirovel](https://github.com/hirovel)
