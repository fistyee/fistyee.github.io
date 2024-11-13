---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I am a Ph.D. from Beijing University of Chemical Technology, supervised by Prof. [Fan Zhang](https://scholar.google.com/citations?hl=zh-CN&user=CujOi1kAAAAJ) and Prof. [Wei Hu](http://www.wei-hu.cn). I am also a visiting student at VLG, Singapore University of Technology and Design, where I have had a wonderful time and have been working with Prof. [Jun Liu](https://scholar.google.com/citations?user=Q5Ild8UAAAAJ&hl=zh-CN) since March 2023. I am currently a Research Associate at Microsoft Research Asia, collaborating with [Yangyu Huang](https://scholar.google.com/citations?user=ycNodL0AAAAJ&hl=zh-CN). 
My research interests mainly focus on Visual Perception and Learning in the Open World, Large Multi-modal Models, AIGC.



# 🔥 News
- *2024.07*: &nbsp;🎉 One paper accept to ECCV 2024, Oral (Oral Paper Rate: 2.1% (188/8585).
- *2024.04*: &nbsp;🏅 LTGC is selected for oral presentation at CVPR 2024 (Oral Paper Rate: 0.78% (90/11532), Acceptance Rate: 23.6% (2719/11532)).
- *2024.02*: &nbsp;🎉 One paper accept to CVPR 2024.


# 📖 Experiences

- 2023.03 - 2024.03, Singapore University of Technology and Design, Visiting Student.
  - Topic: Long-Tail Learning with LLMs
- 2019.09 - 2024.06, Beijing University of Chemical Technology, Joint Master’s and Ph.D.
  - Topic: Image Recognition in the Open World


# 📝 Publications （* Equal Contribution）

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/ECCV2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LTRL: Boosting Long-tail Recognition via Reflective Learning](https://arxiv.org/abs/2407.12568)

<span style="color:red">Oral, Top 2.1% </span>

*Reflective Learning, a plug-and-play method, boosts long-tail recognition by mimicking human thinking.*

**Qihao Zhao** *, Yalun Dai *, Shen Lin, Wei Hu, Fan Zhang, Jun Liu

[**Code**](https://github.com/fistyee/LTRL)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/WeChat369cfcf657ab0bf26f96218b49ad3669.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LTGC: Long-tail Recognition via Leveraging LLMs-driven Generated Content](https://arxiv.org/pdf/2403.05854.pdf) 

<span style="color:red">Oral, Top 0.78% </span>

*A generative and tuning framework leveraging the knowledge of large language models for long-tail recognition.*

**Qihao Zhao** *, Yalun Dai *, Hao Li, Wei Hu, Fan Zhang, Jun Liu

[**Project**](https://ltgccode.github.io)
- 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/MDCS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MDCS: More Diverse Experts with Consistency Self-distillation for Long-tailed Recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhao_MDCS_More_Diverse_Experts_with_Consistency_Self-distillation_for_Long-tailed_Recognition_ICCV_2023_paper.pdf)

*A long-tail learning method for maximizing expert recognition diversity with minimum model variance.*

**Qihao Zhao**, Chen Jiang, Wei Hu, Fan Zhang, Jun Liu

[**Code**](https://github.com/fistyee/MDCS) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MixPro: Data Augmentation with MaskMix and Progressive Attention Labeling for Vision Transformer ](https://openreview.net/pdf?id=dRjWsd3gwsm)

*A novel data augmentation method designed for ViTs considering global information mixture and label space re-weighting.*

**Qihao Zhao**, Yangyu Huang, Wei Hu, Fan Zhang, Jun Liu

[**Code**](https://github.com/fistyee/MixPro) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-CSVT</div><img src='images/31709890976_.pic.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OHD: An Online Category-aware Framework for Learning with Noisy Labels under Long-Tailed Distribution](https://ieeexplore.ieee.org/abstract/document/10271714)

*A novel framework to address the challenge of noisy labels under long-tailed distribution.*

**Qihao Zhao**, Fan Zhang, Wei Hu, Songhe Feng, Jun Liu


[**Code**](https://github.com/fistyee/P-DIFF) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='images/Pdiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[P-DIFF+: Improving Learning Classifier with Noisy Labels by Noisy Negative Learning Loss](https://www.sciencedirect.com/science/article/abs/pii/S0893608021002872)

*A novel loss function, that mining knowledge from noisy samples to improve the robustness of models.*

**Qihao Zhao**, Wei Hu, Yangyu Huang, Fan Zhang

[**Code**](https://github.com/fistyee/P-DIFF) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>





# 💻 Service
- Co-suprivised Students:
  - [Yalun Dai](https://scholar.google.com/citations?user=6XyNVowAAAAJ&hl=zh-CN) (CVPR x 1, ECCV x 1, From BUCT, Now at NTU)
  - [Chen Jiang](https://scholar.google.com/citations?hl=zh-CN&user=scqMvgEAAAAJ) (ICCV x 1,From BUCT, Now at McGill University)
  
- Reviewer: NeurIPS, ICLR, T-CSVT
