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

Welcome to Yifan Wei (Eric)'s Personal Homepage!

I am a PhD student at the [Beihang University](https://scse.buaa.edu.cn/), School of Computer Science and Engineering. 
I have spent wonderful time at [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/) as a master student, advised by Prof [Kang Liu](http://www.nlpr.ia.ac.cn/cip/~liukang/index.html).

My research interests lie in the field of natural language processing (NLP), with a focus on Large Language Models (LLMs), including Question Answering and Knowledge Editing. Currently, I am highly intrigued by exploring the intersection of LLMs and AI safety.
To date, I have authored three papers as the first author, which have been published at AI conferences including the CIKM, EMNLP, and AAAI,
with total <a href='https://scholar.google.com/citations?user=Kmp8kVMAAAAJ'>google scholar citations </a> (<a href='https://scholar.google.com/citations?user=Kmp8kVMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


<div style="border-left: 4px solid #ccc; padding-left: 20px; margin: 20px 0; font-style: italic;">
  "With a Ph.D. you will have a better chance of spending the rest of your life doing what you want to do, instead of what someone else wants you to do."
  <div style="text-align: right; margin-top: 10px;">— William Lipscomb</div>
</div>

# 🔥 News
- *2025.4*: &nbsp;📢📢📢 Our new paper "Structural Entropy Guided Agent for Detecting and Repairing Knowledge Deficiencies in LLMs" is now available on arXiv!
- *2025.4*: &nbsp;🎉 Our paper "SetKE: Knowledge Editing for Knowledge Elements Overlap" has been accepted to IJCAI 2025!
- *2025.2*: &nbsp;🎉 Our paper "Towards Effective, Efficient and Unsupervised Social Event Detection in the Hyperbolic Space" has been accepted to AAAI 2025!
- *2024.09*: &nbsp;🎉🎉 Our paper "Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent" has been accepted to EMNLP 2024!
- *2024.07*: &nbsp;🎉🎉 Our paper "DAMe: Personalized Federated Social Event Detection with Dual Aggregation Mechanism" has been accepted to CIKM 2024!
- *2024.07*: &nbsp;🎉🎉 Our paper "Does Knowledge Localization Hold True? Surprising Differences Between Entity and Relation Perspectives in Language Models" has been accepted to CIKM 2024 (short paper)!
- *2024.05*: &nbsp;📢 Our paper "EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification" has been accepted to ACL 2024 Findings!
- *2023.10*: &nbsp;🎉 Our paper "MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models" has been accepted to EMNLP 2023 Findings!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/senator.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Structural Entropy Guided Agent for Detecting and Repairing Knowledge Deficiencies in LLMs](https://arxiv.org/abs/2505.07184)

**Yifan Wei**, Xiaoyan Yu, Tengfei Pang, Angsheng Li, Li Du

[[PDF]](https://arxiv.org/abs/2505.07184) [[ArXiv]](https://arxiv.org/abs/2505.07184) [[Code]](https://github.com/weiyifan1023/senator) 

we propose a novel Structural Entropy-guided Knowledge Navigator (SENATOR) framework that addresses the intrinsic knowledge deficiencies of LLMs.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/SetKE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SetKE: Knowledge Editing for Knowledge Elements Overlap](https://arxiv.org/abs/2504.20972)

**Yifan Wei**, Xiaoyan Yu, Ran Song, Angsheng Li

[[PDF]](https://arxiv.org/abs/2504.20972) [[ArXiv]](https://arxiv.org/abs/2504.20972) [[Code]](https://github.com/weiyifan1023/SetKE) 

we propose a new formulation, Knowledge Set Editing (KSE), and introduce SetKE, a method that edits sets of triplets simultaneously. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/HyperSED.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Effective, Efficient and Unsupervised Social Event Detection in the Hyperbolic Space](https://arxiv.org/abs/2412.10712)

Xiaoyan Yu, **Yifan Wei**, Shuaishuai Zhou, Liehuang Zhu, Philip S. Yu

[[PDF]](https://arxiv.org/pdf/2412.10712) [[ArXiv]](https://arxiv.org/abs/2412.10712) [[Code]](https://github.com/XiaoyanWork/HyperSED) 


We introduce HyperSED, an effective and efficient unsupervised framework for social event detection, which exploits the benefits of graph learning in the hyperbolic space and structural information to achieve event detection.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/neeko.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent](https://arxiv.org/abs/2402.13717)

Xiaoyan Yu, Tongxu Luo, **Yifan Wei** *, Fangyu Lei, Yiming Huang, Hao Peng, Liehuang Zhu

[[PDF]](https://arxiv.org/pdf/2402.13717) [[ArXiv]](https://arxiv.org/abs/2402.13717) [[Code]](https://github.com/weiyifan1023/Neeko) 


We present Neeko, an innovative framework designed for efficient multiple characters imitation. Unlike existing methods, Neeko employs a dynamic low-rank adapter (LoRA) strategy, enabling it to adapt seamlessly to diverse characters. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/dame.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DAMe: Personalized Federated Social Event Detection with Dual Aggregation Mechanism](https://arxiv.org/pdf/2409.00617)

Xiaoyan Yu, **Yifan Wei**, Pu Li, Shuaishuai Zhou, Hao Peng, Li Sun, Liehuang Zhu, Philip S Yu

[[ArXiv]](https://arxiv.org/abs/2409.00614) [[Code]](https://github.com/XiaoyanWork/DAMe) 

This paper proposes a personalized federated learning framework with a dual aggregation mechanism for social event detection, namely DAMe. 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/rake.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Does Knowledge Localization Hold True? Surprising Differences Between Entity and Relation Perspectives in Language Models](https://arxiv.org/pdf/2409.00617)

**Yifan Wei**, Xiaoyan Yu, Yixuan Weng, Huanhuan Ma, Yuanzhe Zhang, Jun Zhao, Kang Liu

[[ArXiv]](https://arxiv.org/pdf/2409.00617) [[Code]](https://github.com/weiyifan1023/RaKE) 

This study investigates the differences between entity and relational knowledge through knowledge editing. Our findings reveal that entity and relational knowledge cannot be directly transferred or mapped to each other.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/exfever.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification](https://arxiv.org/pdf/2310.09754)

Huanhuan Ma, Weizhi Xu, **Yifan Wei**, Liuji Chen, Liang Wang, Qiang Liu, Shu Wu, Liang Wang

[[ArXiv]](https://arxiv.org/pdf/2310.09754) [[Code]](https://github.com/dependentsign/EX-FEVER)

We introduce a large scale Multi-hop fact checking dataset with textual explanations, which can be used to evaluate the explainability of fact verification models.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/menatqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models](https://aclanthology.org/2023.findings-emnlp.100/)<strong><span class='show_paper_citations' data='Kmp8kVMAAAAJ:LkGwnXOMwfcC'></span></strong>

**Yifan Wei**, Yisong Su, Huanhuan Ma, Xiaoyan Yu, Fangyu Lei, Yuanzhe Zhang, Jun Zhao, Kang Liu

[[PDF]](https://aclanthology.org/2023.findings-emnlp.100.pdf) [[ArXiv]](https://arxiv.org/pdf/2310.05157) [[Code]](https://github.com/weiyifan1023/MenatQA) 

**Findings of the Association for Computational Linguistics: EMNLP 2023**

We construct Multiple Sensitive Factors Time QA (MenatQA), which encompasses three temporal factors (scope factor, order factor, counterfactual factor) with total 2,853 samples for evaluating the time comprehension and reasoning abilities of LLMs.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/rake.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Assessing knowledge editing in language models via relation perspective](https://arxiv.org/abs/2311.09053)

**Yifan Wei**, Xiaoyan Yu, Huanhuan Ma, Fangyu Lei, Yixuan Weng, Ran Song, Kang Liu

[[PDF]](https://arxiv.org/pdf/2311.09053) [[ArXiv]](https://arxiv.org/pdf/2311.09053) [[Code]](https://github.com/weiyifan1023/RaKE) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2023</div><img src='images/s3hqa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[S3HQA: A Three-Stage Approach for Multi-hop Text-Table Hybrid Question Answering](https://aclanthology.org/2023.acl-short.147/)

Fangyu Lei, Xiang Li, **Yifan Wei**, Shizhu He, Yiming Huang, Jun Zhao, Kang Liu

**Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics**

[[PDF]](https://aclanthology.org/2023.acl-short.147.pdf)  [[Code]](https://github.com/lfy79001/S3HQA)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/mvge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-View Graph Representation Learning for Answering Hybrid Numerical Reasoning Questions](https://arxiv.org/abs/2305.03458)

**Yifan Wei**, Fangyu Lei, Yuanzhe Zhang, Jun Zhao, Kang Liu


[[PDF]](https://arxiv.org/pdf/2305.03458)  [[ArXiv]](https://arxiv.org/abs/2305.03458) [[Code]](https://github.com/weiyifan1023/MVGE)

</div>
</div>


# 🚀 Projects

- [Neeko](https://github.com/weiyifan1023/Neeko): Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent. ![GitHub stars](https://img.shields.io/github/stars/weiyifan1023/Neeko?style=social)
- [TableQAKit](https://github.com/lfy79001/TableQAKit): A Toolkit for Table-based Question Answering. ![GitHub stars](https://img.shields.io/github/stars/lfy79001/TableQAKit?style=social)


# 📖 Educations
- *2021.09 - 2024.07*, M.S. in Artificial Intelligence, Institute of Automation, Chinese Academy of Sciences. Advisors: Prof. Kang Liu and Prof. Jun Zhao.

- 2024.09 - , Ph.D. candidate at the School of Computer Science and Engineering, Beihang University.
   
# 💻 Internships
- *2023 - 2024*,   [NOETIX](https://noetixrobotics.com/)
- *2024 - 2025*,   [BAAI](https://www.baai.ac.cn/)

# 📅 Academic Services

## 📖 Reviewers
- Annual Meeting of the Association for Computational Linguistics (ACL,EMNLP,NAACL), Reviewer
- Annual Conference on Neural Information Processing Systems (NeurIPS), Reviewer
- ACM International Conference on Information and Knowledge Management (CIKM), PC member
- International Joint Conference on Artificial Intelligence (IJCAI), PC member
- The Association for the Advancement of Artificial Intelligence (AAAI), PC member
