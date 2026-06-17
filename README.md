<div align="center">

## PM PRD 助手

把产品需求写成开发能直接理解和实现的 PRD。  
强调澄清优先、逻辑完整、表达简练，并减少重复和歧义。

<sub>Clarify · Write · Revise · Review</sub>

<br>

<p>
  <img src="https://img.shields.io/badge/Codex-Skill-2563eb?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-v1.0.1-14b8a6?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-中文-f59e0b?style=flat&logo=markdown&logoColor=white" />
  <img src="https://img.shields.io/badge/Series-PM%20Workflow-7c3aed?style=flat" />
</p>

</div>

```text
PM PRD 助手用于澄清、撰写、修订和审查 App / Web PRD。
它会先补齐影响研发落地的信息，再把需求组织成清楚、可执行、少重复的文档。
```

## 🧭 PM 工作流系列

这一组 Skills 用来把产品想法逐步推进到 AI Coding 可执行状态。推荐顺序是：地基 → PRD → Spec → 原型。

| 顺序 | Skill | 作用 |
|---|---|---|
| 1 | [Agentic 地基](https://github.com/FinnCheung93/agentic-foundation) | 项目开工前，初始化原则、状态、日志和协作治理 |
| 2 | [PM PRD 助手](https://github.com/FinnCheung93/pm-prd-copilot) | 澄清、撰写、修订和审查开发可落地的 PRD |
| 3 | [AI Coding 规范文档](https://github.com/FinnCheung93/aicoding-specpilot) | 基于 PRD 生成更适合 AI Coding 读取的规格文档 |
| 4 | [PM 原型助手](https://github.com/FinnCheung93/finn-protopilot) | 基于 PRD / Spec 生成产品走查原型和演示材料 |

<sub>也可以单独调用其中任意一个 Skill，不一定必须按完整链路使用。</sub>

## ✨ 它能帮你做什么

- 把模糊需求整理成开发可执行的 PRD
- 在成文前识别关键缺口和待澄清问题
- 修改已有 PRD，让逻辑更完整、表达更简练
- 审查 PRD 中的歧义、遗漏、重复和边界问题
- 处理新增需求、已有 PRD 更新和独立增量 PRD

## 🧭 适用场景

- 要从零写一份 App / Web PRD
- 要基于现有 PRD 补充一个版本或增量需求
- 要把口头需求、草稿或会议结论整理成文档
- 要检查 PRD 是否足够让开发和测试落地
- 要减少 PRD 里的空泛章节、重复表达和隐含假设

## 🧩 工作方式

这个 Skill 默认不会一上来就写正文，而是先判断信息是否足够。

- 新写 PRD：先做澄清门检查
- 独立增量 PRD：先确认范围、差异和影响面
- 修改已有 PRD：先识别要改的位置和上下文
- 仅评审 PRD：优先输出问题、风险和改进建议
- 信息不足时：每轮只问一个最关键的问题

## 🚦 边界

- 不替代工程架构、接口设计或测试用例矩阵
- 不在关键需求缺口未澄清时直接承诺成文
- 不为了显得完整而堆章节、写套话或重复规则
- 不把同一规则散落到多个章节反复改写

## 📦 使用方式

把本目录作为 Codex skill 安装或放入你的 skills 目录中，由 Codex 在相关 PRD 任务中自动触发。

```text
SKILL.md
```

<sub>未提供开源许可证，默认保留所有权利。</sub>
