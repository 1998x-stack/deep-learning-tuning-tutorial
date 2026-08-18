# 🔬 深度学习调参技巧与底层原理

> 📘 28章 实战体系 · 交互式 HTML 课程

> **English TL;DR:** An all-Chinese 28-chapter course on **deep-learning hyperparameter tuning from first principles** — the math behind gradient descent, optimizer choice (Adam vs SGD, sharp vs flat minima, two-stage), learning rate (geometric meaning, warmup, cosine), batch size & gradient variance, initialization (Xavier/He), normalization (BN/LN/GN), activation functions, weight decay & AdamW, Dropout as implicit ensembling, LR schedules, loss-function design (CE vs MSE, Focal, label smoothing), augmentation as implicit regularization, validation science, reading training curves, NaN/gradient-explosion root causes, overfit/sanity tests, tuning priority & search methods (grid/random/bayesian), then domain law: CNN, fine-tuning NLP (catastrophic forgetting), recommendation sampling (negative sampling, label imbalance/long-tail), LoRA math, SFT data engineering, RLHF (PPO 4 models, KL, reward hacking), Scaling Laws & μP, and automated tuning frontiers — ending with a from-scratch full-tune capstone.

## 📖 课程简介

本课程把深度学习调参从「炼丹玄学」提升为「有底层数学可依」的科学：逐项剖析梯度下降、优化器（Adam vs SGD）、学习率、批大小、参数初始化、归一化层、激活、正则化/Dropout、损失函数、数据增强与评估验证的数学原理，给出训练曲线解读、NaN/梯度爆炸根因与过拟合小数据调试等实战方法论；再进入 CNN 与 NLP 微调、推荐系统、类别不平衡、LoRA、SFT 数据工程与 RLHF 对齐等分支的调参法则，覆盖 Scaling Law、μP 与自动化精调，最终以「从零调优一个模型」的综合实战收束。

## 🚀 快速开始

```bash
open index.html   # macOS，纯静态即开即看
```

## 📂 项目结构

```text
deep-learning-tuning-tutorial/
├── index.html / 01.html ~ 28.html / courses.json / theme.css
```

## 📖 章节分段

| 阶段 | 章节 | 核心 |
|------|------|------|
| **优化器与核心超参** | 01–06 | 方法论、梯度、优化器、LR、批大小、初始化 |
| **网络与正则** | 07–13 | 归一化、激活、权重衰减、Dropout、调度、损失、增强 |
| **调试与评估** | 14–18 | 验证科学、训练曲线、NaN 根因、过拟合测试、调参优先级 |
| **模态经验法则** | 19–22 | CNN、NLP 微调、推荐特征、不平衡/长尾 |
| **对齐与前沿** | 23–27 | LoRA、SFT 数据、RLHF、Scaling/μP、自动化调参 |
| **实战** | 28 | 从零调优完整流程 |

## ✨ 亮点

- 每章「先讲底层数学，再给调参结论」，贯穿原理到落地
- 覆盖 LoRA / SFT / RLHF / Scaling Law / μP 等大模型最新调参
- 含 NaN 排查、过拟合测试、调参决策树等实操方法

## 🎯 前置知识

- 适合：深度学习调参师 / 模型训练工程师
- 建议具备：PyTorch + 微积分/线性代数基础

## ✨ 特色

- 把玄学炼丹变成可推导的科学方法
- 即开即用纯静态 HTML

---
*本课程由 `deep-learning-tuning-tutorial/` 项目维护。*