<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-20 ~ 2026-05-29
- 运行时间：2026-05-29 06:56:47 UTC
- 运行状态：成功
- 本次总论文数：25
- 精读区：14
- 速读区：11

### 今日简报（AI）
本期日报聚焦LLM推理与后训练优化，精读14篇中两篇9.0分论文分别提出方向自适应自蒸馏和状态分布视角的SFT/RL统一框架。

最值得关注的方向：一是“因材施教”式动态蒸馏提升推理质量，二是从token级转向状态级理解后训练本质，打破传统SFT与RL的边界。

建议优先精读这两篇9.0分论文，并配合速读中关于token信用分配与视觉-语言模型蒸馏的8.0分文章，形成系统认知。
- 详情：[/20260520-20260529/README](/20260520-20260529/README)

### 精读区论文标签
1. [Tailoring Teaching to Aptitude: Direction-Adaptive Self-Distillation for LLM Reasoning](/20260520-20260529/2605.22263v1-tailoring-teaching-to-aptitude-direction-adaptive-self-distillation-for-llm-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：面向大语言模型推理的在线策略自蒸馏方向自适应
2. [Post-Training is About States, Not Tokens: A State Distribution View of SFT, RL, and On-Policy Distillation](/20260520-20260529/2605.22731v1-post-training-is-about-states-not-tokens-a-state-distribution-view-of-sft-rl-and-on-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：针对LLM中SFT、RL和在线策略蒸馏的状态分布视角
3. [EDGE-OPD: Internalizing Privileged Context with Evidence Guided On-Policy Distillation](/20260520-20260529/2605.23493v1-edge-opd-internalizing-privileged-context-with-evidence-guided-on-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：EDGE-OPD：基于证据引导的在线策略蒸馏
4. [Credit Assignment with Resets in Language Model Reasoning](/20260520-20260529/2605.25507v2-credit-assignment-with-resets-in-language-model-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：在LLM推理中使用重置进行失败回滚和信用分配
5. [Not All Disagreement Is Learnable: Token Teachability in On-Policy Distillation](/20260520-20260529/2605.26844v1-not-all-disagreement-is-learnable-token-teachability-in-on-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：在线蒸馏中的token可教性分析
6. [Less is More: Early Stopping Rollout for On-Policy Distillation](/20260520-20260529/2605.27028v1-less-is-more-early-stopping-rollout-for-on-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：针对大语言模型在线策略蒸馏的论文
7. [Counteraction-Aware Multi-Teacher On-Policy Distillation for General Capability Recovery with Domain Preservation](/20260520-20260529/2605.27115v1-counteraction-aware-multi-teacher-on-policy-distillation-for-general-capability-recovery-with-domain-preservation)  
   标签：评分：9.0/10、query:opd
   evidence：多教师在线策略蒸馏用于领域专业化后通用能力恢复
8. [MAIGO: Mitigating Lost-in-Conversation with History-Cleaned On-Policy Self-Distillation](/20260520-20260529/2605.27186v1-maigo-mitigating-lost-in-conversation-with-history-cleaned-on-policy-self-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：面向多轮对话的在线自蒸馏方法
9. [Restoring the Sweet Spot: Pass-Rate Weighted Self-Distillation for LLM Reasoning](/20260520-20260529/2605.27765v1-restoring-the-sweet-spot-pass-rate-weighted-self-distillation-for-llm-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：面向大语言模型推理的在线自蒸馏
10. [ROSD: Reflective On-Policy Self-Distillation for Language Model Reasoning across Domains](/20260520-20260529/2605.28014v1-rosd-reflective-on-policy-self-distillation-for-language-model-reasoning-across-domains)  
   标签：评分：9.0/10、query:opd
   evidence：使用错误轨迹和自反思修正改进推理
11. [ADWIN: Adaptive Windows for Horizon-Aware On-Policy Distillation](/20260520-20260529/2605.28396v1-adwin-adaptive-windows-for-horizon-aware-on-policy-distillation)  
   标签：评分：9.0/10、query:opd
   evidence：面向视界感知在线策略蒸馏的自适应窗口
12. [Skill-Conditioned Gated Self-Distillation for LLM Reasoning](/20260520-20260529/2605.28791v1-skill-conditioned-gated-self-distillation-for-llm-reasoning)  
   标签：评分：9.0/10、query:opd
   evidence：基于技能条件的门控在线自蒸馏
13. [OISD: On-Policy Internal Self-Distillation of Language Models](/20260520-20260529/2605.29089v1-oisd-on-policy-internal-self-distillation-of-language-models)  
   标签：评分：9.0/10、query:opd
   evidence：结合GRPO的在线内部自蒸馏方法提升LLM推理
14. [Draft-OPD: On-Policy Distillation for Speculative Draft Models](/20260520-20260529/2605.29343v1-draft-opd-on-policy-distillation-for-speculative-draft-models)  
   标签：评分：9.0/10、query:opd
   evidence：面向推测草案模型的在线策略蒸馏

### 速读区论文标签
1. [When Are Teacher Tokens Reliable? Position-Weighted On-Policy Self-Distillation for Reasoning](/20260520-20260529/2605.21606v1-when-are-teacher-tokens-reliable-position-weighted-on-policy-self-distillation-for-reasoning)  
   标签：评分：8.0/10、query:opd
   evidence：面向推理的位置加权在线自蒸馏
2. [OPPO: Bayesian Value Recursion for Token-Level Credit Assignment in LLM Reasoning](/20260520-20260529/2605.21851v1-oppo-bayesian-value-recursion-for-token-level-credit-assignment-in-llm-reasoning)  
   标签：评分：8.0/10、query:opd
   evidence：源自在线蒸馏的无评论家token级信用分配
3. [Visual-Advantage On-Policy Distillation for Vision-Language Models](/20260520-20260529/2605.21924v1-visual-advantage-on-policy-distillation-for-vision-language-models)  
   标签：评分：8.0/10、query:opd
   evidence：视觉语言模型的在线策略蒸馏
4. [CLORE: Content-Level Optimization for Reasoning Efficiency](/20260520-20260529/2605.22211v1-clore-content-level-optimization-for-reasoning-efficiency)  
   标签：评分：8.0/10、query:opd
   evidence：使用在线策略轨迹编辑进行内容级优化，直接与OPD相关
5. [Guarded Repair for Harm-Aware Post-hoc Replacement of LLM Mathematical Reasoning](/20260520-20260529/2605.24613v1-guarded-repair-for-harm-aware-post-hoc-replacement-of-llm-mathematical-reasoning)  
   标签：评分：8.0/10、query:opd
   evidence：选择性地修复推理轨迹，使用验证守卫，与错误轨迹过程监督一致
6. [One-Way Policy Optimization for Self-Evolving LLMs](/20260520-20260529/2605.22156v1-one-way-policy-optimization-for-self-evolving-llms)  
   标签：评分：7.0/10、query:opd
   evidence：面向LLM推理的RLVR方法，采用单向策略优化
7. [Self-Policy Distillation via Capability-Selective Subspace Projection](/20260520-20260529/2605.22675v1-self-policy-distillation-via-capability-selective-subspace-projection)  
   标签：评分：7.0/10、query:opd
   evidence：通过能力选择性子空间投影实现自策略蒸馏
8. [SEAL: Synergistic Co-Evolution of Agents and Learning Environments](/20260520-20260529/2605.24426v1-seal-synergistic-co-evolution-of-agents-and-learning-environments)  
   标签：评分：7.0/10、query:opd
   evidence：将失败轨迹诊断转换为回合级失败标签，用于智能体学习的过程监督
9. [CausalFlow: Causal Attribution and Counterfactual Repair for LLM Agent Failures](/20260520-20260529/2605.25338v1-causalflow-causal-attribution-and-counterfactual-repair-for-llm-agent-failures)  
   标签：评分：7.0/10、query:opd
   evidence：利用失败轨迹进行因果归因与反事实修复
10. [Not only where, But when: Temporal Scheduling for RLVR](/20260520-20260529/2605.25381v1-not-only-where-but-when-temporal-scheduling-for-rlvr)  
   标签：评分：6.0/10、query:opd
   evidence：LLM后训练中RLVR的时间调度方法
11. [From Fact Overwriting to Knowledge Evolution: Causal Editing via On-Policy Self-Distillation](/20260520-20260529/2605.28303v1-from-fact-overwriting-to-knowledge-evolution-causal-editing-via-on-policy-self-distillation)  
   标签：评分：6.0/10、query:opd
   evidence：使用在线策略自蒸馏进行知识编辑


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
