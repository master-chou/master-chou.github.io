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

I am **Sashuai Zhou**, currently a Master's student at the **College of Computer Science and Technology, Zhejiang University**, advised by Prof. Zhou Zhao.

My research focuses on **multimodal large models**, particularly on the **alignment between reasoning and generation**. I am interested in improving the **spatial consistency, logical reasoning ability, and controllable generation** of multimodal foundation models under complex instructions.

My recent work explores a full pipeline including:

- Multimodal representation learning  
- Generative foundation model pretraining  
- Executable reasoning and structured planning

---

# 🔥 News

- *2025.02* 🎉 One paper accepted by **EMNLP 2025**.  
- *2025.01* 🎉 One paper accepted by **ICME 2025 (Oral)**.  
- *2024.12* 🎉 One paper accepted by **CVPR 2025**.  
- *2024.11* 📄 One paper submitted to **ACL 2026 ARR** on multimodal reasoning and planning.

---

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpatialCLIP: Learning 3D-aware Image Representations from Spatially Discriminative Language](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_SpatialCLIP_Learning_3D-aware_Image_Representations_from_Spatially_Discriminative_Language_CVPR_2025_paper.pdf)

Zehan Wang*, **Sashuai Zhou***, Shaoxuan He, et al.

- Proposes spatial representation learning for vision-language models
- Improves spatial reasoning ability of multimodal models
- Evaluated on spatial reasoning benchmark **SpatialBench**

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025 (Oral)</div><img src='images/ICME25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Multi-modal Models with Heterogeneous MoE Adapters for Fine-tuning](https://arxiv.org/pdf/2503.20633?)

**Sashuai Zhou**, Yan Xia, Hai Huang

- Introduces a heterogeneous Mixture-of-Experts adapter architecture
- Dynamically combines unimodal and cross-modal experts
- Achieves strong performance with only **5–8% parameter tuning**

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecBase: Generative Foundation Model Pretraining for Zero-Shot Recommendation](https://aclanthology.org/2025.emnlp-main.786.pdf)

**Sashuai Zhou**, Weinan Gan, Qijiong Liu, et al.

- Proposes generative pretraining for recommendation models
- Builds a cross-domain recommendation pretraining dataset
- Demonstrates strong zero-shot recommendation performance with a **1.5B model**

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/CVPR26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpatialReward: Reward Modeling for Spatially Consistent Image Generation](#)

**Sashuai Zhou**, Qiang Zhou, Junpeng Ma, et al.

- Proposes a spatial reward modeling framework for text-to-image generation
- Encourages multimodal models to generate images that satisfy **explicit spatial relations**
- Improves spatial alignment between text instructions and generated images

</div>
</div>
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 ARR</div><img src='images/ACL26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unified Thinker: Decoupling Planning and Generation for Multimodal Reasoning](https://arxiv.org/pdf/2601.03127)

**Sashuai Zhou**, Qiang Zhou, Jijin Hu, et al.

- Separates planning and generation to enable structured reasoning under complex instructions
- Supports executable reasoning and controllable generation
- Demonstrates improved reasoning consistency across multimodal tasks

</div>
</div>

# 🎖 Honors and Awards

- National Scholarship  
- Outstanding Graduate of Zhejiang University  

---

# 📖 Education

- *2024 – Present*, **Zhejiang University**, Master, Computer Science  

- *2020 – 2024*, **Zhejiang University**, Undergraduate, Chu Kochen Honors College(Turing Class), Computer Science

---

# 💻 Research Experience

- *2024 – Present*, Research Assistant, **Zhejiang University**

Research on **multimodal foundation models**, focusing on:

- Multimodal reasoning and generation alignment  
- Reinforcement learning optimization  
- Structured planning for multimodal models

---

# 💬 Contact

Email: chouss911@gmail.com  
GitHub: https://github.com/master-chou
