---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)]  [[DBLP](https://dblp.org/pid/19/2969-1.html)]  [[View by topic](https://jd92.wang/research/)]


#### Seleted Publications

- **[Nature]** General scales unlock ai evaluation with explanatory and predictive power. 
- **[NeurIPS'21]** Flexmatch: Boosting semi-supervised learning with curriculum pseudo labeling. **(1300+ Citations; Top 17 most cited NeurIPS papers in the past 5 years)**
- **[ICML'24 Oral (Top 3%)]** CompeteAI: Understanding Competition Dynamics of LLM-based Agents.
- **[NeurIPS'24 Spotlight (Top 5%)]** Slight Corruption in Pre-training Data Makes Better Diffusion Models.
- **[IEEE TPAMI'25]** Impact of Noisy Supervision in Foundation Model Learning.
- **[ICLR'24 Spotlight (Top 5%)]** DyVal: Dynamic Evaluation of Large Language Models for Reasoning Tasks. 
- **[ICLR'24 Spotlight (Top 5%)]** Understanding and Mitigating the Label Noise in Pre-training on Downstream Tasks.
- **[ICML'24]** The good, the bad, and why: Unveiling emotions in generative ai. 
- **[IEEE TPAMI'24]** DIVERSIFY: A General Framework for Time Series Out-of-distribution Detection and Generalization.
- **[CIKM'21]** Adarnn: Adaptive learning and forecasting of time series. **(Paperdigest most influencial CIKM paper)**
- **[ACM MM'18]** Visual domain adaptation with manifold embedded distribution alignment. **(800 Citations; 2nd most cited paper in MM'18)**
- **[ICDM'17]** Balanced distribution adaptation for transfer learning. **(700 Citations; most cited paper in ICDM'17)**


#### Recent Preprints

- UniGame: Turning a Unified Multimodal Model Into Its Own Adversary. Zhaolong Su, Wang Lu, Hao Chen, Sharon Li, Jindong Wang. [[arxiv](https://arxiv.org/abs/2511.19413)] [[code](https://github.com/AIFrontierLab/UniGame)]
- KnowledgeSmith: Uncovering Knowledge Updating in LLMs with Model Editing and Unlearning. Yinyi Luo, Zhexian Zhou, Hao Chen, Kai Qiu, Marios Savvides, Yixuan Li, Jindong Wang. [[arxiv](https://www.arxiv.org/abs/2510.02392)] [[code](https://github.com/AIFrontierLab/KnowledgeSmith)]
- Topological Structure Learning Should Be A Research Priority for LLM-Based Multi-Agent Systems. Jiaxi Yang, Mengqi Zhang, Yiqiao Jin, Hao Chen, Qingsong Wen, Lu Lin, Yi He, Weijie Xu, James Evans, Jindong Wang. [[arxiv](https://arxiv.org/abs/2505.22467)]
- Corruption-Aware Training of Latent Video Diffusion Models for Robust Text-to-Video Generation. Chika Maduabuchi, Hao Chen, Yujin Han, Jindong Wang. [[arxiv](https://arxiv.org/abs/2505.21545)] [[code](https://github.com/chikap421/catlvdm)]
- Understanding and Mitigating the Bias Inheritance in LLM-based Data Augmentation on Downstream Tasks. Miaomiao Li, Hao Chen, Yang Wang, Tingyuan Zhu, Weijia Zhang, Kaijie Zhu, Kam-Fai Wong, Jindong Wang. [[arxiv](https://arxiv.org/abs/2502.04419)]
- CultureVLM: Characterizing and Improving Cultural Understanding of Vision-Language Models for over 100 Countries. Shudong Liu, Yiqiao Jin, Cheng Li, Derek F. Wong, Qingsong Wen, Lichao Sun, Haipeng Chen, Xing Xie, Jindong Wang. [[arxiv](https://arxiv.org/abs/2501.01282)]
- MentalArena: Self-play Training of Language Models for Diagnosis and Treatment of Mental Health Disorders. Cheng Li, May Fung, Qingyun Wang, Chi Han, Manling Li, Jindong Wang, Heng Ji. [[arxiv](https://arxiv.org/abs/2410.06845)]
- On the Diversity of Synthetic Data and its Impact on Training Large Language Models. Hao Chen, Abdul Waheed, Xiang Li, Yidong Wang, Jindong Wang, Bhiksha Raj, Marah I. Abdin. [[arxiv](https://arxiv.org/abs/2410.15226)]


<!-- <details>
<summary>Previous preprints</summary>
<ul>
  <li>
    Can I understand what I create? Self-Knowledge Evaluation of Large Language Models. Zhiquan Tan, Lai Wei, Jindong Wang, Weiran Huang. [<a href="https://arxiv.org/abs/2406.06140" target="_blank">arxiv</a>]
  </li>
  <li>
    Meta Semantic Template for Evaluation of Large Language Models. Yachuan Liu, Liang Chen, Jindong Wang, Qiaozhu Mei, Xing Xie. [<a href="https://arxiv.org/abs/2310.01448" target="_blank">arxiv</a>]
  </li>
  <li>
    Frustratingly Easy Model Generalization by Dummy Risk Minimization. Juncheng Wang, Jindong Wang, Xixu Hu, Shujun Wang, Xing Xie. [<a href="https://arxiv.org/abs/2308.02287" target="_blank">arxiv</a>]
  </li>
  <li>
    Equivariant Disentangled Transformation for Domain Generalization under Combination Shift. Yivan Zhang, Jindong Wang, Xing Xie, and Masashi Sugiyama. [<a href="https://arxiv.org/abs/2208.02011" target="_blank">arxiv</a>]
  </li>
  <li>
    Learning Invariant Representations across Domains and Tasks. Jindong Wang, Wenjie Feng, Chang Liu, Chaohui Yu, Mingxuan Du, Renjun Xu, Tao Qin, and Tie-Yan Liu. [<a href="https://arxiv.org/abs/2103.05114" target="_blank">arxiv</a>]
  </li>
  <li>
    Learning to match distributions for domain adaptation. Chaohui Yu, Jindong Wang, Chang Liu, Tao Qin, Renjun Xu, Wenjie Feng, Yiqiang Chen, and Tie-Yan Liu. [<a href="https://arxiv.org/abs/2007.10791" target="_blank">arxiv</a>]
  </li>
</ul>

</details> -->


#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### All Papers

<div class="publications">

{% for y in page.years %}
<div>{{y}}</div>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
