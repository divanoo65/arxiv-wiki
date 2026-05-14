---
title: DeepSeek-R1
type: entity
tags: [AI模型, 深度学习, 强化学习, DeepSeek]
summary: DeepSeek-R1 是由 DeepSeek-AI 开发的开源大语言模型，通过纯强化学习方法成功激发了模型的推理能力，无需人工标注数据。
sources: ["raw/notebooklm-analysis/deepseek-r1-paper.md"]
created: 2025-05-20
updated: 2025-05-20
layer: L1
confidence: high
reasoning: 该实体是报告的核心研究对象，技术细节与实验结果均有明确记录，信息完整度高。
---

# DeepSeek-R1

DeepSeek-R1 是由 DeepSeek-AI 团队于 2025 年 1 月发布的一款具有里程碑意义的大语言模型。该模型最核心的突破在于证明了大型语言模型（LLM）的复杂推理能力可以通过纯强化学习（Reinforcement Learning）激发，而无需依赖传统的人工标注推理轨迹数据。在技术实现上，DeepSeek-R1 采用了创新的 GRPO（Group Relative Policy Optimization）算法，通过设置答案正确性和格式规范性作为奖励信号，引导模型自主涌现出包括自我反思、多角度验证以及动态策略适应在内的复杂推理模式。

在性能表现方面，DeepSeek-R1 在多个高难度基准测试中展现了卓越的实力，特别是在数学竞赛（如 AIME 2024）、编程竞赛（如 Codeforces）以及 STEM 领域（如 GPQA Diamond）均达到了顶尖水平。此外，该研究还验证了推理能力的迁移性，通过知识蒸馏技术，使得参数量较小（1.5B-70B）的模型也能继承这种强大的推理模式。尽管目前在语言混合、长推理链冗余及安全对齐方面仍存在一定的局限性，但 DeepSeek-R1 无疑为大模型的训练范式提供了新的思路。

## 在本视频中的角色

DeepSeek-R1 是本报告的核心研究对象。视频/报告详细剖析了该模型如何利用 [[强化学习]] 摆脱对人类标注数据的依赖，重点介绍了其背后的 [[GRPO]] 算法框架，并深入探讨了模型在训练过程中涌现出的 [[自我反思]] 和 [[验证]] 等关键推理行为。报告还通过对比实验数据，评估了其在 [[AIME 2024]] 和 [[Codeforces]] 等任务上的表现，并讨论了通过 [[知识蒸馏]] 将推理能力赋能给小模型的潜力。