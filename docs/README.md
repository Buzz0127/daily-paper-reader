<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-16
- 运行时间：2026-08-16 19:04:40 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日聚焦机器人操作前沿：17篇论文中精选6篇精读，重点覆盖多模态大模型与3D感知结合。

最值得关注：语义3D高斯溅射实现开放词汇移动操作（9.0分），以及JEPA-WAM世界动作模型（9.0分），两者均指向机器人从“感知”到“行动”的端到端突破。

若想快速上手，建议从世界动作模型（WAM）方向切入，结合视频扩散先验与文本空间引导，这类方法对零样本泛化提升最直观。
- 详情：[/202608/16/README](/202608/16/README)

### 精读区论文标签
1. [Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](/202608/16/2608.10756v1-embodied-multimodal-grounding-for-open-vocabulary-mobile-manipulation-via-semantic-3d-gaussian-splatting)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：基于扩散的视觉-语言-动作策略提升具身移动操作性能
2. [JEPA-WAM: Stage-Level Joint-Embedding Prediction for World-Action Models in Robot Manipulation](/202608/16/2608.10780v1-jepa-wam-stage-level-joint-embedding-prediction-for-world-action-models-in-robot-manipulation)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：通过阶段级联合嵌入预测世界动作模型提升机器人操作策略性能
3. [Adaptation of Generalist Robot Policies with Minimal Data](/202608/16/2608.11363v1-adaptation-of-generalist-robot-policies-with-minimal-data)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：研究预训练通用机器人策略（如pi0）在极少数据下适应新任务，契合改进pi0策略以提升机器人操作的目标。
4. [G0.5: One Autoregressive Stream for Robot Reasoning and Action](/202608/16/2608.11739v1-g05-one-autoregressive-stream-for-robot-reasoning-and-action)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：提出单一自回归流的预训练VLA模型，统一推理与动作，提升机器人性能
5. [Policy-Induced Hand Priors in Humanoid Dual-Arm Manipulation: Diagnosing and Mitigating Initial-Pose Dependence](/202608/16/2608.11769v1-policy-induced-hand-priors-in-humanoid-dual-arm-manipulation-diagnosing-and-mitigating-initial-pose-dependence)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：诊断并缓解基于VLA的人形双臂操作中的初始位姿依赖
6. [Self-Evolving Embodied Agents via Skill-Harness Evolution](/202608/16/2608.11350v1-self-evolving-embodied-agents-via-skill-harness-evolution)  
   标签：评分：8.0/10、query:agent-build
   evidence：围绕基础模型构建具身智能体，通过进化技能和执行框架提升性能；直接关联AI智能体的构建与组件作用。

### 速读区论文标签
1. [Auditing Instruction-Trajectory Mismatches in Multimodal Robot Demonstrations](/202608/16/2608.07895v1-auditing-instruction-trajectory-mismatches-in-multimodal-robot-demonstrations)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：审计用于训练VLA策略的多模态示范中的指令-轨迹不匹配，可用于提升VLA策略的可靠性与性能。
2. [Vid2WAM: Distilling Video Diffusion Priors into World Action Models](/202608/16/2608.08558v1-vid2wam-distilling-video-diffusion-priors-into-world-action-models)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：用于策略学习的世界动作模型，利用视频扩散先验改进VLA式机器人策略，免除目标任务专家示范。
3. [SG-WAM: Text-Grounded and Spatial-aware Semantic Guidance for World-Action Models](/202608/16/2608.08839v1-sg-wam-text-grounded-and-spatial-aware-semantic-guidance-for-world-action-models)  
   标签：评分：8.0/10、query:pi-robotics
   evidence：用视觉语言模型作语义规划器增强世界动作模型的指令对齐并提高动作准确率
4. [Trajectory Divergence Horizon Decision for Reliable Dual-Arm Surgical Subtask Manipulation](/202608/16/2608.09125v1-trajectory-divergence-horizon-decision-for-reliable-dual-arm-surgical-subtask-manipulation)  
   标签：评分：8.0/10、query:pi-robotics
   evidence：面向机械臂操作的自适应时域VLA策略，减少累积误差
5. [SLIM-0.5B: Learning Action-Grounded Predictive Latents for Robot Manipulation](/202608/16/2608.09771v1-slim-05b-learning-action-grounded-predictive-latents-for-robot-manipulation)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：面向高效机器人操作的紧凑型视觉-语言-动作隐式交互策略
6. [Multi-modal Interactive Control of Robotic Arm based on Offline Large Language Models](/202608/16/2608.08183v1-multi-modal-interactive-control-of-robotic-arm-based-on-offline-large-language-models)  
   标签：评分：7.0/10、query:embodied-vla
   evidence：基于离线大语言模型实现机械臂多模态交互控制，降低具身智能部署成本
7. [BooST: Bridging Semantics and Motions for Efficient Skill Transfer](/202608/16/2608.10600v1-boost-bridging-semantics-and-motions-for-efficient-skill-transfer)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：桥接语义与运动，实现高效技能迁移与策略学习
8. [Foresight Without Seeing: Latent Futures for World Action Models](/202608/16/2608.11605v1-foresight-without-seeing-latent-futures-for-world-action-models)  
   标签：评分：7.0/10、query:embodied-vla
   evidence：带潜空间未来条件的世界动作模型改善机器人动作生成
9. [DreamX-Phi 1.0: Action-Conditioned Video World Model for Robotic Manipulation](/202608/16/2608.13489v1-dreamx-phi-10-action-conditioned-video-world-model-for-robotic-manipulation)  
   标签：评分：7.0/10、query:embodied-vla
   evidence：面向机器人操作的语言条件动作视频世界模型
10. [Surgical WAM: A World-Action Model for Data-Efficient Surgical Robot Learning](/202608/16/2608.11204v1-surgical-wam-a-world-action-model-for-data-efficient-surgical-robot-learning)  
   标签：评分：6.0/10、query:pi-robotics
   evidence：面向数据高效手术操作策略学习的世界-动作模型
11. [Motion-as-Prompt: Enhancing Motion Reasoning in Multimodal Large Language Models via Motion-Guided Cross-Frame Visual Prompting](/202608/16/2608.11655v1-motion-as-prompt-enhancing-motion-reasoning-in-multimodal-large-language-models-via-motion-guided-cross-frame-visual-prompting)  
   标签：评分：6.0/10、query:embodied-vla
   evidence：为多模态大模型注入运动提示，增强机器人操作等场景中的视觉语言推理能力


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
