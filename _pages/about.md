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

I am a second-year Ph.D. student at [University of California, Los Angeles](https://www.ucla.edu/)'s Department of Computer Science, fortunate to be advised by [Professor Wei Wang](http://web.cs.ucla.edu/~weiwang/).

Prior to that, I obtained my Computer Science bachelor's degree from Tsinghua University, fortunate to be advised by [Prof. Jie Tang](https://keg.cs.tsinghua.edu.cn/jietang/).


My research interest includes machine learning with biology and natural language processing.

- Derive complex, information-rich properties (e.g., structural characteristics) from primary properties [*first principle*].
- Model molecular interactions (protein, ligand, DNA) to make drug discovery more *targeted*.
- Bridge biological data with user-friendly data modalities (texts, images) using *large language models (LLMs)*.

<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

<!-- 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 Started the internship at Amazon Web Service.


# 📝 Publications 
<!-- CPPLM Card -->
<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">EMNLP 2024 Main</div>
            <img src='images/CPPLM.png' alt="CPPLM" width="100%">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
        <a href="https://arxiv.org/abs/2310.02469">Large Language Models Can Be Contextual Privacy Protection Learners</a>
        <p><strong>Yijia Xiao, Yiqiao Jin, Yushi Bai, Yue Wu, Xianjun Yang, Xiao Luo, Wenchao Yu, Xujiang Zhao, Yanchi Liu, Haifeng Chen, Wei Wang, Wei Cheng</strong></p>
        <p><strong>Abstract:</strong> We introduce CPPLM (Contextual Privacy Protection Fine-Tuning for LLM), which emphasizes instruction-based tuning with positive and negative examples, enabling LLMs to capture knowledge while preserving privacy.</p>
    </div>
</div>

<!-- RNA-GPT Card -->
<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">MLSB, Neurips 2024</div>
            <img src='images/RNA-GPT.png' alt="RNA-GPT" width="100%">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
        <a href="https://rna-gpt.github.io/">RNA-GPT: Multimodal Generative System for RNA Sequence Understanding</a>
        <p><strong>Yijia Xiao, Edward Sun, Yiqiao Jin, Wei Wang</strong></p>
        <p><strong>Abstract:</strong> RNA-GPT combines RNA sequence encoders with state-of-the-art LLMs for precise representation alignment, streamlining RNA research by providing accurate responses to RNA queries.</p>
    </div>
</div>

<!-- LogicVista Card -->
<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">Research Benchmark</div>
            <img src='images/LogicVista.png' alt="LogicVista" width="100%">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
        <a href="https://arxiv.org/abs/2407.04973/">LogicVista: Multimodal LLM Logical Reasoning Benchmark in Visual Contexts</a>
        <p><strong>Yijia Xiao, Edward Sun, Tianyu Liu, Wei Wang</strong></p>
        <p><strong>Abstract:</strong> LogicVista is an evaluation benchmark designed to assess logical reasoning capabilities of MLLMs in visual contexts, encompassing multiple logical reasoning tasks and capabilities.</p>
    </div>
</div>

<!-- ProteinGPT Card -->
<div class='paper-box'>
    <div class='paper-box-image'>
        <div>
            <div class="badge">ArXiv Preprint</div>
            <img src='images/ProteinGPT.png' alt="ProteinGPT" width="100%">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
        <a href="https://arxiv.org/abs/2408.11363">ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding</a>
        <p><strong>Yijia Xiao, Edward Sun, Yiqiao Jin, Qifan Wang, Wei Wang</strong></p>
        <p><strong>Abstract:</strong> ProteinGPT enables comprehensive protein analysis by allowing users to upload sequences and structures, providing contextually relevant responses to streamline protein research. Huggingface Demonstraction: https://huggingface.co/spaces/AI-BIO/ProteinGPT-Llama3.</p>
    </div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pretrain@KDD 2021</div><img src='images/ProteinLLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling protein using large-scale pretrain language model](https://arxiv.org/abs/2108.07435)

**Yijia Xiao**, Jiezhong Qiu, Ziang Li, Chang-Yu Hsieh, Jie Tang

**Abstract**: Introducing ProteinLM, a suite of large-scale protein language models comprising 3 billion parameters. ProteinLM enhances contact prediction accuracy from 36% to 75%, showcasing its efficiency in capturing evolutionary data. Our resources are accessible to the public at https://github.com/THUDM/ProteinLM.

<a href="https://en.wikipedia.org/wiki/Wu_Dao">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b3/Wikipedia-logo-v2-en.svg" alt="Wikipedia" style="vertical-align:middle; height:1.2em; margin-right:5px;">
  [Wikipedia: Wen Su]
</a>


</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2023</div><img src='images/examiner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Benchmarking foundation models with language-model-as-an-examiner](https://arxiv.org/abs/2108.07435)

Yushi Bai, Jiahao Ying, Yixin Cao, Xin Lv, Yuze He, Xiaozhi Wang, Jifan Yu, Kaisheng Zeng, **Yijia Xiao**, Haozhe Lyu, Jiayin Zhang, Juanzi Li, Lei Hou

**Abstract**: We propose Language-Model-as-an-Examiner, a novel benchmarking method that utilizes an LM as a knowledgeable examiner to construct dataset and evaluate other models.
</div>
</div>


<!-- 
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->





# 🎖 Honors and Awards
- *2021* Research Excellence Scholarship (*Top 2%, 3 / 230*), Tsinghua University.
- *2020* Silver Medal, ICPC Asia East Continent Final.
- *2020* Gold Medal, ICPC Asia Regional Contest.
- *2019* First Prize, Chinese Collegiate Physics Olympiad.
- *2017* National Bronze, Chinese Physics Olympiad.


# 📖 Educations
- **Ph.D. Student, Computer Science**, *2022 - Now*  
  - University of California, Los Angeles
  - Advisor: [Professor Wei Wang](http://web.cs.ucla.edu/~weiwang/)

- **Bachelor, Computer Science and Technology**, *2018 - 2022*
  - Tsinghua University
  - Advisor: [Professor Jie Tang](https://keg.cs.tsinghua.edu.cn/jietang/)

<!-- 
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->

# 💬 Invited Talks
- *2024*, Delivered a report on the application of machine learning in biomedical scenarios at [dknet](https://dknet.org/).
- *2022*, Delivered a talk on efficient pre-training of large-scale protein language models at [BioMap](https://www.biomap.com/).
- *2021*, Delivered a talk on the progress and applications of pre-trained protein models to AI start-ups at Beijing Academy of Artificial Intelligence.

<!-- 
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->


# 💻 Internships
- *2024.06 - Now*, [AWS](https://aws.amazon.com/entity-resolution/), Seattle.
- *2023.06 - 2023.09*, [NEC Labs America](https://www.nec-labs.com/), Princeton.


<p align="center">
<a href='https://clustrmaps.com/site/1bl9j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=a&t=tt&d=kI-i930V6akQPyUWlqEbKYEq76tgAxp4CdYHMgd9f4s'/></a>
</p>
