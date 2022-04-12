---
title: "Protein-LM"
excerpt: "Super Scale Pretraining of Protein Language Models with Megatron-LM<br/><img src='/images/ProteinLM.png' width='50%' height='50%'>"
collection: projects
---


In the project, we implemented the protein language model (masked language model) in Megatron-LM. And pre-trained one protein language model with 3 billion parameters (the *2-nd* largest in the world)

## Overview
- The work (*Wen Su* in Chinese) is a key partition in [WuDao AI](https://en.wikipedia.org/wiki/Wu_Dao).
- The model has been used by 25 institutions, including Harvard University, University of Toronto and NVIDIA Inc (apply at [WuDao Resource](https://resource.wudaoai.cn/)).
- Implementation are available [here](https://github.com/THUDM/ProteinLM).


## Individual contributions:
- Setup the training cluster (480 * Tesla-V100-32G), and manage the computing recources.
- Wrote the (PyTorch) code for protein language model and regression tasks.
- Pretrained the world's second largest protein model.
- Evaluated a series of protein models on eight tasks.
- Wrote the first-author paper, accepted by Pretrain@KDD 2021.
- Made oral presentation in Pretrain@KDD2021's poster session (virtual meeting).


For more detail, please visit this [page](https://yijia-xiao.github.io/publication/2020-08-ProteinLM-Pretrain)