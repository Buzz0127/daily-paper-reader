<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-01
- 运行时间：2026-08-01 19:57:46 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日共读17篇论文，精读6篇、速读11篇，核心聚焦机器人策略学习与多模态动作建模；最值得关注的是两个高分工作：一是提出视觉-触觉-语言-动作统一模型（9.0），二是用物理引导解耦视频-动作策略（9.0）。下一步建议从“触觉+语言”融合建模和“物理先验+视频生成”两个方向深入，先精读这两篇原文，再扩展到速读中的语言引导与运动学感知方法。
- 详情：[/202608/01/README](/202608/01/README)

### 精读区论文标签
1. [$N_0$-VTLA: Scaling Vision-Tactile-Language-Action Model with Latent Tactile Tokens](/202608/01/2607.23782v1-n0-vtla-scaling-vision-tactile-language-action-model-with-latent-tactile-tokens)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：视觉-触觉-语言-动作基础模型，面向接触丰富的操作与离线策略改进
2. [DeVA: Decoupled Video-Action Model with physical guidance for robot policy learning](/202608/01/2607.24159v1-deva-decoupled-video-action-model-with-physical-guidance-for-robot-policy-learning)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：解耦视频-动作模型与物理引导，提升通用化视觉-语言-动作策略学习
3. [τ: Learning Touch-Augmented Vision-Language-Action Models from Future Visual Supervision](/202608/01/2607.24485v1--learning-touch-augmented-vision-language-action-models-from-future-visual-supervision)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：面向机器人操作的触觉增强视觉-语言-动作模型，直接涉及具身VLA性能提升。
4. [S2A2: Audio-Visual Imitation Learning for Manipulation Tasks Using Acoustic Spatial Information](/202608/01/2607.26047v1-s2a2-audio-visual-imitation-learning-for-manipulation-tasks-using-acoustic-spatial-information)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：集成π0等策略的视听操作学习框架
5. [CheckVLA: Execution-Time Verification with Action-Conditioned World Model for Long-Horizon Mobile Manipulation](/202608/01/2607.26789v1-checkvla-execution-time-verification-with-action-conditioned-world-model-for-long-horizon-mobile-manipulation)  
   标签：评分：9.0/10、query:embodied-vla
   evidence：针对VLA策略的执行时验证，使用动作条件世界模型提高长时程机器人操作的可靠性。
6. [FA-RDP: A Frequency-Adaptive Reactive Diffusion Policy for Contact-Rich Manipulation](/202608/01/2607.28596v1-fa-rdp-a-frequency-adaptive-reactive-diffusion-policy-for-contact-rich-manipulation)  
   标签：评分：9.0/10、query:pi-robotics
   evidence：频域自适应扩散策略平衡多模态与响应性，提升接触丰富操作性能

### 速读区论文标签
1. [A Few Words Go a Long Way: Language Guided Robot Policy Synthesis](/202608/01/2607.23784v1-a-few-words-go-a-long-way-language-guided-robot-policy-synthesis)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：通过语言引导的模块化策略合成，弥补VLA黑箱策略的局限
2. [WorldDiT: A Unified Diffusion Architecture for World and Action Modeling](/202608/01/2607.23909v1-worlddit-a-unified-diffusion-architecture-for-world-and-action-modeling)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：将动作生成与视觉世界建模耦合的统一扩散架构，无需大型预训练视觉语言模型动作骨干
3. [KAI: A Kinematic-Aware Interface for Data-Efficient Articulated Object Manipulation](/202608/01/2607.24493v1-kai-a-kinematic-aware-interface-for-data-efficient-articulated-object-manipulation)  
   标签：评分：8.0/10、query:pi-robotics
   evidence：面向数据高效铰接物体操作的运动学感知接口，通过结构化策略先验增强机器人操作。
4. [CoTinyVLA: Chain-of-Thought Distillation for a Sub-Billion-Parameter Vision-Language-Action Model](/202608/01/2607.25487v1-cotinyvla-chain-of-thought-distillation-for-a-sub-billion-parameter-vision-language-action-model)  
   标签：评分：8.0/10、query:embodied-vla
   evidence：通过思维链蒸馏构建小于10亿参数的VLA模型，提升机器人动作生成鲁棒性
5. [The Curse of Precision: A Data Scaling Law for High-Precision Robotic Manipulation](/202608/01/2607.23108v1-the-curse-of-precision-a-data-scaling-law-for-high-precision-robotic-manipulation)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：高精度模仿学习的数据规模定律
6. [$N_0$-TWAM: Scaling Tactile-Native World-Action Model for Contact-Rich Manipulation](/202608/01/2607.23783v1-n0-twam-scaling-tactile-native-world-action-model-for-contact-rich-manipulation)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：大规模触觉原生世界-动作模型用于接触丰富操作
7. [ArmnetBench v0.1: Parallel Real-World Evaluation of Manipulation Policies on a Low-Cost Arm Farm](/202608/01/2607.24481v1-armnetbench-v01-parallel-real-world-evaluation-of-manipulation-policies-on-a-low-cost-arm-farm)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：在低成本机械臂集群上并行评估操作策略的真实世界基准
8. [Decompose and Reorganize: Planning with Primitives and Visuomotor Policies Learned from Demonstrations](/202608/01/2607.25397v1-decompose-and-reorganize-planning-with-primitives-and-visuomotor-policies-learned-from-demonstrations)  
   标签：评分：7.0/10、query:pi-robotics
   evidence：TAMP门控集成视运动策略的长时程操作框架
9. [NEO: NeRF It Once, Edit It Many Times for Continuous Object Manipulation](/202608/01/2607.24538v1-neo-nerf-it-once-edit-it-many-times-for-continuous-object-manipulation)  
   标签：评分：6.0/10、query:embodied-vla
   evidence：语言引导的NeRF编辑框架用于机器人操作，可在执行前编辑未来场景状态
10. [When Does Legacy Data Start to Help? Emergent Transfer in Cross-Configuration Robot Learning](/202608/01/2607.25593v1-when-does-legacy-data-start-to-help-emergent-transfer-in-cross-configuration-robot-learning)  
   标签：评分：6.0/10、query:pi-robotics
   evidence：跨配置机器人学习中旧数据的涌现迁移
11. [Tri-Manual Visuomotor Imitation Learning of Robot Policies](/202608/01/2607.25731v1-tri-manual-visuomotor-imitation-learning-of-robot-policies)  
   标签：评分：6.0/10、query:pi-robotics
   evidence：面向三臂协调操作的模仿学习策略


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
