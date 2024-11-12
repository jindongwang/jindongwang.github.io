---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)] | [[DBLP](https://dblp.org/pid/19/2969-1.html)] | [[View by topic](https://jd92.wang/research/)]

#### Preprints

- CycleResearcher: Improving Automated Research via Automated Review. Yixuan Weng, Minjun Zhu, Guangsheng Bao, Hongbo Zhang, Jindong Wang, Yue Zhang, Linyi Yang. [[arxiv](https://arxiv.org/abs/2411.00816)]
- Scito2M: A 2 Million, 30-Year Cross-disciplinary Dataset for Temporal Scientometric Analysis. Yiqiao Jin, Yijia Xiao, Yiyang Wang, Jindong Wang. [[arxiv](https://arxiv.org/abs/2410.09510)]
- Meta Semantic Template for Evaluation of Large Language Models. Yachuan Liu, Liang Chen, Jindong Wang, Qiaozhu Mei, Xing Xie. [[arxiv](https://arxiv.org/abs/2310.01448)]
- Frustratingly Easy Model Generalization by Dummy Risk Minimization. Juncheng Wang, Jindong Wang, Xixu Hu, Shujun Wang, Xing Xie. [[arxiv](https://arxiv.org/abs/2308.02287)]
- Equivariant Disentangled Transformation for Domain Generalization under Combination Shift. Yivan Zhang, Jindong Wang, Xing Xie, and Masashi Sugiyama. [[arxiv](https://arxiv.org/abs/2208.02011)]
- Learning Invariant Representations across Domains and Tasks. Jindong Wang, Wenjie Feng, Chang Liu, Chaohui Yu, Mingxuan Du, Renjun Xu, Tao Qin, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2103.05114)]
- Learning to match distributions for domain adaptation. Chaohui Yu, Jindong Wang, Chang Liu, Tao Qin, Renjun Xu, Wenjie Feng, Yiqiang Chen, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2007.10791)]

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
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
