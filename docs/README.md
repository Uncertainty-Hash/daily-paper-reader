<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-30
- 运行时间：2026-06-30 22:03:54 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：7
- 速读区：6

### 今日简报（AI）
1) 今日焦点：强化学习与大模型推理的稳定性与信用分配——13篇论文揭示无评论家RL及多任务Agentic LLM的训练新范式。  
2) 精读双9分推荐：BV-Blend用不确定加权历史基线实现稳定无评论家RL；GRPO策略梯度基础揭示信用分配与秩坍缩问题。速读关注UCOB信用感知双向蒸馏和Hint-Anchored避免推理捷径。  
3) 建议：深入理解RLHF中信用分配机制，尝试在长链推理任务中引入Hint-Anchored方法防幻觉，并关注多任务Agent蒸馏的实用技巧。
- 详情：[/202606/30/README](/202606/30/README)

### 精读区论文标签
1. [BV-Blend: Uncertainty-Weighted Historical Baselines for Stable Critic-Free RL with Verifiable Rewards](/202606/30/2606.28707v1-bv-blend-uncertainty-weighted-historical-baselines-for-stable-critic-free-rl-with-verifiable-rewards)  
   标签：评分：9.0/10、query:opd
   evidence：使用不确定性加权基线稳定GRPO优势估计
2. [On the Policy Gradient Foundations of Group Relative Policy Optimization: Credit Assignment, Gradient Sparsity, and Rank Collapse](/202606/30/2606.29238v1-on-the-policy-gradient-foundations-of-group-relative-policy-optimization-credit-assignment-gradient-sparsity-and-rank-collapse)  
   标签：评分：9.0/10、query:opd
   evidence：GRPO信用分配分析
3. [Process Advantage Signal Shaping: A Paradigm-Agnostic Middleware for Process-Supervised RL in LLM Reasoners](/202606/30/2606.29296v1-process-advantage-signal-shaping-a-paradigm-agnostic-middleware-for-process-supervised-rl-in-llm-reasoners)  
   标签：评分：9.0/10、query:opd
   evidence：直接针对GRPO和过程监督，利用同策略蒸馏KL信号
4. [PHF: Privileged Hidden Flow for On-Policy Self-Distillation](/202606/30/2606.29340v1-phf-privileged-hidden-flow-for-on-policy-self-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：同策略自蒸馏利用特权教师隐藏状态改进推理
5. [CRAFT: Counterfactual Credit Assignment from Free Sibling Rollouts for Self-Distilled Agentic Reinforcement Learning](/202606/30/2606.29476v1-craft-counterfactual-credit-assignment-from-free-sibling-rollouts-for-self-distilled-agentic-reinforcement-learning)  
   标签：评分：9.0/10、query:opd
   evidence：利用GRPO兄弟rollout进行反事实信用分配的自我蒸馏强化学习
6. [LatentRevise: Learning from Zero-Hit Reasoning](/202606/30/2606.29938v1-latentrevise-learning-from-zero-hit-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：从RLVR中零命中失败rollout中恢复训练信号
7. [Experience Augmented Policy Optimization for LLM Reasoning](/202606/30/2606.30420v1-experience-augmented-policy-optimization-for-llm-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：通过自适应重用经验改进大语言模型推理的RLVR

### 速读区论文标签
1. [UCOB: Learning to Utilize and Evolve Agentic Skills via Credit-Aware On-Policy Bidirectional Self-Distillation](/202606/30/2606.29502v1-ucob-learning-to-utilize-and-evolve-agentic-skills-via-credit-aware-on-policy-bidirectional-self-distillation)  
   标签：评分：8.0/10、query:opd
   evidence：信用感知的同策略自蒸馏用于智能体技能
2. [Building Multi-Task Agentic LLMs via Two-Phase Distillation](/202606/30/2606.30044v1-building-multi-task-agentic-llms-via-two-phase-distillation)  
   标签：评分：8.0/10、query:opd
   evidence：比较了多任务大语言模型上的离策略和同策略蒸馏
3. [To Reason or to Fabricate: Reasoning Without Shortcuts via Hint-Anchored Pairwise Aggregation](/202606/30/2606.29481v1-to-reason-or-to-fabricate-reasoning-without-shortcuts-via-hint-anchored-pairwise-aggregation)  
   标签：评分：7.0/10、query:opd
   evidence：HIPPO利用提示注入聚合和成对奖励模型缓解LLM推理RL中的捷径问题
4. [Invariant Reasoning Directions in Latent Trajectories of Language Models](/202606/30/2606.29164v1-invariant-reasoning-directions-in-latent-trajectories-of-language-models)  
   标签：评分：6.0/10、query:opd
   evidence：从强弱推理轨迹的对比精炼中提取不变推理方向
5. [KbSD: Knowledge Boundary aware Self-Distillation for Behavioral Calibration in Agentic Search](/202606/30/2606.29863v1-kbsd-knowledge-boundary-aware-self-distillation-for-behavioral-calibration-in-agentic-search)  
   标签：评分：6.0/10、query:opd
   evidence：面向LLM智能体行为校准的自蒸馏，含token级监督
6. [ARKD: Adaptive Reinforcement Learning-Guided Bidirectional KL Divergence Distillation for Text Generation](/202606/30/2606.29869v1-arkd-adaptive-reinforcement-learning-guided-bidirectional-kl-divergence-distillation-for-text-generation)  
   标签：评分：6.0/10、query:opd
   evidence：强化学习引导的自适应KL散度蒸馏用于大语言模型


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
