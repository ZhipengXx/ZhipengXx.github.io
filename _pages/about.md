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

I am currently a third-year master’s student at Xidian University, the State Key Laboratory of Integrated Services Networks (ISN), advised by Prof. De Cheng and Prof. Nannan Wang. Prior to this, I received my bachelor’s degree from Xidian University in 2023. I will join The Hong Kong University of Science and Technology (HKUST) in Fall 2026. I was also a research intern at Microsoft Research Asia (MSRA). My research interests include **Domain Generalization**, **fine-tuning and parameter-efficient adaptation of foundation models** including LLMs and multimodal models, and **AI agents**. 

Please feel free to contact me via [djddskkekk@gmail.com](mailto:xu_zhipeng@stu.xidian.edu.cn). You can also find my profile on <a href='https://scholar.google.com/citations?user=IMz0WDcAAAAJ&hl=en'>Google Scholar</a> <a href='https://scholar.google.com/citations?user=IMz0WDcAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

<style>
.compact-news ul {
  margin-top: 0.4em;
}

.compact-news li {
  margin-bottom: 0.35em !important;
  line-height: 1.5;
}

.compact-news li p {
  margin: 0 !important;
}
</style>

# 🔥 News
<!-- - *2025.06*: &nbsp;🎉 I started a research internship at **Microsoft Research Asia (MSRA)**.
- *2025*: &nbsp;🎉 Our paper **Adversarial Domain Prompt Tuning and Generation for Single Domain Generalization** was accepted by **CVPR 2025**.
- *2025*: &nbsp;🎉 Our work **Prompt Disentanglement via Language Guidance and Representation Alignment for Domain Generalization** received a major revision from **TPAMI**.
- *2024*: &nbsp;🎉 Our paper **Disentangled Prompt Representation for Domain Generalization** was accepted by **CVPR 2024**.
- *2024-2025*: &nbsp;🎖 I received the **Academic Year National Scholarship**.
- *2023.09*: &nbsp;I began my MEng study in Information and Communication Engineering at **XIDIAN University**. -->

<div class="compact-news" markdown="1">

- **[2026.05]** One paper about Continue Learning is accepted by ICML'26!

- **[2026.01]** Two papers about Continue Learning are accepted by ICLR'26!

- **[2026.01]** One paper about Domain Generalization is accepted by ICLR'26!

- **[2026.01]** One paper about Domain Generalization is accepted by TPAMI'26!

- **[2025.12]** I received the official offer from HKUST for Fall 2026!

- **[2025.02]** One paper about Domain Generalization is accepted by CVPR'25!

- **[2024.02]** One paper about Domain Generalization is accepted by CVPR'24!

</div>


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/CVPR25.png' alt="PAPT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adversarial Domain Prompt Tuning and Generation for Single Domain Generalization](https://openaccess.thecvf.com/content/CVPR2025/html/Xu_Adversarial_Domain_Prompt_Tuning_and_Generation_for_Single_Domain_Generalization_CVPR_2025_paper.html)

**Zhipeng Xu**, De Cheng, Xinyang Jiang, Nannan Wang, Dongsheng Li, Xinbo Gao

