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

# ✨ About Me

I'm a Ph.D. candidate at the Visual Intelligence and Pattern Analysis (VIPA) Lab, Zhejiang University, supervised by Prof. [Zunlei Feng](https://person.zju.edu.cn/fengzunlei) and Prof. [Mingli Song](https://scholar.google.com/citations?user=7oLbhAwAAAAJ&hl=en). Additionally, my research has been significantly shaped by the insightful support of Prof. [Jian Lou](https://sites.google.com/view/jianlou) and Prof. [Ruoxi Jia](https://ruoxijia.net/).

Presently, I am a visiting student at Nanyang Technological University, working under the esteemed supervision of Prof. [Tianwei Zhang](https://personal.ntu.edu.sg/tianwei.zhang/).

## 🔬 Research Interests

- **Trustworthy Generative AI**  
  Exploring reliability, controllability, and ethical alignment in generative models, with a focus on safety and transparency.

- **Efficient Deep Learning**  
  Designing lightweight, high-performance neural architectures and training strategies to reduce computational cost without compromising accuracy.

I’ll be sharing research updates and progress here from time to time—stay tuned!

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='publications'></span>

# 📝 Publications 
<div>
  <p>(* indicates equal contribution.)</p>
  <ul>
  <li class="paper-box-new">
      <span class="sec-conference purple">CCS 2026</span>
      <strong>Understanding and Preserving Safety in Fine-Tuned LLMs</strong>
      ｜<a href="https://arxiv.org/abs/2601.10141"><strong>Pdf</strong></a>
      <!-- ｜<a href="https://github.com/Thecommonirin/TITA"><strong>Code</strong></a> -->
      <br>
      <em>Jiawen Zhang, Yangfan Hu, Kejia Chen, Lipeng He, Jiachen Ma, Jian Lou, Dan Li, Jian Liu, Xiaohu Yang, Ruoxi Jia</em>
  </li>
  <li class="paper-box-new">
      <span class="sec-conference purple">ACL 2026</span>
      <strong>Token-Level Inference-Time Alignment for Vision-Language Models</strong>
      ｜<a href="https://arxiv.org/abs/2510.21794"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Thecommonirin/TITA"><strong>Code</strong></a>
      <br>
      <em>Kejia Chen, Junjun Zheng, Jiawen Zhang, Manxi Lin, Xiao Pan, Jiacong Hu, Jian Lou, Zunlei Feng, Mingli Song</em>
  </li>
  <li class="paper-box-new">
      <span class="sec-conference purple">PR 2026</span>
      <strong>Self-Improved Holistic Alignment for Preference Enhancement</strong>
      ｜<a href="https://www.sciencedirect.com/science/article/abs/pii/S0031320326002037"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Thecommonirin/SHAPE"><strong>Code</strong></a>
      <br>
      <em>Kejia Chen, Jiawen Zhang, Jiazheng Yang, Zunlei Feng, Mingli Song</em>
  </li>
  <li class="paper-box-new">
      <span class="sec-conference purple">ICLR 2026</span>
      <strong>Safety at One Shot: Patching Fine-Tuned LLMs with A Single Instance</strong>
      ｜<a href="https://arxiv.org/abs/2601.01887"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Kevin-Zh-CS/safety-at-one-shot"><strong>Code</strong></a>
      <br>
      <em>Jiawen Zhang, Lipeng He, Kejia Chen, Jian Lou, Jian Liu, Xiaohu Yang, Ruoxi Jia</em>
  </li>
  <li class="paper-box-new">
      <span class="sec-conference pink">Usenix 2025</span>
      <strong>Activation Approximations Can Incur Safety Vulnerabilities in Aligned LLMs: Comprehensive Analysis and Defense</strong>
      ｜<a href="https://arxiv.org/abs/2502.00840"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Kevin-Zh-CS/QuadA"><strong>Code</strong></a>
      <br>
      <em>Jiawen Zhang*, Kejia Chen*, Lipeng He, Jian Lou, Dan Li, Zunlei Feng, Mingli Song, Kui Ren, Xiaohu Yang</em>
    </li>
    <li class="paper-box-new">
      <span class="sec-conference pink">ICML 2025</span>
      <strong>Assessing Safety Risks and Quantization-aware Safety Patching for Quantized Large Language Models</strong>
      ｜<a href="https://openreview.net/pdf?id=jywq7qJLt5"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Thecommonirin/Qresafe"><strong>Code</strong></a>
      <br>
      <em>Kejia Chen*, Jiawen Zhang*, Jiacong Hu, Yu Wang, Mingli Song, Jian Lou, Zunlei Feng</em>
    </li>
    <li class="paper-box-new">
      <span class="sec-conference green">ECAI 2024</span>
      <strong>SecPE: Secure Prompt Ensembling for Private and Robust Large Language Models</strong>
      ｜<a href="https://arxiv.org/pdf/2502.00847"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/Kevin-Zh-CS/SecPE"><strong>Code</strong></a>
      <br>
      <em>Jiawen Zhang*, Kejia Chen*, Zunlei Feng, Mingli Song, Jian Liu, Jian Lou, Xiaohu Yang</em>
    </li>
    <li class="paper-box-new">
      <span class="sec-conference green">NDSS 2025</span>
      <strong>Nexus: Secure Transformer Inference Made Non-interactive</strong>
      ｜<a href="https://eprint.iacr.org/2024/136"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/zju-abclab/NEXUS"><strong>Code</strong></a>
      <br>
      <em>Jiawen Zhang, Xinpeng Yang, Lipeng He, Kejia Chen, Wen-jie Lu, Yinghao Wang, Xiaoyang Hou, Jian Liu, Kui Ren, Xiaohu Yang</em>
    </li>
    <li class="paper-box-new">
      <span class="sec-conference blue">NeurIPS 2024</span>
      <strong>Transformer-Doctor: Diagnosing and Treating Vision Transformers</strong>
      ｜<a href="https://proceedings.neurips.cc/paper_files/paper/2024/file/614f8eba720cfc7ff00274bd64fb0a3f-Paper-Conference.pdf"><strong>Pdf</strong></a>
      ｜<a href="https://github.com/jiaconghu/Transformer-Doctor"><strong>Code</strong></a>
      <br>
      <em>Jiacong Hu, Hao Chen, Kejia Chen, Yang Gao, Jingwen Ye, Xingen Wang, Mingli Song, Zunlei Feng</em>
    </li>
    <li class="paper-box-new">
      <span class="sec-conference blue">BCRA 2024</span>
      <strong>Private, Atomic, Incentive Mechanism for Federated Learning based on Blockchain</strong>
      ｜<a href="https://www.sciencedirect.com/science/article/pii/S2096720924000848"><strong>Pdf</strong></a>
      <!-- ｜<a href="https://github.com/jiaconghu/Transformer-Doctor"><strong>Code</strong></a> -->
      <br>
      <em>Kejia Chen*, Jiawen Zhang*, Xuanming Liu, Zunlei Feng, Xiaohu Yang</em>
    </li>
  </ul>
</div>

<span class='anchor' id='review-services'></span>

# 📖 Review Services 
I am honored to contribute to the research community as a technical reviewer for several premier conferences and journals in AI and Security. 

My service includes:
- Conference Program Committee: ICML, ICLR, NeurIPS, CVPR, ICCV, ECCV, ACL, EMNLP.
- Journal Peer Review: IEEE Transactions on Image Processing (TIP), IEEE Transactions on Information Forensics and Security (TIFS).

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->