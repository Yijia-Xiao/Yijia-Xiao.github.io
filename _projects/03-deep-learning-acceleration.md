---
title: "Deep Learning Inference Acceleration with FPGA"
excerpt: "Use quantization and a pipeline matrix multiplication design.<br/><img src='/images/FPGA.png' width='45%' height='45%'>"
collection: projects
---

We proposed a MLP accelerator based on FPGA, which utilizes quantization and a novel matrix multiplication design.

The matrix multiplication is decomposed into data-loading process (from RAM) and data-computing process (within registers). 

We also implement floating-point quantization on FPGA by using the extended SP-x quantization methodology, which simplify scalar calculation while achieving good linear characteristics in  almost the whole quantization interval. 

Individual contributions:
- Literature review: inference acceleration's paradigms and application.
- Experiments: setup deep learning framework, train the model, measure the power consumption.
- Writing: composed the `related work` part of the paper.
- Supervision: tracked the project's progress with the corresponding author.


For more detail, please visit this [page](https://yijia-xiao.github.io/publication/2020-09-deep-learning-acceleration)