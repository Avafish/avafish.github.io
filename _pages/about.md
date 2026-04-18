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

Welcome to Zewen Long's Personal Homepage!

Currently, I am an Algorithm Engineer in Didi Chuxing, Beijing, responsible for the design and optimization of popup recommendation models. I graduated from the [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn/) in June 2025 as a member at [Center for Research on Intelligent Perception and Computing (CRIPAC)](http://cripac.ia.ac.cn/en/EN/volumn/home.shtml), National Laboratory of Pattern Recognition (NLPR). I am fortunate to be advised by Professor [Shu Wu](https://people.ucas.ac.cn/~shuwu?language=en).

My research interests lie in the field of Recommender Systems, with a focus on modeling user preferences. Currently, I am highly intrigued by exploring the intersection of Large Language Models (LLMs) and Trustworthy AI.

# 🔥 News
- *2026.04*: &nbsp;🎉 Our paper "When Safety Alignment Fails to Generalize: Probing with Language Game Jailbreaks" has been accepted by the Findings of ACL 2026!
- *2026.01*: &nbsp;🎉 Our paper "Graph of Thoughts Signal Modeling for Sequential Recommendation" has been accepted by ICASSP 2026!
- *2023.08*: &nbsp;🎉 Our paper "Personalized Interest Sustainability Modeling for Sequential POI Recommendation" has been accepted by CIKM 2023!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/iclr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

When Safety Alignment Fails to Generalize: Probing with Language Game Jailbreaks

**Zewen Long<sup>\*</sup>**, Yu Peng<sup>\*</sup>, Fangming Dong, Congyi Li, Xingmao Guan, Shu Wu, Kai Chen

**Accepted by The Findings of the Association for Computational Linguistics: ACL 2026**

We discover a novel jailbreak attack method to exploit large language models (LLMs) by playing custom-designed language games. This method circumvents LLM safety alignments, showcasing the vulnerability of current safety protocols.

[[PDF]](pdfs/Jailbreak.pdf) [[Code]](https://anonymous.4open.science/r/lgjail)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026</div><img src='images/aaai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Graph of Thoughts Signal Modeling for Sequential Recommendation

**Zewen Long**, Liang Wang, Shu Wu, Qiang Liu, Liang Wang

**Accepted by The 2026 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2026).**

We propose the GOT4Rec model, which first utilizes the graph of thoughts (GoT) prompting strategy in the sequential recommendation domain to capture three key types of information contained within user history sequences: short-term interests, long-term interests and collaborative information from other users.

[[PDF]](pdfs/GOT4Rec.pdf) [[Code]](https://anonymous.4open.science/r/GOT4Rec)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2023</div><img src='images/cikm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Personalized Interest Sustainability Modeling for Sequential POI Recommendation](https://dl.acm.org/doi/abs/10.1145/3583780.3615278)

**Zewen Long<sup>\*</sup>**, Liang Wang<sup>\*</sup>, Qiang Liu, Shu Wu

**Accepted by The 32nd ACM International Conference on Information and Knowledge Management (CIKM 2023).**

We propose a personalized interest sustainability model for sequential POI recommendation (INSPIRE) to capture whether each user's interest in specific POIs will sustain beyond the training time, aiding in more accurate and sustainable recommendations.

[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3583780.3615278)

</div>
</div>



# 📖 Educations
- *2022.09 - 2025.06*, M.S. in Computer Application Technology, Institute of Automation, Chinese Academy of Sciences. Advisor: Prof. Shu Wu.

- *2018.09 - 2022.06*, B.E. in School of Cyber Security, University of Chinese Academy of Sciences. 

# 📅 Academic Services
- ACM Transactions on Recommender Systems, Reviewer
- The Thirteenth International Conference on Learning Representations (ICLR 2025), Reviewer
- The 40th Annual AAAI Conference on Artificial Intelligence (AAAI 2026), Reviewer
- The Fourteenth International Conference on Learning Representations (ICLR 2026), Reviewer

# 📋 CV
[[PDF]](pdfs/Resume.pdf)