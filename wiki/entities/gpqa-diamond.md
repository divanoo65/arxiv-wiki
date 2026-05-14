---
title: GPQA Diamond
type: entity
tags: [benchmark, evaluation, reasoning, deepseek-r1]
summary: GPQA Diamond 是一个极具挑战性的科学推理基准测试集，用于评估大语言模型在生物、物理和化学等高难度STEM领域的专家级推理能力。
sources: ["raw/notebooklm-analysis/deepseek-r1-paper.md"]
created: 2024-05-22
updated: 2024-05-22
layer: L1
confidence: high
reasoning: 该实体是 DeepSeek-R1 论文中用于衡量模型推理能力的核心基准测试之一，数据来源于提供的分析报告。
---

# GPQA Diamond

GPQA Diamond（Graduate-Level Google-Proof Q&A Benchmark - Diamond subset）是一个专门为评估大语言模型在极高难度科学领域推理能力而设计的基准测试集。该数据集包含数百个由生物学、物理学和化学领域的专家编写的高难度多项选择题。这些问题的设计初衷是确保即使是具备相关领域知识的非专家也难以通过简单的搜索找到答案，从而有效地测试模型的深度推理、逻辑分析以及跨学科知识整合能力。在学术界，GPQA Diamond 被广泛视为衡量大模型是否具备“专家级”科学思维的重要试金石。

### 在本视频/论文中的角色

在 DeepSeek-R1 的研究中，GPQA Diamond 扮演了关键的性能评估指标角色。研究团队通过该基准测试来验证模型在经过强化学习训练后的推理表现。实验结果显示，DeepSeek-R1 在 GPQA Diamond 上取得了 71.5% 的准确率，这一成绩显著证明了模型在处理复杂 STEM 问题时具备强大的逻辑推演能力，能够有效应对需要多步推理和深度验证的科学挑战。该指标不仅展示了模型在基础知识上的储备，更体现了其在面对高难度、非直觉性问题时，通过 [[自我反思]] 和 [[验证]] 机制进行自我纠错和答案优化的能力。

### 相关链接

* [[DeepSeek-R1]]
* [[推理链]]
* [[强化学习]]