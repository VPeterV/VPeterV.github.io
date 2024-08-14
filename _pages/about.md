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

Hi, my name is Wei Liu (刘威). Currently, I am an incoming Ph.D. student at [HKUST NLP](https://github.com/hkust-nlp), supervised by Prof. [Junxian He](https://jxhe.github.io/). Previously, I obtained my master's degree from ShanghaiTech University, advised by Prof. [Kewei Tu](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/).

I am focusing on natural language processing (NLP) and machine learning (ML).

To be more specific, my research interests lie in:
  - **Efficiency in Large Language Models (LLMs)**: Enhancing efficiency in training, inference, and handling long-range scenarios for Large Language Models (LLMs)
  - **Large Language Models (LLMs)**: Explorations of the emergent capabilities and applications in complex scenarios.
  - **Structured Predictions**: Parsing and application of parsing algorithm in downstream tasks. 
  - **Deep Generative Models**: Deep Latent-variable models.

# News
  - \[07/2024\] **Is Your Model Really a Good Math Reasoner?**Let's use [MathCheck](https://mathcheck.github.io/) to **Evaluate Mathematical Reasoning with a Checklist**! Unlike benchmarks that can be tackled merely through memorization, MathCheck reveals the more robust and comprehensive mathematical reasoning abilities of LLMs. It represents **Mathematical Intelligence More Linearly**!
  - \[01/2024\] Our [Deita](https://github.com/hkust-nlp/deita) paper [What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning](https://arxiv.org/abs/2312.15685) has been accepted by ICLR2024!
  - \[12/2023\] Our [Deita](https://github.com/hkust-nlp/deita) (**D**ata-**E**fficient **I**nstruction **T**uning for **A**lignment) Project has been released! Utilizing only **6K** samples of SFT data selected by Deita, along with **10K** randomly selected preference data, our Deita-7B model has achieved remarkable results, scoring **7.55** on the MT-Bench benchmark, **90.06%** on AlpacaEval, and **69.86** on the OpenLLM Benchmark! Welcome to try!

# 📝 Publications (* denotes equal contribution)

[Is Your Model Really A Good Math Reasoner? Evaluating Mathematical Reasoning with Checklist](https://arxiv.org/abs/2407.08733)

Preprint. [project](https://mathcheck.github.io/)

Zihao Zhou\*, Shudong Liu\*, Maizhen Ning, **Wei Liu**, Jindong Wang, Derek F. Wong, Xiaowei Huang, Qiufeng Wang, Kaizhu Huang

[What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning](https://arxiv.org/abs/2312.15685)

In Proceedings of ICLR, 2024. [project](https://github.com/hkust-nlp/deita)

**Wei Liu**\*, Weihao Zeng\*, Keqing He, Yong Jiang, Junxian He

[MathAttack: Attacking Large Language Models Towards Math Solving Ability](https://arxiv.org/pdf/2309.01686.pdf)

In Proceedings of AAAI, 2024.

Zihao Zhou, Qiufeng Wang, Mingyu Jin, Jie Yao, Jianan Ye, **Wei Liu**, Wei Wang, Xiaowei Huang, Kaizhu Huang


[SeqGPT: An Out-of-the-box Large Language Model for Open Domain
Sequence Understanding](https://arxiv.org/pdf/2308.10529.pdf)

In Proceedings of AAAI, 2024. [code](https://github.com/Alibaba-NLP/SeqGPT)

Tianyu Yu\*, Chengyue Jiang\*, Chao Lou\*, Shen Huang\*, Xiaobin Wang, **Wei Liu**, Jiong Cai, Yangning Li, Yinghui Li, Kewei Tu, Hai-Tao Zheng, Ningyu Zhang, Pengjun Xie, Fei Huang, Yong Jiang

[Simple Hardware-Efficient PCFGs with Independent Left and Right Productions](https://arxiv.org/abs/2310.14997)

**Wei Liu\***, Songlin Yang\*, Yoon Kim, Kewei Tu

In Findings of EMNLP, 2023. [code](https://github.com/sustcsonglin/TN-PCFG)

[Joint Entity and Relation Extraction with Span Pruning and Hypergraph Neural Networks](https://aclanthology.org/2023.emnlp-main.467.pdf)

Zhaohui Yan, Songlin Yang, **Wei Liu**, Kewei Tu

In Proceedings of EMNLP, 2023. [code](https://github.com/yanzhh/HGERE)

[Structured Mean-Field Variational Inference for Higher-Order Span-Based Semantic Role Labeling](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/acl23srl.pdf)

In Findings of ACL, 2023. [code](https://github.com/VPeterV/Structured-MFVI)

**Wei Liu**, Songlin Yang, Kewei Tu

<!-- Joint Entity and Relation Extraction with Span Pruning and Hypergraph Neural Networks (submitted) -->
[Dynamic Programming in Rank Space: Scaling Structured Inference with Low-Rank HMMs and PCFGs](https://aclanthology.org/2022.naacl-main.353.pdf)

Songlin Yang\*, **Wei Liu\***, Kewei Tu

In Proceedings of NAACL, 2022(<font color="#dd0000">Top-3 Score in ARR Jan 2022</font>). [code](https://github.com/VPeterV/RankSpace-Models)

[Knowledge-Based Chat Detection With False Mention Discrimination](https://ieeexplore.ieee.org/document/9414073)

**Wei Liu**, Peijie Huang, Dongzhu Liang, Zihao Zhou

In Proceedings of ICASSP, 2021.

[A Knowledge-gated Mechanism for Utterance Domain Classification](https://link.springer.com/chapter/10.1007/978-3-030-32236-6_12)

Zefeng Du, Peijie Huang, Yuhong He, **Wei Liu** & Jiankai Zhu 

In Proceedings of NLPCC, 2019.

# 👥 Service
- Reviewer: ARR, ACL, NAACL, EMNLP, COLM, ICLR

# 💻 Internships

- *2023.11 - present*, Shanghai AI Laboratory
  
- *2022.07 - 2023.10*, Alibaba DAMO Academy

# 🏆 Awards
- *2023* National Scholarship in China

# 📖 Educations
- *2024.09 - Present*, The Hong Kong University of Science and Technology, Ph.D. Student in computer science
- *2021.09 - 2024.07*, ShanghaiTech University, M.S. in computer science
- *2017.09 - 2021.06*, South China Agricultural University, B.E. in computer science


