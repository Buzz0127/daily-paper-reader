<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-18
- 运行时间：2026-08-18 19:35:22 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：8
- 速读区：11

### 今日简报（AI）
今日处理19篇论文，精读8篇、速读11篇，重点聚焦机器人推理与动作生成模型。

最值得关注的是两篇9.0分精读：《G0.5》提出统一自回归流用于推理与动作，《Reflex》面向反应关键操作实现快速预测性视-语-动模型。

建议普通读者优先了解这两篇高分工作，并留意速读中8.0分的世界-动作模型（如JEPA-WAM、StageWAM）对操控预测的潜在价值。
- 详情：[/202608/18/README](/202608/18/README)

### 精读区论文标签
1. [G0.5: One Autoregressive Stream for Robot Reasoning and Action](/202608/18/2608.11739v1-g05-one-autoregressive-stream-for-robot-reasoning-and-action)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：将推理与行动统一为自回归流的 VLA 模型
2. [Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation](/202608/18/2608.14379v1-reflex-enabling-fast-and-predictive-vision-language-action-models-for-reaction-critical-manipulation)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：面向反应关键型机器人操作的VLA模型与基准
3. [PACE: Phase-Progress-Aware Credit for Long-Horizon Embodied Manipulation](/202608/18/2608.15026v1-pace-phase-progress-aware-credit-for-long-horizon-embodied-manipulation)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：面向长时程操作中VLA模型后训练的信用分配框架
4. [Remember Smarter: Visual History Compressor and Hyperbolic Experience Space for Robotic Memory](/202608/18/2608.15269v1-remember-smarter-visual-history-compressor-and-hyperbolic-experience-space-for-robotic-memory)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：压缩视觉历史与双曲经验空间的VLA记忆模块
5. [Robo-Dopamine 2.0: History-Conditioned and OOD-Aware Process Reward Modeling for Robotic Manipulation](/202608/18/2608.15680v1-robo-dopamine-20-history-conditioned-and-ood-aware-process-reward-modeling-for-robotic-manipulation)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：提出历史条件与OOD感知的过程奖励模型，强化精炼预训练VLA操控策略
6. [GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture](/202608/18/2608.15875v1-gigabrain-07-scaling-embodied-foundation-models-to-emergent-capabilities-with-a-three-system-architecture)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：具身基础模型采用三系统VLA架构，提升跨机器人泛化能力
7. [NebulaVLA: A Dual-Frequency Vision-Language-Action Model With Guide Action for Robotic Manipulation](/202608/18/2608.16503v1-nebulavla-a-dual-frequency-vision-language-action-model-with-guide-action-for-robotic-manipulation)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：双频视觉-语言-动作模型通过引导动作提升机器人操作效率和平滑性
8. [HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-manipulation via Hierarchical Action Flow and Spectral Latent RL](/202608/18/2608.16837v1-haf-adapting-generalist-vlas-to-humanoid-whole-body-loco-manipulation-via-hierarchical-action-flow-and-spectral-latent-rl)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：面向人形全身移动操控的通用VLA适配，提出分层动作流与谱潜在强化学习

### 速读区论文标签
1. [SLIM-0.5B: Learning Action-Grounded Predictive Latents for Robot Manipulation](/202608/18/2608.09771v1-slim-05b-learning-action-grounded-predictive-latents-for-robot-manipulation)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：提出紧凑VLA策略，通过动作锚定潜变量提升机器人操作效率。
2. [JEPA-WAM: Stage-Level Joint-Embedding Prediction for World-Action Models in Robot Manipulation](/202608/18/2608.10780v2-jepa-wam-stage-level-joint-embedding-prediction-for-world-action-models-in-robot-manipulation)  
   标签：评分：8.0/10、query:pi-robotics
   evidence：引入阶段级联合嵌入预测增强世界-动作模型，提升通用机器人操控策略
3. [StageWAM: Joint-Embedding Stage Prediction for World-Action Models in Robot Manipulation](/202608/18/2608.10780v3-stagewam-joint-embedding-stage-prediction-for-world-action-models-in-robot-manipulation)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：面向机器人操作世界-动作模型的阶段预测，提升通用策略性能
4. [Policy-Induced Hand Priors in Humanoid Dual-Arm Manipulation: Diagnosing and Mitigating Initial-Pose Dependence](/202608/18/2608.11769v1-policy-induced-hand-priors-in-humanoid-dual-arm-manipulation-diagnosing-and-mitigating-initial-pose-dependence)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：诊断并缓解 VLA 人形双机械臂操作中的初始位姿依赖
5. [Self-Evolving Embodied Agents via Skill-Harness Evolution](/202608/18/2608.11350v1-self-evolving-embodied-agents-via-skill-harness-evolution)  
   标签：评分：7.0/10、query:agent-build
   evidence：自进化框架通过进化可复用技能与上下文-代码执行器改进非参数化智能体系统
6. [DreamX-Phi 1.0: Action-Conditioned Video World Model for Robotic Manipulation](/202608/18/2608.13489v1-dreamx-phi-10-action-conditioned-video-world-model-for-robotic-manipulation)  
   标签：评分：7.0/10、query:embodied-vla
   evidence：用于机器人操作的动作条件视频世界模型，带几何编码
7. [GAINS: Leveraging Inconsistent Human Intervention Signals in Reinforcement Learning](/202608/18/2608.15707v1-gains-leveraging-inconsistent-human-intervention-signals-in-reinforcement-learning)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：利用不一致人类干预信号的分布强化学习框架，纠正机器人操作策略
8. [Making two action heads agree: coordination mechanisms and a runtime collapse certificate for flow-matching policies](/202608/18/2608.15748v1-making-two-action-heads-agree-coordination-mechanisms-and-a-runtime-collapse-certificate-for-flow-matching-policies)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：面向流匹配策略的协调机制与运行时坍缩证书，提升机器人动作可靠性
9. [RoboSeg: Online Part-Level Semantic Reconstruction for Robotic Manipulation via a Single Eye-in-Hand Camera](/202608/18/2608.09778v1-roboseg-online-part-level-semantic-reconstruction-for-robotic-manipulation-via-a-single-eye-in-hand-camera)  
   标签：评分：6.0/10、query:embodied-vla
   evidence：基于 VLM 的部件级语义重建用于机械臂操作
10. [XPolicyLab: A Unified Standard and Open Ecosystem for Robot Policy Evaluation and Deployment](/202608/18/2608.09892v2-xpolicylab-a-unified-standard-and-open-ecosystem-for-robot-policy-evaluation-and-deployment)  
   标签：评分：6.0/10、query:pi-robotics
   evidence：统一的机器人策略评估与部署生态系统
11. [FlatLab: A Unified Methodology Framework and Simulation-Based Benchmark for Robotic Manipulation of Flat Objects](/202608/18/2608.14049v1-flatlab-a-unified-methodology-framework-and-simulation-based-benchmark-for-robotic-manipulation-of-flat-objects)  
   标签：评分：6.0/10、query:pi-robotics
   evidence：解耦策略生成与动作执行的统一框架，提升机器人对扁平物体的操控性能


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
