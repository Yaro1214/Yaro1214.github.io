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

Hi! I am Yaojie Zhang, a senior undergraduate majoring in Software Engineering at the University of Electronic Science and Technology of China (UESTC). In Fall 2027, I will join the School of Computer Science at Peking University as an M.S. student, advised by Prof. [Xupeng Miao](https://hsword.github.io/). Previously, I was a research intern at the EPIC Lab, Shanghai Jiao Tong University, advised by Prof. [Linfeng Zhang](http://www.zhanglinfeng.tech/).

My research focuses on efficient inference and serving for large language models, including both autoregressive language models and diffusion language models. I am particularly interested in speculative decoding, feature caching, and cache optimization. My goal is to develop practical algorithms and systems that accelerate language model generation, reduce memory usage, and preserve output quality.

<span class='anchor' id='news'></span>

# 🔥 News
- *2026.09*: &nbsp;🎉 Our paper "Domino" was accepted to EMNLP 2026.
- *2026.09*: &nbsp;🎉 We released the paper "DFlow: Enabling Verifier Information Flow in Block Diffusion Speculative Decoding".
- *2026.07*: &nbsp;🎉 Our paper "Mask Tokens as Prophet" was published in Findings of ACL 2026.
- *2026.05*: &nbsp;🎉 Our paper "dLLM-Cache" was accepted to ICML 2026.
- *2026.05*: &nbsp;🎉 We released the papers "FlexDraft" and "Domino".
- *2026.02*: &nbsp;🎉 Our paper "SlowFast Sampling" was accepted to ICLR 2026.
- *2026.01*: &nbsp;🎉 We released Innovator-VL, a fully open-source multimodal large language model for scientific discovery.
- *2025.10*: &nbsp;🎉 We released the paper "Mask Tokens as Prophet: Fine-Grained Cache Eviction for Efficient dLLM Inference".
- *2025.07*: &nbsp;🎉 We released the paper "Accelerating Diffusion Large Language Models with SlowFast Sampling: The Three Golden Principles".
- *2025.05*: &nbsp;🎉 We released the paper "dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching".
- *2025.03*: &nbsp;🤗 Started a research internship at EPIC Lab, Shanghai Jiao Tong University, focusing on efficient inference methods.

<span class='anchor' id='publications'></span>

# 📝 Publications (* denotes equal contribution.)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/dflow.png' alt="DFlow pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DFlow: Enabling Verifier Information Flow in Block Diffusion Speculative Decoding](https://arxiv.org/abs/2609.06498)

**Yaojie Zhang**, Linfeng Zhang, Bin Cui, Xupeng Miao.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026</div><img src='images/domino.png' alt="Domino pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Domino: Decoupling Causal Modeling from Autoregressive Drafting in Speculative Decoding](https://arxiv.org/abs/2605.29707)

Jianuo Huang *, **Yaojie Zhang** *, Qituan Zhang, Hao Lin, Hanlin Xu, Linfeng Zhang.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/flexdraft.png' alt="FlexDraft pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlexDraft: Flexible Speculative Decoding via Attention Tuning and Bonus-Guided Calibration](https://arxiv.org/abs/2605.20022)

**Yaojie Zhang** *, Jianuo Huang *, Junlong Ke, Yuhang Han, Yongji Long, Tianchen Zhao, Biqing Qi, Linfeng Zhang.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2026</div><img src='images/maskKV.png' alt="MaskKV" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mask Tokens as Prophet: Fine-Grained Cache Eviction for Efficient dLLM Inference](https://aclanthology.org/2026.findings-acl.170/)

Jianuo Huang *, **Yaojie Zhang** *, Yicun Yang, Benhao Huang, Linfeng Zhang.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/slowfast-sampling.png' alt="SlowFast Sampling" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerating Diffusion Large Language Models with SlowFast Sampling: The Three Golden Principles](https://proceedings.iclr.cc/paper_files/paper/2026/hash/08487598819cba9feca884ef0d442950-Abstract-Conference.html)

Qingyan Wei, **Yaojie Zhang**, Zhiyuan Liu, Puyu Zeng, Yuxuan Wang, Biqing Qi, Dongrui Liu, Linfeng Zhang.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/dLLM-Cache_pipeline.png' alt="dLLM-Cache pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching](https://arxiv.org/abs/2506.06295)

Zhiyuan Liu *, Yicun Yang *, **Yaojie Zhang**, Junjie Chen, Chang Zou, Qingyan Wei, Shaobo Wang, Yichen Zhu, Linfeng Zhang.

</div>
</div>

<span class='anchor' id='open-source-projects'></span>

# 🛠 Open-source Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Open Source</div><img src='images/innovator_vl.png' alt="Innovator-VL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Innovator-VL: A Multimodal Large Language Model for Scientific Discovery](https://github.com/InnovatorLM/Innovator-VL)

Zichen Wen *, Boxue Yang *, Shuang Chen, **Yaojie Zhang**, et al.

[[Paper](https://arxiv.org/abs/2601.19325)] [[Project Page](https://innovatorlm.github.io/Innovator-VL/)]

</div>
</div>

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2026* CCF Elite Collegiate Award (CCF优秀大学生)
- *2026* Sichuan Provincial College Student Comprehensive Quality A Level Certificate (四川省大学生“综合素质A级证书”)
- *2025* National Scholarship (国家奖学金)
- *2025* Tencent Scholarship (腾讯企业奖学金)
- *2024* National Scholarship (国家奖学金)
- *2024* Virtuos Corporate Scholarship (维塔士企业奖学金)

<span class='anchor' id='education'></span>

# 📖 Education
- *2027.09 - 2030.06*, Peking University, M.S. in Computer Science (Advised by Prof. [Xupeng Miao](https://hsword.github.io/))
- *2023.08 - 2027.06*, University of Electronic Science and Technology of China, B.E. in Software Engineering

<span class='anchor' id='internships'></span>

# 💻 Internships
- *2025.03 - 2026.07*, Research Intern, EPIC Lab, Shanghai Jiao Tong University (Advised by Prof. [Linfeng Zhang](http://www.zhanglinfeng.tech/)).
