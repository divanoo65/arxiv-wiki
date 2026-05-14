# DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning

**来源**: https://arxiv.org/abs/2501.12948
**作者**: DeepSeek-AI
**发布**: 2025-01-22

## 核心贡献

DeepSeek-R1 证明了 LLM 的推理能力可以通过**纯强化学习**激发，无需人工标注的推理轨迹数据。

## 技术方法

### 强化学习框架
- 使用 GRPO（Group Relative Policy Optimization）
- 奖励信号：答案正确性 + 格式规范性
- 无需人类示范，模型自主涌现推理模式

### 涌现推理模式
- **自我反思（Self-reflection）**: 模型发现错误后自动回溯
- **验证（Verification）**: 对答案进行多角度检验
- **动态策略适应**: 根据问题难度调整思考深度

## 实验结果

| 任务类型 | 表现 |
|----------|------|
| 数学竞赛 | AIME 2024: 79.8% Pass@1 |
| 代码 | Codeforces: 超越 96% 人类参赛者 |
| STEM | GPQA Diamond: 71.5% |

## 蒸馏能力

通过知识蒸馏，小模型（1.5B-70B）也能获得强推理能力，证明推理模式可迁移。

## 局限性

- 语言混合问题（中英文混用）
- 长推理链的冗余计算
- 安全对齐有待加强
