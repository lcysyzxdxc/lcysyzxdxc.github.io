---
permalink: /
title: "Chunyi Li's homepage"
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

(This page is under modification.)

I'm Chunyi Li(李春一), a joint Ph.D. candidate at the Shanghai Jiao Tong University and Nanyang Technological University, supervised by Prof. [Wenjun Zhang](https://icisee.sjtu.edu.cn/jiaoshiml/zhangwenjun.html) (中国工程院院士, IEEE Fellow), Prof. [Guangtao Zhai](https://icisee.sjtu.edu.cn/jiaoshiml/zhaiguangtao.html) (IEEE Fellow), and Prof. [Weisi Lin](https://personal.ntu.edu.sg/wslin/Home.html) (IEEE Fellow). Prior to this, I was a research intern at the National University of Singapore supervised by Prof [Roger Zimmermann](https://www.comp.nus.edu.sg/cs/people/rogerz/) (ACM Distinguished Scientist).

Our research team at the Center of AI ​​Evaluation, Shanghai Artificial Intelligence Laboratory, publishes benchmark lists related to Embodied AI and participates in the development of Chinese national standards. See our project homepage: [OpenCompass](https://opencompass.org.cn/embodied-intelligence) and [AIBench](https://aiben.ch/).

My research interests cover multimodal signal processing, including Generative AI and Embodied AI, and their low-level downstream application. I'm a regular reviewer for journals: TPAMI/JSAC/TIP/TMM/TCSVT/TNNLS/TOMM, and conferences: CVPR/ICCV/NIPS/ICLR/ACMMM/ICME, etc.

See my top Repos:
- 🥇[AIGC Quality Evaluation](https://github.com/lcysyzxdxc/AGIQA-3k-Database): a comprehensive fine-grained AI-Generated Content (AIGC) subjective quality assessment database. (200+ citations)
- 🧰[Embodied AI Evaluation](https://github.com/lcysyzxdxc/MPD): the first subjective evaluation paradigm from human to machine. (CVPR Ratings: 555)

📫 Reach me by e-mail: lcysyzxdxc@sjtu.edu.cn, lich0076@e.ntu.edu.sg

# 🔥 News
- *2025.07*: &nbsp;🎉🎉 I'm honored to receive the Membership Funding Program by the Chinese Institute of Electronics!

<!--

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TCSVT 2023</div><img src='images/TCSVT2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AGIQA-3K: An Open Database for AI-Generated Image Quality Assessment](https://arxiv.org/pdf/2306.04717.pdf)

**Chunyi Li**, Zicheng Zhang, Haoning Wu, Wei Sun, Xiongkuo Min, Xiaohong Liu, Guangtao Zhai, and Weisi Lin

[**Project**](https://github.com/lcysyzxdxc/AGIQA-3k-Database) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A fine-grained AI-Generated Image (AGI) subjective quality assessment database considering various popular AGI models. Generating AGI through different prompts and model parameters, with subjective data in both perceptual quality and text-to-image alignment levels.

[**Project**](https://github.com/lcysyzxdxc/AGIQA-1k-Database) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The first AI-Generated Image (AGI) subjective quality assessment database, with subjective perceptual quality data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE ICME 2023</div><img src='images/ICME2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[A Real-Time Blind Quality-of-Experience Assessment Metric for HTTP Adaptive Streaming](https://arxiv.org/pdf/2303.09818.pdf)

**Chunyi Li**, May Lim, Abdelhak Bentaleb, and Roger Zimmermann

[**Project**](https://github.com/lcysyzxdxc/ASPECT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A QoE model for streaming video that realizes high consistency, low latency, and blind assessment together.
</div>
</div>


The Full Publication list is on [Google Scholar](https://scholar.google.com/citations?user=WosRriMAAAAJ).

# 🎖 Honors and Awards
- *2023.06* **Outstanding Bachelor Thesis** of SJTU (1/200+).
- *2023.06* Outstanding Bachelor Graduate Student of SJTU.

- *2022.08* National University Internet of Things (IoT) Designing Competition, **HarmonyOS Grand Prize & National First Prize** (10/1400+).
- *2021.02* The Mathematical Contest in Modeling, Meritorious Winner.
- *2020.12* National College Mathematical Competition in Shanghai, First Prize.
- *2020.11 - 2023.04* ZhangXu Fellowship (10k CNY), ZhanJiaJun Scholarship (15k CNY), Panasonic Scholarship (5k CNY), Huawei Scholarship (4k CNY), B-level Scholarship (1k CNY), Merit Student.

- *2018.09* National High School Mathematical League in Beijing, First Prize.

# 📖 Educations
- *2023.09 - now*, Ph.D. Student, [Cooperative Media-net Innovation Center](https://cmic.sjtu.edu.cn/), Shanghai Jiao Tong University, supervised by Prof. Guangtao Zhai.
- *2022.07 - 2022.12*, Research Intern, [Institute of Data Science](https://ids.nus.edu.sg/), National University of Singapore, supervised by Prof. Roger Zimmermann.
- *2019.09 - 2023.06*, Undergraduate Student, Shanghai Jiao Tong University.
- *2013.09 - 2019.06*, High School Student, The Experimental High School Attached to Beijing Normal University.



# 💬 Invited Talks
- *2025.06*, Invited Speaker, Advanced Signal Processing Theory and Methods. Outstanding Doctoral Student Forum, Chinese Institute of Electronics, Hangzhou.
- *2025.06*, Panel Speaker, Reconstruction and Generation of Large Scenes. Vision and Learning Seminar(VALSE), Chinese Society of Image and Graphics, Zhuhai.
- *2025.05*, Invited Speaker, Perceptual Quality Assessment for Embodied AI. Outstanding Doctoral Student Forum, Chinese Society of Image and Graphics, Online.
- *2025.05*, Invited Speaker, Image Quality Assessment for Machine Preference. Chinese Congress on Image and Graphics, Chinese Society of Image and Graphics, Changsha.
- *2024.04*, Invited Speaker, Cooperative Evolution of Video Coding and Generative AI. College of Computing and Data Science Technical Seminar, Nanyang Technological University, Singapore.

# 💻 Internships
- *2023.07 - now*, [Shanghai AI Lab](https://www.shlab.org.cn/), China.

-->