[**Paper**](https://openaccess.thecvf.com/content/CVPR2025/html/Xu_Adversarial_Domain_Prompt_Tuning_and_Generation_for_Single_Domain_Generalization_CVPR_2025_paper.html)

* We propose **PAPT** for single domain generalization, which uses pre-trained text-to-image foundation models to synthesize diverse training domains from a single source domain. Instead of relying on hand-crafted textual styles, PAPT learns abstract **category prompts** and **domain prompts** to preserve class semantics while generating diverse domain shifts, and further designs a progressive adversarial training strategy to continuously expand the domain prompt pool.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR24.png' alt="DPR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Disentangled Prompt Representation for Domain Generalization](https://openaccess.thecvf.com/content/CVPR2024/html/Cheng_Disentangled_Prompt_Representation_for_Domain_Generalization_CVPR_2024_paper.html)

De Cheng, **Zhipeng Xu**, Xinyang Jiang, Nannan Wang, Dongsheng Li, Xinbo Gao

[**Paper**](https://openaccess.thecvf.com/content/CVPR2024/html/Cheng_Disentangled_Prompt_Representation_for_Domain_Generalization_CVPR_2024_paper.html)

* We propose **DPR** for domain generalization, which leverages the easier disentanglement of language prompts to guide visual representation learning. Specifically, DPR uses LLM-generated domain-invariant and domain-specific descriptions to learn disentangled prompts, and designs **Domain-Specific Prototype Learning (DSPL)** to combine invariant prediction with relevant domain-specific knowledge for robust unseen-domain recognition.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2026</div><img src='images/TPAMI261.png' alt="PADG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prompt Disentanglement via Language Guidance and Representation Alignment for Domain Generalization](https://arxiv.org/pdf/2507.02288)

De Cheng, **Zhipeng Xu**, Xinyang Jiang, Dongsheng Li, Nannan Wang, Xinbo Gao

[**Paper**](https://arxiv.org/pdf/2507.02288)

* We propose **PADG** for domain generalization, which combines LLM-guided prompt disentanglement with worst-case representation alignment. PADG uses **CMD** to learn domain-invariant and domain-specific visual features from disentangled textual guidance, designs **WERA** to simulate worst-case domain shifts and enforce representation alignment, and further adopts **DSPL** to integrate domain-invariant and domain-specific knowledge during inference.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ICLR2026.png' alt="RD-MLDG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning-Driven Multimodal LLMs for Domain Generalization](https://arxiv.org/pdf/2602.23777)

**Zhipeng Xu**, Zilong Wang, Xinyang Jiang, Dongsheng Li, De Cheng, Nannan Wang

[**Paper**](https://arxiv.org/pdf/2602.23777) [**code**](https://github.com/ZhipengXx/DomainBed-Reasoning/tree/main)

* We propose **RD-MLDG**, a reasoning-driven multimodal LLM framework for domain generalization, which leverages class-relevant reasoning chains as domain-invariant supervision beyond visual features. We construct **DomainBed-Reasoning** to study reasoning under domain shift, and design **MTCT** to align reasoning supervision with direct classification and **SARR** to reduce reasoning-pattern mismatch through self-aligned reasoning refinement, enabling robust and interpretable out-of-domain generalization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ICLR262.png' alt="IIKC" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Interference-Isolated Elastic Weight Consolidation and Knowledge Calibration for Incremental Object Detection](https://openreview.net/pdf?id=VrXdmCjni4)

De Cheng, Mingyue Zeng, **Zhipeng Xu**, Di Xu, Nannan Wang, Xinbo Gao

[**Paper**](https://openreview.net/pdf?id=VrXdmCjni4)

* We propose **IIKC** for incremental object detection, which tackles catastrophic forgetting by explicitly modeling task interference between old and new classes. The core **IKI-EWC** module isolates conflicting knowledge caused by unlabeled objects being learned as background, and selectively regularizes model parameters to preserve useful old knowledge while suppressing interference. In addition, **PKC** calibrates old-class prototypes through a learnable projection layer and combines them with current-task features to reduce semantic drift in the classification head.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/ICLR261.png' alt="StPR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[StPR: Spatiotemporal Preservation and Routing for Exemplar-Free Video Class-Incremental Learning](https://arxiv.org/pdf/2505.13997)

Huaijie Wang, De Cheng, Guozhang Li, **Zhipeng Xu**, Lingfeng He, Jie Li, Nannan Wang, Xinbo Gao

[**Paper**](https://arxiv.org/pdf/2505.13997)

* We propose **StPR**, a unified exemplar-free framework for video class-incremental learning. StPR tackles catastrophic forgetting under spatiotemporal shifts by explicitly disentangling frame-shared semantics and temporal dynamics. Specifically, we design **Frame-Shared Semantics Distillation (FSSD)** to preserve stable semantic channels, and **Temporal Decomposition-based Mixture-of-Experts (TD-MoE)** to dynamically route temporal experts without task IDs or stored exemplars.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/ICML26.png' alt="SIKD" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Symbiosis-Inspired Knowledge Distillation for Incremental Object Detection]

Mingyue Zeng, De Cheng, **Zhipeng Xu**, Huaijie Wang, Nannan Wang, Xinbo Gao

[**Paper**]

* We propose **SIKD** for incremental object detection, which leverages **object symbiosis** to preserve knowledge across old and new classes. SIKD designs **SpSD** to distill spatial dependencies from co-occurrence and occlusion regions, and **SeSD** to maintain old-class semantic topology through confidence-weighted prototype rank alignment, enabling a unified feature space that reduces old-new confusion and catastrophic forgetting.
</div>
</div>

# 🎖 Honors and Awards
- *2024-2025*: Academic Year **National Scholarship**.
- *2023-2024*: Master's **First-Class Scholarship** at XIDIAN University, Top 5%.
- *2023*: **Outstanding Graduate Representative**, Top 1%.

# 💬 Academic Services
- Reviewer for top-tier venues, including **TIP**, **CVPR 2026**, **ECCV 2026** and **NeurIPS 2026**.

# 💻 Internships
- *2025.06 - Present*, **Microsoft Research Asia (MSRA)**. Supervisors: Zilong Wang, Xinyang Jiang, Dongsheng Li.
  - Working on reasoning-driven multimodal LLMs for domain generalization.
  - Working on Pathology-Agent, a collaborative task-decomposition agent with multiple pathology foundation models.
