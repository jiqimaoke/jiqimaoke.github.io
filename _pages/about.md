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

Hello, I am Keyan Zhou(周柯言), a PhD student at Fudan University and Shanghai Innovation Institute, under the supervision of [Prof. Ziwei He](https://scholar.google.com/citations?hl=en&user=3ii0orgAAAAJ) and [Prof. Xipeng Qiu](https://xpqiu.github.io/en.html).

My research focuses on long-context modeling, with an emphasis on improving how language models learn from and utilize long-form contexts. Specifically, I explore effective data strategies for long-context pre-training and develop post-training methods to enhance models’ retrieval and reasoning capabilities in long-context scenarios.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

**\* denotes equal contribution.**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/mmlongcite.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMLongCite: A Benchmark for Evaluating Fidelity of Long-Context Vision-Language Models](https://arxiv.org/pdf/2510.13276)

<strong>Keyan Zhou</strong>, Zecheng Tang, Lingfeng Ming, Guanghao Zhou, Qiguang Chen, Dan Qiao, Zheming Yang, Libo Qin, Minghui Qiu, Juntao Li, Min Zhang

- This work rigorously evaluates multimodal models' ability to utilize information in long-context settings through citation generation tasks and is a comprehensive multimodal benchmark covering images, videos, and documents. The findings highlight a significant gap between the correctness of their responses and their faithful citation of the context.

[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/bytedance/MMLongCite)
[![](https://img.shields.io/badge/🤗 HuggingFace-Data-red)](https://huggingface.co/datasets/Jonaszky123/MMLongCite)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/l-citeeval.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[L-CiteEval: A Suite for Evaluating Fidelity of Long-context Models](https://aclanthology.org/2025.acl-long.263.pdf)

Zecheng Tang\*, <strong>Keyan Zhou\*</strong>, Juntao Li, Baibei Ji, Jianye Hou, Min Zhang

- This work proposes a long-context benchmark L-CiteEval, which evaluates the citation quality of LCMs and highlights the tendency of current open-source LCMs to rely on intrinsic knowledge rather than the provided context for generating responses.

[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/LCM-Lab/L-CITEEVAL)
[![](https://img.shields.io/badge/🤗 HuggingFace-Data-red)](https://huggingface.co/datasets/Jonaszky123/L-CiteEval)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/cmd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CMD: a framework for Context-aware Model self-Detoxification](https://aclanthology.org/2024.emnlp-main.115.pdf)

Zecheng Tang\*, <strong>Keyan Zhou\*</strong>, Juntao Li, Yuyang Ding, Pinzheng Wang, Yan Bowen, Renjie Hua, Min Zhang

- This work proposes a context-aware detoxification framework, balancing detoxification and generation quality.

[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/ZetangForward/CMD-Context-aware-Model-self-Detoxification)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/sadr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revealing and Mitigating Over-attention in Knowledge Editing](https://openreview.net/pdf/6d4a9844cb479837281ce47668c12ff8833c06be.pdf)

Pinzheng Wang, Zecheng Tang, <strong>Keyan Zhou</strong>, Juntao Li, Qiaoming Zhu, Min Zhang

- This work reveals the over-attention issue in knowledge eiditing.

[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/PinzhengWang322/Reveal_Attention_Drift)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/loom.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LOOM-Scope: a comprehensive and efficient LOng-cOntext Model
evaluation framework](https://arxiv.org/pdf/2507.04723)

Zecheng Tang, Haitian Wang, Quantong Qiu, Baibei Ji, Ruoxi Sun, <strong>Keyan Zhou</strong>, Juntao Li, Min Zhang

- This work standardizes long-context evaluation across 22 benchmarks, integrates inference acceleration techniques, and introduces a lightweight comprehensive long-context benchmark called LOOMBench.

[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/LCM-Lab/LOOM-Scope)
[![](https://img.shields.io/badge/Demo-yellow)](https://loomscope.github.io/)

</div>
</div>

- `ACL 2023` [Can Diffusion Model Achieve Better Performance in Text Generation ? Bridging the Gap between Training and Inference !](https://aclanthology.org/2023.findings-acl.721.pdf)

  Zecheng Tang, Pinzheng Wang, **Keyan Zhou**, Juntao Li, Ziqiang Cao, Min Zhang
  [![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/LCM-Lab/Bridge_Gap_Diffusion)

# 🎖 Honors and Awards
- National Scholarship, Ministry of Education
- Soochow University Outstanding Graduate
- Huawei Scholarship
- Mathematical Contest in Modeling(MCM) Finalist Winner

# 📖 Educations
- *2026.09 - Now*, PhD candidate, Fudan University & Shanghai Innovation Institute, Shanghai.
- *2023.09 - 2026.06*, Master, Artificial Intelligence Research Institute, Soochow University, Suzhou.
- *2019.09 - 2023.06*, Bachelor, Institute of Computer Science and Technology, Soochow University, Suzhou.

# 💬 Invited Talks
- *2024.10*, [NICE-NLP, Presentation on Model Safety, EMNLP 2024](https://www.bilibili.com/video/BV1kVykYgEUe/?spm_id_from=333.1387.search.video_card.click)

# 💻 Internships
- *2025.12 - 2026.02*, Research Intern, Tencent, Beijing, China.
- *2025.06 - 2025.11*, Multi-modal LLM R&D Intern, ByteDance, Shanghai, China.
- *2025.03 - 2025.05*, Research Intern, MiraclePlus, Shanghai, China.