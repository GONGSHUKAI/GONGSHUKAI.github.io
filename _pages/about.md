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

# About me

My name is Shukai Gong (龚舒凯). I'm a first-year MPhil student in Computer Science at Peking University, advised by [Prof. Daquan Zhou](https://zhoudaquan.github.io/homepage.io/index.html). Previously, I received my B.S. in Data Science from Renmin University of China in 2026, where I was advised by [Prof. Hongteng Xu](https://hongtengxu.github.io) and [Prof. Feng Zhou](http://zhoufeng6288.github.io). My current research interests lie in **Robotics and Video Generation**. For potential collaboration, please feel free to reach out to me at gongshukai26[at]stu.pku.edu.cn.

# News

- **2026.10**: [*ViGAR*](https://arxiv.org/abs/2610.02368) is fully open-sourced and is released on arXiv.

- **2026.05**: [*StableVLA*](https://arxiv.org/abs/2507.09252) has been accepted by **ICML 2026**.

- **2025.09**: [*TPP-SD*](https://arxiv.org/abs/2507.09252) has been accepted by **NeurIPS 2025**.

- **2025.01**: [*USPTO-LLM*](https://dl.acm.org/doi/10.1145/3701716.3715295) has been accepted by **WWW 2025**.

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/vigar.jpg' alt="paper thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Rethinking World-Action Model for Compositional and In-Context Robotic Manipulation](https://arxiv.org/abs/2610.02368)**

**Shukai Gong**\*, Xuanran Zhai\*, Yintianrun Zhang\*, Ruopeng Cui, Ye Huang, Yiyang Fu, Dexuan Lyu, Chaojie Li, Xinyi Song, Peiwen Lin, Chuang Wang, Mingyuan Jia, Yufan Deng, Jiaxin Fang, Bo Liang, Jiaxin Li, Yuxiang Gao, Hao Liu, Daquan Zhou

[**Paper**](https://arxiv.org/abs/2610.02368) \| [**Code**](https://github.com/DAGroup-PKU/ViGAR) \| [**Model**](https://huggingface.co/DAGroup-PKU/ViGAR) \| [**Project Page**](https://dagroup-pku.github.io/ViGAR/)

We propose ViGAR, a hierarchical world-action model that factorizes long-horizon manipulation into visual subgoal planning and subgoal execution on a shared pretrained world model. ViGAR achieves strong compositional manipulation in both simulation and the real world, and generalizes to unseen tasks via in-context steering with a goal image, without any policy parameter updates.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/stablevla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**StableVLA: Towards Robust Vision-Language-Action Models without Extra Data**

Yiyang Fu, Chubin Zhang, **Shukai Gong**, Yufan Deng, Kaiwei Sun, Qiyang Min, Qibin Hou, Yansong Tang, Jianan Wang†, Daquan Zhou†

[**Paper**](https://arxiv.org/abs/2605.18287) \| [**Code**](https://github.com/DAGroup-PKU/HumanNet/blob/main/docs/stablevla.md) \| [**Model**](https://huggingface.co/DAGroup-PKU/StableVLA) \| [**Project Page**](https://dagroup-pku.github.io/StableVLA/)

We propose a lightweight adapter module for VLA, IB-Adapter, which selectively filters potential noise from visual inputs. Without requiring any extra data or augmentation strategies, IB-Adapter consistently improves the robostness of VLA, while adding fewer than 10M parameters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/humanscale.jpg' alt="paper thumbnail" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[HumanScale: Egocentric Human Video Can Outperform Real-Robot Data for Embodied Pretraining](https://arxiv.org/abs/2606.20521)**

Juncheng Ma\*, Jianxin Bi\*, Yufan Deng, Xuanran Zhai, Kewei Zhang, Ye Huang, Bo Liang, **Shukai Gong**, Jiankai Tu, Xiaotian Tang, Jiaxin Li, Kaiqi Chen, Duomin Wang, Yuqi Wang, Bingyi Kang, Eric Huang, Zhiyang Dou, Zhen Dong, Enze Xie, Wojciech Matusik, Tat-Seng Chua, Daquan Zhou

<span style="font-size:0.85em">(\* stands for equal contribution)</span>

[**Paper**](https://arxiv.org/abs/2606.20521) \| [**Code**](https://github.com/DAGroup-PKU/HumanNet/)

With a carefully designed filtering and labeling pipeline, we show that egocentric human video is a scalable pretraining source for embodied foundation models that surpasses real-robot data, especially in out-of-distribution generalization.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/tppsd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**TPP-SD: Accelerating Transformer Point Process Sampling with Speculative Decoding**

**Shukai Gong**\*, Yiyang Fu\*, Fengyuan Ran\*, Quyu Kong, Feng Zhou†

<span style="font-size:0.85em">(\* stands for equal contribution)</span>

[**Paper**](https://arxiv.org/pdf/2507.09252) \| [**Code**](https://github.com/GONGSHUKAI/tppsd)

By identifying the structural similarities between thinning algorithms for TPPs and speculative decoding for language models, we develop
TPP-SD, which maintains the identical output distribution as autoregressive sampling while achieving 2-6× speedup on both synthetic and real datasets.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2025</div><img src='images/uspto-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**USPTO-LLM: A Large Language Model-Assisted Information-enriched Chemical Reaction Dataset**

Shen Yuan\*, **Shukai Gong**\*, Hongteng Xu†

<span style="font-size:0.85em">(\* stands for equal contribution)</span>

[**Paper**](https://dl.acm.org/doi/10.1145/3701716.3715295) \| [**Dataset**](https://zenodo.org/records/14396156)

we construct an information-enriched chemical reaction dataset called USPTO-LLM, which comprises over 247K chemical reactions extracted from the patent documents of USPTO encompassing abundant information on reaction conditions. Experiments show that USPTO-LLM helps pre-train the existing retrosynthesis methods and the condition information in the dataset helps improve the model performance.

</div>
</div>

# Experiences

<div class='paper-box'><div class='paper-box-image' style="text-align: center;"><div><div class="badge"></div><img src='images/bytedance.jpg' alt="sym" style="display: inline-block; width: 80%;"></div></div>
<div class='paper-box-text' markdown="1">

**Research Intern, Bytedance Seed, Beijing, 2026.04 - present**

Research on physical video generation and embodied AI.

</div>
</div>
<div class='paper-box'><div class='paper-box-image' style="text-align: center;"><div><div class="badge"></div><img src='images/pixverse.jpg' alt="sym" style="display: inline-block; width: 80%;"></div></div>
<div class='paper-box-text' markdown="1">

**Research Intern, Pixverse, Beijing, 2025.07 - 2026.01**

Research on the acceleration and long-video adaption of visual-audio joint generation.


</div>
</div>

# Honors and Awards

- *2025*, Jing Dong Future Scholar, Renmin University of China (¥10000 CNY). 

- *2025*, The ICBC Award for Outstanding Student in Integrated Innovation (¥10000 CNY). 

- *2024*, The Jing Dong Premium Scholarship, Renmin University of China (¥10000 CNY). 

# Educations

- *2026.09 - present*, MPhil in Computer Science, Peking University. 

- *2022.09 - 2026.06*, B.S in Data Science and Economics, Renmin University of China.


