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
  - **Efficient Sequence Modeling**: Exploring more efficient model architecture, particularly for long-range sequence.
  - **Structured Predictions**: Parsing and application of parsing algorithm in downstream tasks.
  - **Deep Generative Models**: Deep Latent-variable models.
  - **Large Language Models (LLMs)**: Explorations of their Emergent Capabilities and Applications in Complex Scenarios.

# 📝 Publications (* denotes equal contribution)

[Structured Mean-Field Variational Inference for Higher-Order Span-Based Semantic Role Labeling](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/acl23srl.pdf)

In Findings of ACL, 2023. [code](https://github.com/VPeterV/Structured-MFVI)

**Wei Liu**, Songlin Yang, Kewei Tu

<!-- Joint Entity and Relation Extraction with Span Pruning and Hypergraph Neural Networks (submitted) -->
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
  - [MAOE (Paper underwriting)](https://www.modelscope.cn/models/damo/nlp_maoe_named-entity-recognition_general/summary): A pre-trained language model that supports (ultra-)fine-grained named entity recognition. Welcome to try out our model: [Try it now](https://www.modelscope.cn/studios/TTCoding/maoe_fsl_ner/summary)

# 📖 Educations
- *2021.09 - Present*, ShanghaiTech University, M.S. in computer science
- *2017.09 - 2021.06*, South China Agricultural University, B.E. in computer science


