---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
I am currently working as an NLP Algorithm Engineer at Xiaohongshu (小红书) in the NLP Group, focusing on large language model applications and AI Agent systems. I obtained my Master degree in MSc Advanced Computing from [Imperial College London](https://www.imperial.ac.uk/) in 2019, supervised by [Dr Anandha Gopalan](https://www.imperial.ac.uk/people/a.gopalan). Before that, I received B.E. degree of Software Engineering from [Wuhan University of Technology](http://english.whut.edu.cn/) in 2018 under the supervision of [Prof. Luo Zhong](http://cst.whut.edu.cn/xygk/szdw/201505/t20150527_168516.htm).

I previously worked as a Machine Learning Engineer at [Trip.com](https://www.trip.com/pages/about-us) in the Semantic Application Group, lead by Jianxun Ju. Before that, I worked as an Applied Scientist Intern supervised by [Dr Xingjian Shi](https://sxjscience.github.io) in [Amazon Web Services (AWS)'s AI Lab](https://github.com/awslabs) Shanghai in the group of GluonNLP lead by [Dr. Mu Li](http://www.cs.cmu.edu/~muli/) and [Dr. Alex Smola](https://alex.smola.org/). I am also a member of [DMLC](https://github.com/dmlc), constantly contributing to the open-source community of deep learning.

My research interests lie in Natural Language Processing, particularly in Large Language Models, AI Agents, Model Compression, and Multimodal Reasoning.

## Recent Highlights

**Nov 2025.** One dataset paper accepted to **EMNLP 2025 Dataset Track** (RedOne: Revealing Domain-specific LLM Post-Training in Social Networking Services).

**July 2025.** One paper accepted to **ACL 2025 Demo** (iPET: An Interactive Emotional Companion Dialogue System).

**June 2025.** One paper received **ACL 2025 Outstanding Paper Award** (Towards the Law of Capacity Gap in Distilling Language Models).

**April 2025.** One paper accepted to **SIGIR 2025 Industry Track** (PaRT: Enhancing Proactive Social Chatbots with Personalized Real-Time Retrieval).

## Experiences

<ul class="timeline">
	<li>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">小红书</span>
				<span class="time-wrapper"><span class="time">2021.12 - 至今</span></span>
			</div>
			<div class="desc">NLP算法工程师，应用算法部</div>
		</div>
	</li>
	<li>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">携程旅行网</span>
				<span class="time-wrapper"><span class="time">2020.08 - 2021.11</span></span>
			</div>
			<div class="desc">Machine Learning Engineer in Semantic Application Group, lead by Jianxun Ju</div>
		</div>
	</li>
	<li>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">AWS AI Lab</span>
				<span class="time-wrapper"><span class="time">2019.11 - 2020.08</span></span>
			</div>
			<div class="desc">Applied Scientist Intern，GluonNLP Group</div>
		</div>
	</li>
	<li>
		<div class="direction-l">
			<div class="flag-wrapper">
				<span class="flag">帝国理工学院</span>
				<span class="time-wrapper"><span class="time">2018.09 - 2019.11</span></span>
			</div>
			<div class="desc">MSc Advanced Computing</div>
		</div>
	</li>
	<li>
		<div class="direction-r">
			<div class="flag-wrapper">
				<span class="flag">武汉理工大学</span>
				<span class="time-wrapper"><span class="time">2014.09 - 2018.06</span></span>
			</div>
			<div class="desc">软件工程，本科</div>
		</div>
	</li>
</ul>

<!-- ## Projects

***RedOne大模型应用落地*** <br>
构建统一评估与后训练框架（SFT / DPO / GRPO），应用于搜索推词、翻译、商品生成、query预测等场景。设计并实现基于LLM Reasoning的笔记推词系统，采用CoT SFT + RLVR两阶段训练策略，构建8B近线、0.6B在线的一体化LLM模式。 <br>
*小红书，2024.12 - 至今*

***AI Agent创新应用-从0到1建设*** <br>
设计复杂记忆系统、多路召回检索、世界模拟和对话联网等功能。搭建了业界首个落地的"斯坦福小镇"，支持对话与记忆因子推演，生成虚拟世界生活行程。项目获**小红书2024年度最佳项目（用户突破）**。 <br>
*小红书，2023.04 - 2025.02* [[AI群聊]](https://raw.githubusercontent.com/zheyuye/zheyuye.github.io/refs/heads/master/images/202403292242282.jpg) [[AI宠物]](https://raw.githubusercontent.com/zheyuye/zheyuye.github.io/refs/heads/master/images/202403292242362.jpg) [[AI助手]](https://raw.githubusercontent.com/zheyuye/zheyuye.github.io/refs/heads/master/images/202403292242429.jpg) -->

## Publications & Manuscripts [<img src="./assets/imgs/google.ico" width="22" height="22" alt="google" align=center/>](https://scholar.google.com/citations?user=1_AmlNsAAAAJ)
\# indicates equal contributions.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

