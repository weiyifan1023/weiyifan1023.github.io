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

I am a Ph.D. student at the [Beihang University](https://scse.buaa.edu.cn/), School of Computer Science and Engineering. 
I have spent wonderful time at [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/) as a master student, advised by Prof [Kan Liu](http://www.nlpr.ia.ac.cn/cip/~liukang/index.html).

My research interests lie in the field of natural language processing (NLP), with a focus on Large Language Models (LLMs), including Question Answering and Knowledge Editing. Currently, I am highly intrigued by exploring the intersection of LLMs and AI safety.



<div style="border-left: 4px solid #ccc; padding-left: 20px; margin: 20px 0; font-style: italic;">
  "With a Ph.D. you will have a better chance of spending the rest of your life doing what you want to do, instead of what someone else wants you to do."
  <div style="text-align: right; margin-top: 10px;">— William Lipscomb</div>
</div>

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Our paper "DAMe: Personalized Federated Social Event Detection with Dual Aggregation Mechanism" has been accepted to CIKM 2024!
- *2024.07*: &nbsp;🎉🎉 Our paper "Does Knowledge Localization Hold True? Surprising Differences Between Entity and Relation Perspectives in Language Models" has been accepted to CIKM 2024 (short paper)!
- *2024.05*: &nbsp;📢 Our paper "EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification" has been accepted to ACL 2024 Findings!
- *2023.10*: &nbsp;🎉 Our paper "MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models" has been accepted to EMNLP 2023 Findings!
- *2023.12*: &nbsp;🎉 Our paper "S3HQA: A Three-Stage Approach for Multi-hop Text-Table Hybrid Question Answering" has been accepted to ACL 2023 (short paper)!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/exfever.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EX-FEVER: A Dataset for Multi-hop Explainable Fact Verification](https://arxiv.org/pdf/2310.09754)

Huanhuan Ma, Weizhi Xu, **Yifan Wei**, Liuji Chen, Liang Wang, Qiang Liu, Shu Wu, Liang Wang

[[ArXiv]](https://arxiv.org/pdf/2310.09754) [[Code]](https://github.com/dependentsign/EX-FEVER)

We introduce a large scale Multi-hop fact checking dataset with textual explanations, which can be used to evaluate the explainability of fact verification models.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/neeko.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neeko: Leveraging Dynamic LoRA for Efficient Multi-Character Role-Playing Agent](https://arxiv.org/abs/2402.13717)

Xiaoyan Yu, Tongxu Luo, **Yifan Wei**, Fangyu Lei, Yiming Huang, Hao Peng, Liehuang Zhu

[[PDF]](https://arxiv.org/pdf/2402.13717) [[ArXiv]](https://arxiv.org/abs/2402.13717) [[Code]](https://github.com/weiyifan1023/Neeko) 


We present Neeko, an innovative framework designed for efficient multiple characters imitation. Unlike existing methods, Neeko employs a dynamic low-rank adapter (LoRA) strategy, enabling it to adapt seamlessly to diverse characters. 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023</div><img src='images/menatqa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MenatQA: A New Dataset for Testing the Temporal Comprehension and Reasoning Abilities of Large Language Models](https://aclanthology.org/2023.findings-emnlp.100/)

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


# 🚀 Projects

- [TableQAKit](https://github.com/lfy79001/TableQAKit): A Toolkit for Table-based Question Answering. ![GitHub stars](https://img.shields.io/github/stars/lfy79001/TableQAKit?style=social)

# 📖 Educations
- *2021.09 - 2024.07*, M.S. in Artificial Intelligence, Institute of Automation, Chinese Academy of Sciences. Advisors: Prof. Kang Liu and Prof. Jun Zhao.

- *2024.09 - *, Ph.D. at the School of Computer Science and Engineering, Beihang University.
   
# 💻 Internships


# 📅 Academic Services

## 📖 Reviewers
- Annual Meeting of the Association for Computational Linguistics 2023, 2024, Reviewer
- Annual Conference on Neural Information Processing Systems (NeurIPS) Dataset&Benchmark track 2023, Reviewer
- ACM International Conference on Information and Knowledge Management (CIKM) 2024, PC member
