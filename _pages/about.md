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

I am a third-year Ph.D. student at [University of California, Los Angeles](https://www.ucla.edu/)'s Department of Computer Science, advised by [Professor Wei Wang](http://web.cs.ucla.edu/~weiwang/).

Prior to that, I obtained my Computer Science bachelor's degree from Tsinghua University, advised by [Prof. Jie Tang](https://keg.cs.tsinghua.edu.cn/jietang/).


My research interest includes AI for Biology and LLM for Finance.

- Derive complex, information-rich properties (e.g., structural characteristics) from primary properties [*first principle*].
  - Bridge biological data with user-friendly data modalities (texts, images) using *large language models (LLMs)*.
- Derive high-level market structure characteristics by integrating information from various sources [*market liquidity*]
  - Utilize Multi LLM Agents to process, collaborate, decide, and deliver human-friendly content to finance practitioners.

For further details, please refer to my [Resume](https://yijia-xiao.com/images/YIJIA_XIAO-CV.pdf).

<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

<!-- 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Two Full papers and Two Workshops Papers accepted at AAAI.
- *2024.10*: &nbsp;🎉 One paper accepted at Neurips workshop.
- *2024.10*: &nbsp;🎉🎉 Three papers accepted at EMNLP.
- *2024.07*: &nbsp;🎉 Started the internship at Amazon Web Service.


# 📝 Publications

<!-- TradingAgents Card -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025, Multi-Agent AI in the Real World </div><img src='images/TradingAgents.png' alt="TradingAgents" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TradingAgents: Multi-Agents LLM Financial Trading Framework](https://tradingagents-ai.github.io/), **Oral Presentation**, [**Poster**](https://yijia-xiao.com/images/TradingAgents-Poster.pdf)

**Yijia Xiao**, Edward Sun, Di Luo, Wei Wang

**Abstract**: We present <strong>TradingAgents</strong>, a pioneering multi-agent LLM framework that revolutionizes autonomous trading by simulating professional trading firm dynamics. Our system orchestrates specialized agents—from analysts to risk managers—in a collaborative decision-making process, achieving up to 30.5% annualized returns, significantly outperforming traditional trading strategies while maintaining robust risk management.

<!-- **Abstract**: We introduce TradingAgents, a novel stock trading framework inspired by trading firms, utilizing multiple LLM-powered agents with specialized roles such as fundamental, sentiment, and technical analysts, as well as traders with diverse risk profiles. The system features Bull and Bear researchers evaluating market conditions, a risk management team overseeing exposure, and traders integrating insights from debates and historical data to make informed decisions. This collaborative, dynamic environment enhances trading performance, as demonstrated by our comprehensive experiments showing significant improvements in cumulative returns, Sharpe ratio, and maximum drawdown compared to baseline models. -->

</div></div>

<!-- ProteinGPT Card -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv Preprint</div><img src='images/ProteinGPT.png' alt="ProteinGPT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProteinGPT: Multimodal LLM for Protein Property Prediction and Structure Understanding](https://arxiv.org/abs/2408.11363), **Spotlight, MLGenX, ICLR 2025**, [**Poster**](https://yijia-xiao.com/assets/ProteinGPT.pdf)

**Yijia Xiao**, Edward Sun, Yiqiao Jin, Qifan Wang, Wei Wang

**Abstract**: ProteinGPT enables comprehensive protein analysis by allowing users to upload sequences and structures, providing contextually relevant responses to streamline protein research. 

Huggingface Demonstration: [https://huggingface.co/spaces/AI-BIO/ProteinGPT-Llama3](https://huggingface.co/spaces/AI-BIO/ProteinGPT-Llama3).

</div></div>

<!-- CPPLM Card -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024 Main</div><img src='images/CPPLM.png' alt="CPPLM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Large Language Models Can Be Contextual Privacy Protection Learners](https://arxiv.org/abs/2310.02469)

**Yijia Xiao**, Yiqiao Jin, Yushi Bai, Yue Wu, Xianjun Yang, Xiao Luo, Wenchao Yu, Xujiang Zhao, Yanchi Liu, Quanquan Gu, Haifeng Chen, Wei Wang, Wei Cheng

**Abstract**: We introduce CPPLM (Contextual Privacy Protection Fine-Tuning for LLM), which emphasizes instruction-based tuning with positive and negative examples, enabling LLMs to capture knowledge while preserving privacy.

</div></div>

<!-- RNA-GPT Card -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLSB, Neurips 2024</div><img src='images/RNA-GPT.png' alt="RNA-GPT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RNA-GPT: Multimodal Generative System for RNA Sequence Understanding](https://rna-gpt.github.io/)

**Yijia Xiao**, Edward Sun, Yiqiao Jin, Wei Wang

**Abstract**: RNA-GPT combines RNA sequence encoders with state-of-the-art LLMs for precise representation alignment, streamlining RNA research by providing accurate responses to RNA queries.

</div></div>

<!-- LogicVista Card -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Research Benchmark</div><img src='images/LogicVista.png' alt="LogicVista" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LogicVista: Multimodal LLM Logical Reasoning Benchmark in Visual Contexts](https://arxiv.org/abs/2407.04973/)

Yijia Xiao*, Edward Sun*, Tianyu Liu, Wei Wang

**Abstract**: LogicVista is an evaluation benchmark designed to assess logical reasoning capabilities of MLLMs in visual contexts, encompassing multiple logical reasoning tasks and capabilities.

</div></div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pretrain@KDD 2021</div><img src='images/ProteinLLM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling protein using large-scale pretrain language model](https://arxiv.org/abs/2108.07435)

**Yijia Xiao**, Jiezhong Qiu, Ziang Li, Chang-Yu Hsieh, Jie Tang

**Abstract**: Introducing ProteinLM, a suite of large-scale protein language models comprising 3 billion parameters. ProteinLM enhances contact prediction accuracy from 36% to 75%, showcasing its efficiency in capturing evolutionary data. Our resources are accessible to the public at https://github.com/THUDM/ProteinLM.

<a href="https://en.wikipedia.org/wiki/Wu_Dao">
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b3/Wikipedia-logo-v2-en.svg" alt="Wikipedia" style="vertical-align:middle; height:1.2em; margin-right:5px;">
  [Wikipedia: Wen Su]
</a>

</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurips 2023</div><img src='images/examiner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Benchmarking foundation models with language-model-as-an-examiner](https://arxiv.org/abs/2108.07435)

Yushi Bai, Jiahao Ying, Yixin Cao, Xin Lv, Yuze He, Xiaozhi Wang, Jifan Yu, Kaisheng Zeng, **Yijia Xiao**, Haozhe Lyu, Jiayin Zhang, Juanzi Li, Lei Hou

**Abstract**: We propose Language-Model-as-an-Examiner, a novel benchmarking method that utilizes an LM as a knowledgeable examiner to construct dataset and evaluate other models.

</div></div>


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
