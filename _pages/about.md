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

I am a first-year PhD student at the College of Engineering, Westlake University, advised by Prof. Huan Wang.

My research interests include: 
- Video Large Language Model
- Multi-modal models
- Efficient AI
- Image Restoration

# 🔥 News

- *2025.11*: 🌟 **[Preprint]** A new work: [OmniZip](https://arxiv.org/abs/2511.14582) has been released. OmniZip is an audio-guided token compression method for fast OmniLLMs. Code is available at [Repo](https://github.com/KD-TAO/OmniZip).
- *2025.10*: **[Preprint]** We have released the preprint of [StreamingTom](https://arxiv.org/abs/2510.18269), the first token compression method for streaming setting efficient video understanding!
- *2025.09*: 🎉 **[NeurIPS'25]** [Poison as Cure](https://arxiv.org/abs/2501.19164) and [Hilitom](https://arxiv.org/abs/2505.21334) are accepted by NeurIPS 2025!
- *2025.08*: 🌟 **[Survey]** We are excited to present the first systematic review of multimodal long-context token compression methods: "When Tokens Talk Too Much". [arXiv](https://arxiv.org/abs/2507.20198) [Repo](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression)
- *2025.07*: 🎉 **[Reward]** Received the **"2025 Westlake University Xinrui Award" (西湖大学博士研究生新锐奖)**.
- *2025.05*: **[Preprint]** We have released the preprint of [Hilitom](https://arxiv.org/abs/2505.21334): "Holistic Token Merging for Fast Video Large Language Models".
- *2025.03*: **[Preprint]** We introduce [VidKV](https://arxiv.org/abs/2503.16257), a plug-and-play 1.x-bit KV Cache quantization for VideoLLMs. Code is available at [VidKV](https://github.com/KD-TAO/VidKV).
- *2025.02*: 🎉 **[CVPR'25]** [DyCoke](https://github.com/KD-TAO/DyCoke) is accepted by CVPR'25! DyCoke is a plug-and-play token compression method for fast VideoLLMs.
- *2025.02*: **[Preprint]** We have released the preprint of our paper [Poison as Cure](https://arxiv.org/abs/2501.19164). We propose a novel visual adversarial perturbation (VAP) method to mitigate the hallucination issue in VLMs.
- *2025.01*: 🎉 **[ICLR'25]** [MGFR](https://arxiv.org/html/2410.04161v2): "Overcoming False Illusions in Real-World Face Restoration with Multi-Modal Guided Diffusion Model" is accepted by ICLR 2025 **Spotlight**! The [Reface-HQ](https://github.com/KD-TAO/MGFR) dataset is also released! 
- *2024.11*: **[Preprint]** We have released the preprint of our paper [DyCoke](https://github.com/KD-TAO/DyCoke).


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/OmniZip.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniZip: Audio-Guided Dynamic Token Compression for Fast Omnimodal Large Language Models.](https://arxiv.org/abs/2109.15166) \\
`Keda Tao`, Kele Shao, Bohan Yu, Weiqiang Wang, Jian Liu, Huan Wang.

[**Project**](https://github.com/KD-TAO/OmniZip) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=paper)](https://huggingface.co/papers/2511.14582)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Soptlight</div><img src='images/MGFR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming False Illusions in Blind Face Restoration with Multi-Modal Guided Diffusion Model.]([https://arxiv.org/abs/2109.15166](https://arxiv.org/abs/2410.04161)) **Spotlight**\\
`Keda Tao`, Jinjin Gu, Yulun Zhang, Xiucheng Wang, Nan Cheng.

[**Project & Reface-HQ Dataset**](https://github.com/KD-TAO/MGFR)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/DyCoke.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DyCoke: Dynamic Compression of Tokens for Fast Video Large Language Models.]([https://arxiv.org/abs/2109.15166](https://arxiv.org/abs/2411.15024)) \\
`Keda Tao`, Can Qin, Haoxuan Yu, Yang Sui, Huan Wang.

[**Project**](https://github.com/KD-TAO/DyCoke) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=paper)](https://huggingface.co/papers/2411.15024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/token_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When Tokens Talk Too Much: A Survey of Multimodal Long-Context Token Compression across Images, Videos, and Audios.]([[https://arxiv.org/abs/2109.15166](https://arxiv.org/abs/2411.15024](https://arxiv.org/abs/2507.20198))) \\
Kele Shao*, `Keda Tao*`, Kejia Zhang, Sicheng Feng, Mu Cai, Yuzhang Shang, Haoxuan You, Can Qin, Yang Sui, Huan Wang. (* Equal Contribution)

[**Project**](https://github.com/cokeshao/Awesome-Multimodal-Token-Compression) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=paper)](https://huggingface.co/papers/2507.20198)

</div>
</div>

<div class='paper-box-text' markdown="1">

-	Xiucheng Wang*, `Keda Tao*`,  Nan Cheng, Zhisheng Yin, Zan Li, Yuan Zhang, Xuemin (Sherman) Shen. RadioDiff: An Effective Generative Diffusion Model for Sampling-Free Dynamic Radio Map Construction. TCCN, 2024.

</div>

<div class='paper-box-text' markdown="1">

-	`Keda Tao`, Haoxuan Yu, Yang Sui, Can Qin, Huan Wang. Plug-and-Play 1.x-Bit KV Cache Quantization for Video Large Language Models. [arXiv](https://arxiv.org/abs/2503.16257), 2025.
[[Github]](https://github.com/KD-TAO/VidKV) [[Page]](https://kd-tao.github.io/VidKV.Web.io/)

</div>

<div class='paper-box-text' markdown="1">

-	Kejia Zhang, `Keda Tao`, Jiasheng Tang, Huan Wang. Poison as Cure: Visual Noise for Mitigating Object Hallucinations in LVMs. [arXiv](https://arxiv.org/abs/2501.19164), 2025.
[[Github]](https://github.com/KejiaZhang-Robust/VAP)

</div>

<div class='paper-box-text' markdown="1">

-	Kele Shao, `Keda Tao`, Can Qin, Haoxuan You, Yang Sui, Huan Wang. HoliTom: Holistic Token Merging for Fast Video Large Language Models. [arXiv](https://arxiv.org/abs/2505.21334), 2025.
[[Github]](https://github.com/cokeshao/HoliTom)

</div>

<div class='paper-box-text' markdown="1">

-	Haoyu Chen, `Keda Tao`, Yizao Wang, Xinlei Wang, Lei Zhu, Jinjin Gu. PhotoArtAgent: Intelligent Photo Retouching with Language Model-Based Artist Agents. [arXiv](https://arxiv.org/abs/2505.23130), 2025.

</div>

<div class='paper-box-text' markdown="1">

-	Sicheng Feng, `Keda Tao`, Huan Wang. Is Oracle Pruning the True Oracle? [arXiv](https://arxiv.org/abs/2412.00143), 2025.
[[Github]]([https://fscdc.github.io/Oracle-Pruning-Sanity-Check/])

</div>


# 🏭 Internships
- *2023.05 - 2024.05*, UNIC Lab, Xidian University, China.
- *2024.06 - now*, ENCODE Lab, Westlake University, China.

  
