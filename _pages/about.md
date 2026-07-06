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


I am currently a Research Fellow at the Nanyang Technological University (NTU), where I collaborate with Prof. [Yap Kim Hui](https://dr.ntu.edu.sg/entities/person/Yap-Kim-Hui). I received my Ph.D. from Beijing University of Chemical Technology, under the supervision of Prof. [Fan Zhang](https://scholar.google.com/citations?hl=zh-CN&user=CujOi1kAAAAJ) and Prof. [Wei Hu](http://www.wei-hu.cn).

Also, I was a visiting student at the Vision and Learning Group (VLG) at SUTD, where I had a wonderful and productive experience working with Prof. [Jun Liu](https://scholar.google.com/citations?user=Q5Ild8UAAAAJ&hl=zh-CN) since March 2023. Following that, I conducted research at Microsoft Research Asia, collaborating with [Yangyu Huang](https://scholar.google.com/citations?user=ycNodL0AAAAJ&hl=zh-CN).

My research interests:
Human Robot Interaction, 3D understanding, [Research AI co-author](https://github.com/microsoft/ResearchStudio) and [AI Music understanding](https://dawnote.app/), data-effenciency learning.


# 🔥 News
- *2026.07*: &nbsp;🎉 [ResearchStudio](https://github.com/microsoft/ResearchStudio) is release.
- *2025.05*: &nbsp;🎉 MMLU_CF accept to ACL 2025 main conference. 
- *2024.07*: &nbsp;🎉 LTRL accept to ECCV 2024, Oral (Oral Paper Rate: 2.1% (188/8585).
- *2024.04*: &nbsp;🏅 LTGC is selected for oral presentation at CVPR 2024 (Oral Paper Rate: 0.78% (90/11532), Acceptance Rate: 23.6% (2719/11532)).


# 📝 Publications （* Equal Contribution）


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"Preprint</div><img src='images/ideaspark_thumb.gif' alt="sym" width="100%"> </div></div>
<div class='paper-box-text' markdown="1">

ResearchStudio-Idea: An Evidence-Grounded Research-Ideation Skill Suite from ML Conference Outcomes

Qihao Zhao, Yangyu Huang, Yalun Dai Lingao Xiao Jianjun Gao, Xin Zhang, Wenshan Wu, Scarlett Li, Yang He, Yan Lu, Yap Kim Hui

[**Project**](https://microsoft.github.io/ResearchStudio/)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/mmlu_cf.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMLU-CF: A Contamination-free Multi-task Language Understanding Benchmark](https://arxiv.org/abs/2412.15194)


*MMLU-CF is a contamination-free and more challenging multiple-choice question benchmark.*

**Qihao Zhao**, Yangyu Huang, Tengchao Lv, Lei Cui, Qinzheng Sun, Shaoguang Mao, Xin Zhang, Ying Xin, Qiufeng Yin, Scarlett Li, Furu Wei

[**Dataset**](https://huggingface.co/datasets/microsoft/MMLU-CF)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/Block.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GaussianBlock: Building Part-Aware Compositional and Editable 3D Scene by Primitives and Gaussians
]([https://arxiv.org/abs/2412.15194](https://arxiv.org/abs/2410.01535))


*GaussianBlock introduces a hybrid representation that leverages the advantages of both primitives, known for their flexible actionability and editability, and 3D Gaussians, which excel in reconstruction quality.*

Shuyi Jiang, **Qihao Zhao**, Hossein Rahmani, De Wen Soh, Jun Liu, Na Zhao

[**Code**](https://github.com/Jiangshuyi0V0/GaussianBlock)
</div>
</div>

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



# 📖 Experiences
- 2025.10 - Now, Nanyang Technological University, Research Fellow
  - Topic, Human Robot Interaction, Research AI co-author
- 2025.01 - 2025.10, Singapore University of Technology and Design, Research Fellow
  - Topic, AI for Building Design
- 2024.06 - 2025.01, MSRA
  - Topic: Contamination-free LLMs Benchmark
- 2023.03 - 2024.03, Singapore University of Technology and Design, Visiting Student.
  - Topic: Long-Tail Recognition with LLMs
- 2019.09 - 2024.06, Beijing University of Chemical Technology, Joint Master’s and Ph.D.
  - Topic: Visual Recognition in the Open World

# 💻 Service
- Co-suprivised Students:
  - [Yalun Dai](https://scholar.google.com/citations?user=6XyNVowAAAAJ&hl=zh-CN) (CVPR x 1, ECCV x 1, From BUCT, Now at NTU)
  - [Chen Jiang](https://scholar.google.com/citations?hl=zh-CN&user=scqMvgEAAAAJ) (ICCV x 1,From BUCT, Now at McGill University)
  
- Reviewer: CVPR, NeurIPS, ICLR, T-CSVT, ICCV, ACM MM
