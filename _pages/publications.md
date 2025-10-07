---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)] | [[DBLP](https://dblp.org/pid/19/2969-1.html)] | [[View by topic](https://jd92.wang/research/)]

#### Recent Preprints

- KnowledgeSmith: Uncovering Knowledge Updating in LLMs with Model Editing and Unlearning. Yinyi Luo, Zhexian Zhou, Hao Chen, Kai Qiu, Marios Savvides, Yixuan Li, Jindong Wang. [[arxiv](https://www.arxiv.org/abs/2510.02392)] [[code](https://github.com/AIFrontierLab/KnowledgeSmith.git)]
- Topological Structure Learning Should Be A Research Priority for LLM-Based Multi-Agent Systems. Jiaxi Yang, Mengqi Zhang, Yiqiao Jin, Hao Chen, Qingsong Wen, Lu Lin, Yi He, Weijie Xu, James Evans, Jindong Wang. [[arxiv](https://arxiv.org/abs/2505.22467)]
- Corruption-Aware Training of Latent Video Diffusion Models for Robust Text-to-Video Generation. Chika Maduabuchi, Hao Chen, Yujin Han, Jindong Wang. [[arxiv](https://arxiv.org/abs/2505.21545)] [[code](https://github.com/chikap421/catlvdm)]
- Understanding and Mitigating the Bias Inheritance in LLM-based Data Augmentation on Downstream Tasks. Miaomiao Li, Hao Chen, Yang Wang, Tingyuan Zhu, Weijia Zhang, Kaijie Zhu, Kam-Fai Wong, Jindong Wang. [[arxiv](https://arxiv.org/abs/2502.04419)]
- CultureVLM: Characterizing and Improving Cultural Understanding of Vision-Language Models for over 100 Countries. Shudong Liu, Yiqiao Jin, Cheng Li, Derek F. Wong, Qingsong Wen, Lichao Sun, Haipeng Chen, Xing Xie, Jindong Wang. [[arxiv](https://arxiv.org/abs/2501.01282)]
- MentalArena: Self-play Training of Language Models for Diagnosis and Treatment of Mental Health Disorders. Cheng Li, May Fung, Qingyun Wang, Chi Han, Manling Li, Jindong Wang, Heng Ji. [[arxiv](https://arxiv.org/abs/2410.06845)]
- On the Diversity of Synthetic Data and its Impact on Training Large Language Models. Hao Chen, Abdul Waheed, Xiang Li, Yidong Wang, Jindong Wang, Bhiksha Raj, Marah I. Abdin. [[arxiv](https://arxiv.org/abs/2410.15226)]
- Can I understand what I create? Self-Knowledge Evaluation of Large Language Models. Zhiquan Tan, Lai Wei, Jindong Wang, Weiran Huang. [[arxiv](https://arxiv.org/abs/2406.06140)]

<details>
<summary>Previous preprints</summary>
<ul>
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

</details>


#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Papers

<div class="publications">

{% for y in page.years %}
<div>{{y}}</div>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
