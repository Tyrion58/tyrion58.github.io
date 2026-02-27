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

My name is Tunyu Zhang (张焞宇), a first-year Ph.D. student in the Department of Computer Science at Rutgers University, advised by Prof.[DIMITRIS N. METAXAS](https://people.cs.rutgers.edu/~dnm/). Previously, I obtained my bachelor degree at the University of Science and Technology of China (USTC) in 2025. 

My research interests include large language models reasoning, diffusion language models, uncertainty estimation, and efficient training of generative models.

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Our paper *TokUR* was accepted to ICLR 2026
- *2025.09*: &nbsp;🎉🎉 Our paper *TokUR* on Bayesian LLM reasoning was accepted to the [NeurIPS 2025 Workshop FoRLM](https://reasoning-workshop.github.io/)!
- *2025.08*: &nbsp;🎉🎉 I will join Professor Dimitris Metaxas's group to pursue my PhD degree at Rutgers.

# 📝 Publications 
where “*” denotes equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/projects/t3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[T3D: Trajectory Self-Distillation via Direct Discriminative Optimization for Efficient Diffusion Language Models](https://arxiv.org/abs/2602.12262)  
**Tunyu Zhang\***, Xinxi Zhang\*, Ligong Han, Haizhou Shi, Xiaoxiao He, Zhuowei Li, Hao Wang, Kai Xu, Akash Srivastava, Hao Wang, Vladimir Pavlovic, Dimitris Metaxas  
<!-- <strong><span class='show_paper_citations' data='XXXX'></span></strong>   -->
[**Paper**](https://arxiv.org/abs/2602.12262) | [**Code**](https://github.com/Tyrion58/T3D) | [**Slides**](__files/t3d_talk.pdf)
- **T3D** is a training framework for **efficient diffusion language models** via *trajectory self-distillation*.  
- T3D uses **Direct Discriminative Optimization (DDO)** to replace mode-covering objectives with a mode-seeking training signal.  
- The framework enables **aggressive few-step generation** while preserving full-step diffusion capabilities and reasoning performance.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/projects/tokur.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TokUR: Token-Level Uncertainty Estimation for Large Language Model Reasoning](https://arxiv.org/abs/2505.11737)  
**Tunyu Zhang\***, Haizhou Shi\*, Yibin Wang, Hengyi Wang, Xiaoxiao He, Zhuowei Li, Haoxian Chen, Ligong Han, Kai Xu, Huan Zhang, Dimitris Metaxas, Hao Wang  
<!-- <strong><span class='show_paper_citations' data='y3st15YAAAAJ:tokur'></span></strong>   -->
[**Paper**](https://arxiv.org/abs/2505.11737)
- We propose **TokUR**, a framework for *token-level uncertainty estimation* tailored for **LLM reasoning**.  
- TokUR introduces a low-rank stochastic perturbation mechanism to approximate predictive distributions efficiently.  
- The framework enables more reliable multi-step reasoning, and provides uncertainty-aware signals for downstream tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/projects/mmneedle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multimodal needle in a haystack: Benchmarking long-context capability of multimodal large language models](https://aclanthology.org/2025.naacl-long.166.pdf)  
Hengyi Wang, Haizhou Shi, Shiwei Tan, Weiyi Qin, Wenyuan Wang, **Tunyu Zhang**, Akshay Nambi, Tanuja Ganu, Hao Wang 

[**Paper**](https://aclanthology.org/2025.naacl-long.166.pdf) | [**Code**](https://github.com/Wang-ML-Lab/multimodal-needle-in-a-haystack)
- MMNeedle provides a systematic evaluation framework for long-context multimodal understanding.
- It enables controlled benchmarking of retrieval and reasoning over large visual contexts, and reveals robustness challenges in current multimodal LLMs.
<!-- <strong><span class='show_paper_citations' data='y3st15YAAAAJ:tokur'></span></strong>   -->
</div>
</div>

## Complex Networks
- [Study of nonequilibrium phase transitions mechanisms in exclusive network and node model of heterogeneous assignment based on real experimental data of KIF3AC and KIF3CC motors](https://link.springer.com/article/10.1140/epjp/s13360-022-03372-5), EPJP 2022
- [Physical mechanisms of exit dynamics in microchannels of nonequilibrium transport systems](https://www.worldscientific.com/doi/full/10.1142/S0217979224501935), IJMP 2024



# 🎖 Honors and Awards
- **2025.06** Outstanding Undergraduate Thesis Award, University of Science and Technology of China
- **2022.12** Second Prize, Asia and Pacific Mathematical Contest in Modeling (APMCM)
- **2022.05** Outstanding Student Scholarship (Gold Award), University of Science and Technology of China



# 📖 Educations
- *2021.09 - 2025.06*, Univeristy of Science and Technology of China, Hefei.


# 💬 Invited Talks
- *2026.02*, Few-Step Diffusion Language Models (Red Hat AI Innovation Team, Random Sample Talk) [**Slides**](files/t3d_talk.pdf). 


# 💻 Internships
- *2024.06 - 2025.08*, Research Assistant at Rutgers University
- *2023.06 - 2024.05*, Research Assistant at University of Hong Kong (HKU)

