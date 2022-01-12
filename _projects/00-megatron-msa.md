---
title: "Megatron-MSA: Cracking the Grammar of Protein MSA via Super Scale Pretraining"
excerpt: "Cracking the Grammar of Protein via modeling the co-evolution information in protein MSA<br/><img src='/images/3-long-165-hit-98.png' width='45%' height='45%'>"
collection: projects
---

`Work in progress, co-advised by Prof. Jinbo Xu and Prof. Jie Tang.`

Proteins are an indispensable part of life and are linked to almost every important activity in life. Therefore, deciphering protein structures is crucial to the study of life sciences. For decades, researchers have proposed various methods to infer the structure of proteins The primary sequence of a protein. However, inference from individual ones is difficult because there are few co-evolutionary processes that can be extracted from pure primary sequences. Only limited co-evolution can be extracted from pure primary sequences.

Multiple sequence alignment (MSA) provides a good alternative solution. Co-modeling of aligned protein sequences can provide co-evolutionary information between amino acid residues in a protein for structure prediction. prediction. On the other hand, the excellent performance of pre-trained language models on a range of natural language tasks The excellent performance of pre-trained language models on a range of natural language tasks illustrates its potential in identifying patterns from large amounts of unlabeled data Identifying patterns from large amounts of unlabeled data. Combination of multiple sequence alignment and large-scale pre-training The combination of sequence alignment and large-scale pre-trained language models will enable even more precise modeling of proteins.

<p align="center">
<img src='/images/RPLP0_90_ClustalW_aln.png' width="75%" height="75%">
</p>

We pre-trained a 1 billion parameter MSA transformer model, Protein-MSA-1B. To our knowledge, this is the largest pre-trained MSA language model in the world. We demonstrated that scaling up the model size can significantly improve data utilization. On the first stage, trained with only 5.7% of the baseline data (1.5 million MSA), our model exceeds the baseline Our model exceeds the performance of the baseline in terms of contact prediction. On the following stage, we are using ~ 40 million (also more diverse) MSA data.

Codes, models, inference toolkits will be released soon.
