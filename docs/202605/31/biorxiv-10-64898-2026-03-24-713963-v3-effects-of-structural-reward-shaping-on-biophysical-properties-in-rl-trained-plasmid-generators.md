---
title: Effects of Structural Reward Shaping on Biophysical Properties in RL-Trained Plasmid Generators
title_zh: 结构奖励塑形对RL训练质粒生成器生物物理性质的影响
authors: "Thiel, M., Cunningham, A., Barnes, C. P."
date: 2026-05-29
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.24.713963v3.full.pdf"
tags: ["query:opd"]
score: 7.0
evidence: 使用GRPO进行质粒生成模型的强化学习训练
tldr: "针对质粒生成基础模型PlasmidGPT，本文对比了监督微调与强化学习后训练的效果。采用基于生物信息的奖励函数（含功能注释、长度约束、重复惩罚），利用组相对策略优化进行RL训练，使质量控制通过率从基线的4.3%提升至71.6%。奖励消融实验揭示核心为基因盒排列奖励。RL生成的序列在3-mer组成和最小自由能密度上趋近真实质粒分布，且对29个保留序列的连续对数似然平均提升0.83纳特。"
source: biorxiv
selection_source: fresh_fetch
motivation: 现有质粒生成模型后训练方法缺乏生物物理性质引导，需探索结构奖励塑造对生成质量的影响。
method: 采用GRPO算法对PlasmidGPT进行RL后训练，奖励函数融合功能注释、长度约束和重复惩罚，并进行五模型奖励消融。
result: "RL模型在8个提示下生成4000序列，质量控制通过率71.6%，显著优于基线（4.3%）和SFT（11.0%）；核心奖励为cassette arrangement bonus。"
conclusion: 结构奖励塑造使RL生成序列在组成与热力学性质上逼近真实质粒，且提升保留序列似然，表明RL可诱导未直接优化的生物物理收敛。
---

## 摘要
我们比较了监督微调（SFT）和强化学习（RL）后训练对PlasmidGPT（一个用于全质粒生成的基础模型）的有效性和分布效应，其中RL模型使用了群体相对策略优化（GRPO）。使用一个基于生物学的奖励函数，该函数编码了功能注释、长度约束和重复惩罚，RL模型在8个提示词上的4,000条序列中达到了71.6%的质量控制通过率，而预训练基线为4.3%，SFT为11.0%。五项奖励消融实验确定了盒式排列奖励（奖励正确的启动子[->]CDS[->]终止子顺序）为关键奖励成分。拒绝采样基线表明，从基础模型中更密集地采样并不能恢复这一增益。除了直接优化的特征外，RL生成的序列在3-mer组成和最小自由能密度上趋近于真实质粒分布，而这两者均未被奖励函数直接优化。尽管SFT和RL是并行的后训练路径，但最小自由能密度在两者下均独立收敛到真实质粒区间。在一个精心挑选的保留集上，RL在所有29条保留序列上的延续对数似然均优于预训练基线（平均Δ = +0.83 nats）。

## Abstract
We compare the efficacy and distributional effects of supervised fine-tuning (SFT) and reinforcement learning (RL) post-training for PlasmidGPT, a foundation model for whole-plasmid generation, using Group Relative Policy Optimization (GRPO) for the RL model. Using a biologically motivated reward function encoding functional annotations, length constraints, and repeat penalties, the RL model achieves a 71.6% quality-control pass rate across 8 prompts on 4,000 sequences, compared to 4.3% for the pretrained baseline and 11.0% for SFT. A five-model reward ablation identifies the cassette arrangement bonus, which rewards correct promoter[-&gt;]CDS[-&gt;]terminator ordering, as the critical reward component. Rejection sampling baselines indicate that the gain is not recovered by sampling more heavily from the base model. Beyond directly optimized features, RL generated sequences converge toward real plasmid distributions in 3-mer composition and minimum free energy density, neither of which is directly optimized by the reward function. Minimum free energy density independently converges to the real-plasmid regime under both SFT and RL despite these being parallel post-training paths. On a small curated hold-out set, RL improves continuation log-likelihood over the pretrained baseline on all 29 held-out sequences (mean {triangleup} = +0.83 nats).