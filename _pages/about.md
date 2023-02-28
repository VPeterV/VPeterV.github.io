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

Hi, my name is Wei Liu (刘威). Currently, I am a second-year graduate student at ShanghaiTech University, advised by Prof. [KeWei Tu](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/). I am focusing on natural language processing (NLP) and machine learning (ML).

To be more specific, my research interests lie in:
  - **Structured prediction** (parsing, application of parsing algorithm to downstream tasks)
  - **Few-shot Learning** (application of PLMs/LLMs to zero/few-shot scenario)
  - **Efficient sequence modeling**
  - **Knowledge-enhanced NLP**
  

# 📝 Publications (* denotes equal contribution)

[Dynamic Programming in Rank Space: Scaling Structured Inference with Low-Rank HMMs and PCFGs](https://aclanthology.org/2022.naacl-main.353.pdf)

Songlin Yang\*, **Wei Liu\***, Kewei Tu

In Proceedings of NAACL, 2022. [code](https://github.com/VPeterV/RankSpace-Models)

[Knowledge-Based Chat Detection With False Mention Discrimination](https://ieeexplore.ieee.org/document/9414073)

**Wei Liu**, Peijie Huang, Dongzhu Liang, Zihao Zhou

In Proceedings of ICASSP, 2021.

[A Knowledge-gated Mechanism for Utterance Domain Classification](https://link.springer.com/chapter/10.1007/978-3-030-32236-6_12)

Zefeng Du, Peijie Huang, Yuhong He, **Wei Liu** & Jiankai Zhu 

In Proceedings of NLPCC, 2019.

# 💻 Internships
- *2022.07 - Present*, Alibaba DAMO academy
  - Doing some research about **pre-trained language models** and **few-shot learning**
  - One of the developers of [AdaSeq](https://github.com/modelscope/AdaSeq)

# 📖 Educations
- *2021.09 - Present*, ShanghaiTech University, M.S. in computer science
- *2017.09 - 2021.06*, South China Agricultural University, B.E. in computer science


