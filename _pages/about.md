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

I am a second-year master student from [School of Information Science and Technology](https://sist.shanghaitech.edu.cn/), [Shanghaitech University](https://www.shanghaitech.edu.cn/) supervised by [Prof. Quan Li](https://faculty.sist.shanghaitech.edu.cn/liquan/). My research focuses on human-computer interaction (HCI) and data visualization (VIS), with a recent emphasis on leveraging Large Language Models (LLMs) to enhance interactive systems. I explore how LLMs can be integrated into user interfaces to create more intuitive and responsive experiences, aiming to bridge the gap between complex data and user-friendly interactions.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG</div><img src='images/CHI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Danmaku Avatar: Enabling Asynchronous Co-viewing Experiences in Virtual Reality via Danmaku

**Xiaofeng Dou**, Jiahe Dong, Shuhao Zhang, Qian Zhu, Quan Li

This study introduces the Danmaku Avatar system, designed to bring the popular danmaku comment experience to virtual reality (VR). By adapting danmaku for VR, our system enhances asynchronous co-viewing, boosting social presence and encouraging communication. These findings pave the way for improved virtual social interactions and immersive viewing experiences.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG</div><img src='images/TVCG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Requirement to Solution: Unveiling Problem-Driven Design Patterns in Visual Analytics

Yuchen Wu, Shenghan Gao, Shizhen Zhang, **Xiaofeng Dou**, Xingbo Wang, Quan Li

<span>
  <a href="https://ieeexplore.ieee.org/abstract/document/10874217">PDF</a>
  <a href="https://upddp.github.io/">Website</a>
  <strong><span class='show_paper_citations' data='AB_U2BoAAAAJ:d1gkVwhDpl0C'></span></strong>
</span>
<div>
This study identified computational features, formulated design requirements, and developed LiveRetro , an interactive visual analytics system. It enables comprehensive retrospective analysis of livestream e-commerce for streamers, viewers, and merchandise. LiveRetro employs enhanced visualization and time-series forecasting models to align performance features and feedback, identifying influences at channel, merchandise, feature, and segment levels.
</div>
</div>
</div>

# 🎖 Honors and Awards
- *ChinaVis	2023	中国可视化与可视分析大会*	“数字中国”数据可视化竞赛	三等奖 2023.07
- *ACM-ICPC	2020中国大学生程序设计竞赛（西部）*	铜牌  2020.11
- *第十五届全国大学生计算机设计大赛人工智能实践赛*	省赛三等奖 2022.05
- *第十四届全国大学生计算机设计大赛算法设计组*	国赛三等奖 2021.07
- *第十一届蓝桥杯全国软件和信息技术专业人才大赛*	国赛三等奖 2020.11
- *第四届中国虚拟现实大赛*	国赛三等奖 2021.10
- *第十二届“挑战杯”全区大学生课外学术科技作品竞赛*	省赛银奖 2021.06
- *华北五省（市、自治区）及港澳台大学生计算机应用大赛*	大区三等奖 2021.11
 

# 📖 Educations
- *2023.09 - present*, Master Student, Shanghaitech University, Shanghai 
- *2019.09 - 2023.06*, Undergraduate, Inner Mongolia University of Science and Technology, Inner Mongolia

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *安德阿镆贸易（上海）有限公司*	-	大模型应用实习生	IT 2024.12 - 2025.04
  1.	ChatBI项目开发和测试：构建企业知识库，使用Python和Ollama接入LLM（大语言模型），使得LLM能够基于文本生成SQL代码并
  得到BI结果。编写SQL代码测试LLM的输出结果是否与编写的SQL代码查询一致。在此过程中，基于LLM驱动的BI系统目前面临的挑
  战，提出并实现了ExplainableBI，并已提交至CCF-A类会议。
  2.	神秘访客Agent：利用LLM构建训练销售的虚拟顾客。参与用户需求调研、工作流构建、产品知识库构建，测试agent表现行为。
- *上海信投数字科技有限公司*	数据实习生 2024.09 - 2024.12
  1. 利用LLM实现医疗问诊小助手，利用Bert对问题进行分类，利用RAG、CoT、Langchain微调医疗大模型。
  2.	参与医疗大健康项目，使用ETL工具（Kettle）对分散在各个社区、二三甲医院的数据转换整理到大数据库中。
  3.	竞品分析，PRD文档编写，使用Azure进行系统设计。