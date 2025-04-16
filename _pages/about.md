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

# Projects
- ExplainableBI：基于人机协同的NL2BI可信增强方案（CCF-A会议论文，在投）	-	第一作者 2025年01月-2025年04月
  - 项目职责：文献调研；用户访谈（需求调研）；使用Figma进行系统原型设计；使用Langchain、Vue、element-plus、Axios、FastAPI、
  RAG、In-context	learning（ICT）、CoT等技术实现基于text-to-sql的具有可解释功能的LLM-based	BI应用；用户体验设计；用户实
  验。

- LLM4VA：基于Multi-Agent的可视化分析系统原型设计（CCF-A会议论文，在投）	-	第三作者 2025年01月-2025年04月
  - 项目背景：该项目旨在利用LLM构建5个智能体，分别为data	analyst、domain	expert、searcher、designer、coder，每个智能体模拟可视
  化分析人员在完成每个可视化分析系统的步骤，从而帮助可视化分析人员设计并实现一个可视化分析系统的原型。
  - 项目职责：利用BeautifulSoup、requests爬取可视化分析领域的学术论文；利用Langchain实现designer和coder两个Agent，designer负责
  得出设计目标和每个可视化视图的内容和位置，coder基于vue3框架和d3.js生成每个视图的可视化分析代码。

- Danmaku	Avatar：基于弹幕实现VR中的虚拟共同观看者（CCF-A，已收录）	-	第一作者 2024年06月-2024年09月
  - 项目职责：文献调研；用户访谈（需求分析）；设计研讨会；使用request进行数据爬取；python数据处理和分析；使用Bert和ERNIE
  进行预训练、文本分类、情感识别；使用Character	Creator	4设计虚拟人形象、骨骼绑定；文本转语音；使用Unity构建虚拟场景并实现
  与虚拟人进行共同观看视频，文本转语音，利用LLM实现实时语音、动作、眼神交互;	用户体验设计；用户实验，EEG信号分析。

- DIVAS驾驶行为可视化分析系统（ChainVis2023	数据可视化挑战赛	三等奖）	-	第二作者 2023年04月-2024年06月
  - 项目职责：使用Python处理和分析车辆驾驶数据得到车辆加速、减速、刹车，车辆变道，车辆占道、人车距离、车辆停车线减速、车
  辆间距等结果；利用TSNE、DBSCAN进行驾驶行为的降维和聚类；利用jsonVee、d3.js可视化这里数据追踪每位驾驶人的车辆行驶路
  径和行为。

- 基于收购事件的人才流动对创新能力影响的可视化分析系统（CCF-A，在投）	-	第三作者 2023年07月-2023年09月
  - 项目职责：对AI领域的专利和论文以及收购事件的数据进行python数据处理、数据分析；利用机器学习算法TSNE、Kmeans、Shape进
  行数据降维、聚类、评估；使用vue、d3.js	实现可视化视图。

- 医疗大数据分析平台	-	第一作者 2021年12月-2022年03月
  - 项目职责：利用SpringBoot、mybatis、echarts、Spark、Spark	SQL、Hive处理和分析全国各医院数据、在线诊疗医师数据、在售各类药
  品数据、各类药房数据数据，将分析结构制作了10个可视化分析大屏。