---
title: "SPLDExtraTrees: Robust machine learning approach for predicting kinase inhibitor resistance"
collection: publications
permalink: /publication/2020-11-SPLDExtraTrees-Drug
excerpt: 'We proposed a robust machine learning method for predicting ligand binding affinity changes upon protein mutations for cancer target Abl kinase and identifying resistant mutations.'
date: 2020-11-15
venue: 'Ziyi Yang, Zhaofeng Ye, <b>Yijia Xiao</b>, Chang-Yu Hsieh<br/>Briefings in Bioinformatics'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

<!-- 分子筛选是药物开发中重要的一环。通过湿实验筛选，是非常消耗人力和物资的，并且有较长的反馈周期。我们感兴趣的是，如何使用机器学习方法辅助筛选，找到那些最可能成为药物分子的候选分子，缩小待实验分子范围，更有针对性、更聪明的进行药物开发。 -->

Molecular screening is an important and indispensable part in drug development. Screening by wet experiments is costly and labor-intensive. Besides, wet experiments usually have a longer feedback circle. We are interested in how machine learning methods can be leveraged to assist in virtual screening to find those candidate molecules that are most likely to be serve treatment purposes. By narrowing down the number of molecules to be experimented on, we can make drug discovery more targeted and smarter.


<!--
蛋白质在生命活动中承担了众多重要的任务（运动、催化、运输、免疫等）。人类不少的疾病是由于蛋白质的异常工作造成的，比方氨基酸的插入、替换会使其结构、功能异常。最直接的例子是由于氨基酸替换引发的Sickle-cell disease。此外，酶的活性过低或过高也会影响人体的新陈代谢，引发间接疾病。因此，我们探究的是蛋白质序列中的突变，对蛋白-配体之间结合性的影响，找到靶向分子，在不影响正常蛋白（野生型）的前提下， 针对性作用在异常蛋白（突变型）上，达到靶向治疗的目的。

鉴于数据的特征，我们采用了extremely randomized trees，一种集成学习，并且获得了不错的效果，超过了包括rosetta ref15在内的baseline。此外，我们加入了Self paced learning来让模型更加鲁棒。
-->

Protein undertakes numerous important tasks in life (movement, catalysis, transport, immunity, etc.). A number of human diseases are caused by abnormalities in protein, for example, amino acid insertions and substitutions can cause abnormalities in their structure and function. In addition, low or high activity of enzymes can affect human metabolism and cause indirect diseases. Therefore, we investigate on the protein sequences's mutations effect on protein-ligand binding affinity. In this way, we can discover targeted molecules on the abnormal protein (mutant type), without affecting the normal protein (wild type).

Given the characteristics of the data, we adopted extremely randomized trees, a kind of ensemble learning, exceeding the baselines including ROSETTA's *REF15*. In addition, we applied self-paced learning to make the model more robust.


The paper is available [here](https://yijia-xiao.github.io/files/publications/SPLDExtraTrees_Robust_Machine_Learning_Approach_for_Predicting_Kinase_Inhibitor_Resistance.pdf).

Please [cite](https://arxiv.org/abs/2111.08008) our paper if you find this work helpful for your research.
