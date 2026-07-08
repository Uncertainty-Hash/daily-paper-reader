<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-08
- 运行时间：2026-07-08 21:29:47 UTC
- 运行状态：成功
- 本次总论文数：9
- 精读区：3
- 速读区：6

### 今日简报（AI）
1) 今日精读两篇高分文章：自反思强化学习（SRRL）与回合感知同策略蒸馏（TurnOPD），主攻智能体长期任务训练与策略迁移。
2) 最值得看：SRRL 通过跨回合记忆+策略蒸馏实现高效自对齐，TurnOPD 则针对长程任务优化蒸馏效率；速读中 RSPO 的奖励切换方法对多轮LLM训练有启发。
3) 建议关注这些强化学习策略在LLM多轮对话、跨语言推理等场景的落地，尤其是代码切换与贝叶斯实验设计中的自适应信息收集。
- 详情：[/202607/08/README](/202607/08/README)

### 精读区论文标签
1. [Self-Review Reinforcement Learning (SRRL) with Cross-Episode Memory and Policy Distillation](/202607/08/2607.05541v1-self-review-reinforcement-learning-srrl-with-cross-episode-memory-and-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：通过自我审查利用失败实验序列，结合策略蒸馏，提升LLM推理能力
2. [TurnOPD: Making On-Policy Distillation Turn-Aware for Efficient Long-Horizon Agent Training](/202607/08/2607.05804v1-turnopd-making-on-policy-distillation-turn-aware-for-efficient-long-horizon-agent-training)  
   标签：评分：9.0/10、query:opd
   evidence：直接提出TurnOPD实现长任务智能体训练中高效的同策略蒸馏
3. [Repair the Amplifier, Not the Symptom: Stable World-Model Correction for Agent Rollouts](/202607/08/2607.01767v2-repair-the-amplifier-not-the-symptom-stable-world-model-correction-for-agent-rollouts)  
   标签：评分：8.0/10、query:opd
   evidence：从失败规划图中选择紧凑子图进行修正以稳定后续rollout

### 速读区论文标签
1. [Efficient Multilingual Reasoning Transfer via Progressive Code-Switching](/202607/08/2607.00485v1-efficient-multilingual-reasoning-transfer-via-progressive-code-switching)  
   标签：评分：7.0/10、query:opd
   evidence：通过渐进式代码切换实现高效推理迁移，避免蒸馏成本
2. [Amortising Bayesian Experimental Design for Sequential Information Gathering in LLMs](/202607/08/2607.03426v1-amortising-bayesian-experimental-design-for-sequential-information-gathering-in-llms)  
   标签：评分：7.0/10、query:opd
   evidence：使用多轮扩展的GRPO与期望信息增益奖励进行信息收集
3. [RSPO: Reward-Swap Policy Optimization for Multi-Turn LLM Agents](/202607/08/2607.04713v1-rspo-reward-swap-policy-optimization-for-multi-turn-llm-agents)  
   标签：评分：7.0/10、query:opd
   evidence：针对多轮LLM智能体的奖励交换策略优化，涉及过程奖励
4. [STAPO: Selective Trajectory-Aware Policy Optimization for LLM Agent Training](/202607/08/2607.04963v1-stapo-selective-trajectory-aware-policy-optimization-for-llm-agent-training)  
   标签：评分：7.0/10、query:opd
   evidence：利用归一化熵进行步骤级监督，解决轨迹忽视问题
5. [Information Gain-based Rollout Policy Optimization: An Adaptive Tree-Structured Rollout Approach for Multi-Turn LLM Agents](/202607/08/2607.06223v1-information-gain-based-rollout-policy-optimization-an-adaptive-tree-structured-rollout-approach-for-multi-turn-llm-agents)  
   标签：评分：7.0/10、query:opd
   evidence：IGRPO根据中间状态信息量自适应分配回滚预算，提升失败回滚利用效率
6. [Beyond Static Evaluation: Building Simulation Environments for Scalable Agentic Reinforcement Learning](/202607/08/2607.05773v1-beyond-static-evaluation-building-simulation-environments-for-scalable-agentic-reinforcement-learning)  
   标签：评分：6.0/10、query:opd
   evidence：具有可验证奖励的LLM智能体RL模拟环境


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
