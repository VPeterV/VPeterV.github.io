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

Hi, my name is Wei Liu (刘威). Currently, I am a 2nd-year Ph.D. student at [HKUST NLP](https://github.com/hkust-nlp), supervised by Prof. [Junxian He](https://jxhe.github.io/). Previously, I obtained my master's degree from ShanghaiTech University, advised by Prof. [Kewei Tu](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/).

I am interested in investigating scalable and principled methods to build performant AI models that can interact with complex, real-world environments.

# News

<style>
.news-container {
  max-height: 200px;
  overflow-y: auto;
  padding: 15px 15px 15px 18px;
  margin-bottom: 20px;
  border-left: 3px solid #2962ff;
  border-radius: 8px;
  background: linear-gradient(to bottom, rgba(255,255,255,0.9), rgba(255,255,255,0.95));
  box-shadow: 
    0 -8px 16px -8px rgba(0, 0, 0, 0.1),
    0 8px 16px -8px rgba(0, 0, 0, 0.1),
    0 2px 8px rgba(0, 0, 0, 0.06);
}
.news-container::-webkit-scrollbar {
  width: 6px;
}
.news-container::-webkit-scrollbar-track {
  background: #f1f1f1;
  border-radius: 3px;
}
.news-container::-webkit-scrollbar-thumb {
  background: #c1c1c1;
  border-radius: 3px;
}
.news-container::-webkit-scrollbar-thumb:hover {
  background: #a1a1a1;
}
</style>

<div class="news-container" markdown="1">

- \[05/2025\] We release [Laser](https://arxiv.org/abs/2505.15612) to improve efficacy-efficiency trade-off of Large Reasoning Models, improving AIME24 +6.1 while reducing 63% of tokens used!
- \[05/2025\] Three papers accepted by ICML 2025!
- \[01/2025\] Announce our latest effort on O/R-1 Style Model and Scalable Reinforcement Learning for LLM Reasoning! [SimpleRL-Reason](https://hkust-nlp.notion.site/simplerl-reason) [Twitter](https://x.com/junxian_he/status/1883183099787571519)
- \[11/2024\] Announce [M-STAR](https://mstar-lmm.github.io/) (**M**ultimodal **S**elf-Evolving **T**r**A**ining for **R**easoning) project! M-STAR aims at facilitating multimodal reasoning via self-evolving training. More details will be released soon!
- \[07/2024\] **Is Your Model Really a Good Math Reasoner?**Let's use [MathCheck](https://mathcheck.github.io/) to **Evaluate Mathematical Reasoning with a Checklist**! Unlike benchmarks that can be tackled merely through memorization, MathCheck reveals the more robust and comprehensive mathematical reasoning abilities of LLMs. It represents **Mathematical Intelligence More Linearly**!
- \[01/2024\] Our [Deita](https://github.com/hkust-nlp/deita) paper [What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning](https://arxiv.org/abs/2312.15685) has been accepted by ICLR2024!
- \[12/2023\] Our [Deita](https://github.com/hkust-nlp/deita) (**D**ata-**E**fficient **I**nstruction **T**uning for **A**lignment) Project has been released! Utilizing only **6K** samples of SFT data selected by Deita, along with **10K** randomly selected preference data, our Deita-7B model has achieved remarkable results, scoring **7.55** on the MT-Bench benchmark, **90.06%** on AlpacaEval, and **69.86** on the OpenLLM Benchmark! Welcome to try!

</div>

# 📝 Publications (* denotes equal contribution)

<style>
.pub-toggle-container {
  display: flex;
  gap: 8px;
  margin-bottom: 20px;
}
.pub-toggle-btn {
  padding: 8px 16px;
  border: 2px solid #2962ff;
  background: transparent;
  color: #2962ff;
  border-radius: 20px;
  cursor: pointer;
  font-weight: 600;
  font-size: 14px;
  transition: all 0.3s ease;
}
.pub-toggle-btn:hover {
  background: rgba(41, 98, 255, 0.1);
}
.pub-toggle-btn.active {
  background: #2962ff;
  color: white;
}
.pub-item {
  margin-bottom: 1.5em;
}
.pub-item.full-only {
  display: none;
}
.show-full .pub-item.full-only {
  display: block;
}
</style>

<div class="pub-toggle-container">
  <button class="pub-toggle-btn active" onclick="showSelected()">Selected</button>
  <button class="pub-toggle-btn" onclick="showFull()">Full List</button>
</div>

<div id="publications-container">

<div class="pub-item" markdown="1">

[The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution
](https://arxiv.org/abs/2510.25726)

Junlong Li, Wenshuo Zhao, Jian Zhao, Weihao Zeng, Haoze Wu, Xiaochen Wang, Rui Ge, Yuxuan Cao, Yuzhen Huang, **Wei Liu**, Junteng Liu, Zhaochen Su, Yiyang Guo, Fan Zhou, Lueyang Zhang, Juan Michelini, Xingyao Wang, Xiang Yue, Shuyan Zhou, Graham Neubig, Junxian He

Preprint. \| [Project](https://toolathlon.xyz/introduction)

[Learn to Reason Efficiently with Adaptive Length-based Reward Shaping](https://arxiv.org/abs/2505.15612)

**Wei Liu**, Ruochen Zhou, Yiyun Deng, Yuzhen Huang, Junteng Liu, Yuntian Deng, Yizhe Zhang, Junxian He

Preprint. \| [Project](https://github.com/hkust-nlp/Laser)

</div>

<div class="pub-item" markdown="1">

[Diving into Self-Evolving Training for Multimodal Reasoning](https://arxiv.org/abs/2412.17451)

**Wei Liu**\*, Junlong Li\*, Xiwen Zhang, Fan Zhou, Yu Cheng, Junxian He

In Proceedings of ICML, 2025. \| Reasoning and Planning for Large Language Models Workshop at ICLR 2025. [project](https://mstar-lmm.github.io/)

</div>

<div class="pub-item full-only" markdown="1">

[Divide and Conquer: Grounding LLMs as Efficient Decision-Making Agents
via Offline Hierarchical Reinforcement Learning]()

Zican Hu, **Wei Liu**, Xiaoye Qu, Xiangyu Yue, Chunlin Chen, Zhi Wang, Yu Cheng

In Proceedings of ICML, 2025.

</div>

<div class="pub-item full-only" markdown="1">

[Bring Reason to Vision: Understanding Perception and Reasoning through Model Merging]()

Shiqi Chen\*, Jinghan Zhang\*, Tongyao Zhu, **Wei Liu**, Siyang Gao, Miao Xiong, Manling Li, Junxian He 

In Proceedings of ICML, 2025.

</div>

<div class="pub-item" markdown="1">

[SimpleRL-Zoo: Investigating and Taming Zero Reinforcement Learning for Open Base Models in the Wild](https://arxiv.org/abs/2503.18892)

Weihao Zeng\*, Yuzhen Huang\*, Qian Liu\*, **Wei Liu**, Keqing He, Zejun Ma, Junxian He

Preprint. [project](https://hkust-nlp.notion.site/simplerl-reason)

</div>

<div class="pub-item" markdown="1">

[7B Model and 8K Examples: Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient](https://hkust-nlp.notion.site/simplerl-reason)

Weihao Zeng\*, Yuzhen Huang\*, **Wei Liu**, Keqing He, Qian Liu, Zejun Ma, Junxian He

Preprint. [project](https://hkust-nlp.notion.site/simplerl-reason) [Twitter](https://x.com/junxian_he/status/1883183099787571519)

</div>

<div class="pub-item" markdown="1">

[Is Your Model Really A Good Math Reasoner? Evaluating Mathematical Reasoning with Checklist](https://arxiv.org/abs/2407.08733)

Zihao Zhou\*, Shudong Liu\*, Maizhen Ning, **Wei Liu**, Jindong Wang, Derek F. Wong, Xiaowei Huang, Qiufeng Wang, Kaizhu Huang


In Proceedings of ICLR, 2025. [project](https://mathcheck.github.io/)

</div>

<div class="pub-item" markdown="1">

[What Makes Good Data for Alignment? A Comprehensive Study of Automatic Data Selection in Instruction Tuning](https://arxiv.org/abs/2312.15685)

**Wei Liu**\*, Weihao Zeng\*, Keqing He, Yong Jiang, Junxian He

In Proceedings of ICLR, 2024. [project](https://github.com/hkust-nlp/deita)

</div>

<div class="pub-item full-only" markdown="1">

[MathAttack: Attacking Large Language Models Towards Math Solving Ability](https://arxiv.org/pdf/2309.01686.pdf)

Zihao Zhou, Qiufeng Wang, Mingyu Jin, Jie Yao, Jianan Ye, **Wei Liu**, Wei Wang, Xiaowei Huang, Kaizhu Huang

In Proceedings of AAAI, 2024.

</div>

<div class="pub-item full-only" markdown="1">

[SeqGPT: An Out-of-the-box Large Language Model for Open Domain
Sequence Understanding](https://arxiv.org/pdf/2308.10529.pdf)

Tianyu Yu\*, Chengyue Jiang\*, Chao Lou\*, Shen Huang\*, Xiaobin Wang, **Wei Liu**, Jiong Cai, Yangning Li, Yinghui Li, Kewei Tu, Hai-Tao Zheng, Ningyu Zhang, Pengjun Xie, Fei Huang, Yong Jiang

In Proceedings of AAAI, 2024. [code](https://github.com/Alibaba-NLP/SeqGPT)

</div>

<div class="pub-item" markdown="1">

[Simple Hardware-Efficient PCFGs with Independent Left and Right Productions](https://arxiv.org/abs/2310.14997)

**Wei Liu\***, Songlin Yang\*, Yoon Kim, Kewei Tu

In Findings of EMNLP, 2023. [code](https://github.com/sustcsonglin/TN-PCFG)

</div>

<div class="pub-item full-only" markdown="1">

[Joint Entity and Relation Extraction with Span Pruning and Hypergraph Neural Networks](https://aclanthology.org/2023.emnlp-main.467.pdf)

Zhaohui Yan, Songlin Yang, **Wei Liu**, Kewei Tu

In Proceedings of EMNLP, 2023. [code](https://github.com/yanzhh/HGERE)

</div>

<div class="pub-item" markdown="1">

[Structured Mean-Field Variational Inference for Higher-Order Span-Based Semantic Role Labeling](https://faculty.sist.shanghaitech.edu.cn/faculty/tukw/acl23srl.pdf)

**Wei Liu**, Songlin Yang, Kewei Tu

In Findings of ACL, 2023. [code](https://github.com/VPeterV/Structured-MFVI)

</div>

<div class="pub-item" markdown="1">

<!-- Joint Entity and Relation Extraction with Span Pruning and Hypergraph Neural Networks (submitted) -->
[Dynamic Programming in Rank Space: Scaling Structured Inference with Low-Rank HMMs and PCFGs](https://aclanthology.org/2022.naacl-main.353.pdf)

Songlin Yang\*, **Wei Liu\***, Kewei Tu

In Proceedings of NAACL, 2022(<font color="#dd0000">Top-3 Score in ARR Jan 2022</font>). [code](https://github.com/VPeterV/RankSpace-Models)

</div>

<div class="pub-item full-only" markdown="1">

[Knowledge-Based Chat Detection With False Mention Discrimination](https://ieeexplore.ieee.org/document/9414073)

**Wei Liu**, Peijie Huang, Dongzhu Liang, Zihao Zhou

In Proceedings of ICASSP, 2021.

</div>

<div class="pub-item full-only" markdown="1">

[A Knowledge-gated Mechanism for Utterance Domain Classification](https://link.springer.com/chapter/10.1007/978-3-030-32236-6_12)

Zefeng Du, Peijie Huang, Yuhong He, **Wei Liu** & Jiankai Zhu 

In Proceedings of NLPCC, 2019.

</div>

</div>

<script>
function showSelected() {
  document.getElementById('publications-container').classList.remove('show-full');
  document.querySelectorAll('.pub-toggle-btn')[0].classList.add('active');
  document.querySelectorAll('.pub-toggle-btn')[1].classList.remove('active');
}
function showFull() {
  document.getElementById('publications-container').classList.add('show-full');
  document.querySelectorAll('.pub-toggle-btn')[0].classList.remove('active');
  document.querySelectorAll('.pub-toggle-btn')[1].classList.add('active');
}
</script>

# 👥 Service
- Reviewer: ARR, ACL, NAACL, EMNLP, COLM, NeurIPS, ICLR, ICML

# 💻 Internships

- *2025.06 - Present*, TikTok AI Innovation Center, Singapore, Research Scientist Intern, advised by [Qian Liu](https://siviltaram.github.io/)

- *2023.11 - 2024.08*, Shanghai AI Laboratory, Research Intern, advised by Prof. [Yu Cheng](https://ych133.github.io/)
  
- *2022.07 - 2023.10*, Alibaba DAMO Academy, Research Intern, advised by [Yong Jiang](https://jiangyong.site/)

# 🏆 Awards
- *2023* National Scholarship in China

# 📖 Educations
- *2024.09 - Present*, The Hong Kong University of Science and Technology, Ph.D. Student in computer science
- *2021.09 - 2024.07*, ShanghaiTech University, M.S. in computer science
- *2017.09 - 2021.06*, South China Agricultural University, B.E. in computer science


