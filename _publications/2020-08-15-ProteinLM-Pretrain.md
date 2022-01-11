---
title: "Modeling Protein Using Large-scale Pretrain Language Model"
collection: publications
permalink: /publication/2020-08-15-ProteinLM-Pretrain
excerpt: 'We pretrained <b><i>Wen Su</i></b>, the second largest protein language model in the world.'
date: 2021-08-15
venue: 'Pretrain@KDD2021 (The International Workshop on Pretraining: Algorithms, Architectures, and Applications)'
# paperurl: 'https://arxiv.org/abs/2108.07435'
# citation: '<b>Yijia Xiao</b>, Jiezhong Qiu, Ziang Li, Chang-Yu Hsieh and *Jie Tang (2020). &quot;Modeling Protein Using Large-scale Pretrain Language Model.&quot; <i>Pretrain@KDD2021</i>.'
---

<!-- <span style="color:red">Highlight</span> We have pretrained the world's second largest protein language model -->

**Protein** is linked to almost every life process. Therefore, analyzing the biological structure and property of protein sequences is critical to the exploration of life, as well as disease detection and drug discovery.

Artificial intelligence models excel in modeling the relationship between features and labels (e.g. inferencing label from input features), and have prove to be successful in text and vision tasks. However, things are a little bit different when it comes to biological data. On the one hand, labeling biological data requires domain knowledge. So it requires expertise and cannot be done via crowd-sourcing. On the other hand, the quantity of training data plays a critical role in the performance of artificial models. So building a high-quality dataset requires the involvement of lots of experts and can be labor-intensive.

Fortunately, the high-throughput sequencing technology provides us with abundant primary structure (unlabeled) sequences, which are gold mines to be exploited. **Pretrain** technique can be leveraged to bridge the gap between massive unlabeled data and limited amount of labeled data. In the protein case, we can pretrain protein language models on the protein sequence databases (like [PFAM](http://pfam.xfam.org/), [UniRef](https://www.uniprot.org/help/uniref), etc.), and then **finetune** the model on downstream tasks. The pretrained model have grasped some 'universal knowledge' of protein sequences, so finetuning only need to apply some task-specific signals to the model, and thus requires much less labeled data.


Based on the scheme described above, we have pretrained a series of protein language models on `PFAM` dataset, and tested them on five downstream tasks (contact prediction, secondary structure, homology, stability and florescence). The largest model (with 3 billion parameters) exceeded the contact prediction baseline by a wide margin, improving `Precision@L/5` from 36% to 75%.


The paper is available [here](https://yijia-xiao.github.io/files/publications/Large-scale_Protein_Language_Model_Pretrain.pdf). The codes needed for pretraining and reproducing results are available [here](https://github.com/THUDM/ProteinLM). If you wish to download the models, you will need [apply](https://resource.wudaoai.cn/) and submit your affiliation and purposes. The models are free for usage in academic research.

Please [cite](https://dblp.uni-trier.de/rec/journals/corr/abs-2108-07435.html?view=bibtex) our paper if you find this work helpful for your research.
