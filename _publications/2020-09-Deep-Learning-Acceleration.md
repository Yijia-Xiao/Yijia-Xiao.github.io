---
title: "A Deep Learning Inference Scheme Based on Pipelined Matrix Multiplication Acceleration Design and Non-uniform Quantization"
collection: publications
permalink: /publication/2020-09-deep-learning-acceleration
excerpt: 'We proposed a deep learning inference accelerator based on FPGA, which utilizes quantization and a pipelined matrix multiplication design.'
date: 2020-09-30
venue: 'Yuyang Zhang, *Dik Hin Leung, Min Guo, <b>Yijia Xiao</b>, Haoyue Liu, Yunfei Li, Jiyuan Zhang, Guan Wang, Zhen Chen<br/>IEEE International Conference on Cloud Computing and Intelligence Systems (CCIS)'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

<!-- 
在取得优异表现的同时，现代人工神经网络在能耗和速度方面也有比较明显的短板。大规模的神经网络往往需要数百张显卡和数月的时间来完成训练。而常见的模型如MLP、RNN、CNN和Transformer，其中超过30%的操作都是矩阵的乘法运算，占据了大量时间和资源的矩阵乘法成为制约计算性能的瓶颈。从底层来看，使用通用的计算设备（GPU CPU）来进行特定的运算（矩阵乘法）并不能充分地利用计算设备。以MLP为例，它可以看做一个线性的组合：矩阵乘法、激活函数（softmax/ReLU）、加法（bias）。对此，我们提出了使用特定的设备FPGA进行矩阵乘法加速，并且使用流水线技术，使得数据读取和计算并行进行，充分利用各个组件，提高设备利用率。
 -->
While achieving excellent performance, modern artificial neural networks have a relatively obvious shortcoming in terms of energy consumption and speed. Large-scale neural networks often require hundreds of graphics cards and months of time to complete training. And common models such as MLP, RNN, CNN and Transformer, in which more than 30% of the operations are matrix multiplication operations, occupy a lot of time and resources of the matrix multiplication become a bottleneck to limit the computational performance. From the bottom, using a general-purpose computing device (GPU CPU) for a specific operation (matrix multiplication) does not fully utilize the computing device. Take MLP as an example, it can be seen as a linear combination: matrix multiplication, activation function (softmax/ReLU), and addition (bias). In this regard, we propose to use device-specific FPGAs for matrix multiplication acceleration and to use pipelining techniques that allow data reading and computation to be performed in parallel, making full use of each component and improving device utilization.


The paper is available [here](https://yijia-xiao.github.io/files/publications/Deep_Learning_Pipelined_Matrix_Multiplication_Acceleration_Design.pdf).

Please cite our [paper](https://arxiv.org/abs/2110.04861) if you find this work helpful for your research.
