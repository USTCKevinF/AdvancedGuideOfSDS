---
description: 学分：3.0
---

# 大数据算法（专业核心）

## 课程简介

大数据算法课程内容主要包括降维算法、数据流算法、监督机器学习和无监督机器学习（特指聚类）算法。大数据算法一大重要的手段就是通过概率不等式放缩从而分析算法性质或者推导参数取值，具体而言，主要利用Markov、Chebyshev、Chernoff-Hoeffding三大不等式对某个概率的表达式进行缩放，分析出这个概率的上界或者下界，进一步可以利用导出的界对概率进行约束，从而确定超参数的取值。这一范式通用于课堂、作业和考试。大数据算法的另一精髓思想是对某个不稳定的随机算法A（比如算法A，以一个较低的概率输出正确解），可以通过多次运行算法A输出其输出结果的均值从而提高随机算法的稳定性（往往称为算法A+），进一步地，可以多次运行算法A+输出其输出结果的中位数从而更一步提高算法稳定性（往往称为算法A++）。另外，课程会在PAC学习部分讲解VC-dimension、在聚类算法部分介绍D^2采样（Kmean++算法的核心）、Coreset等概念等等。课堂讲解SVD算法主要是依照贪心算法的思路逐步完善，其实也可以通过线性代数手段对课上讲解的引理进行分析——实方阵的正交相似标准型与实矩阵的正交相抵标准型理论。

## 前置知识涉及的课程

数据结构、线性代数B1、概率论、离散数学

## 往年经验

2023春季学期的这门课体验很好，总体而言，难度水平课堂>作业>考试。课堂内容充实，值得一听，同时考前速成也不是问题，是一门两全其美的好课。课堂资料全为英文版，可能会对部分同学的学习造成影响，但AI方面的文献与视频几乎都为英文版，大数据夏令营面试也有英文问答环节，部分导师的招生考核也会有论文考核，所以这方面的困难需要克服。

## 与后续课程的联系

关于机器学习理论部分的一些核心概念介绍对于理解机器学习有较大帮助，而算法部分与数据挖掘领域如检索领域又有较多应用。

## 课程资源

{% embed url="https://rec.ustc.edu.cn/share/bf0a30f0-515b-11ee-9f4c-fd10d73f615e" %}

## 目录

<details>

<summary>大数据算法教学大纲</summary>

#### Dimension Reduction <a href="#anonymous_element_9" id="anonymous_element_9"></a>

#### Streaming and Sketching Algorithms <a href="#anonymous_element_18" id="anonymous_element_18"></a>

#### Machine Learning <a href="#anonymous_element_27" id="anonymous_element_27"></a>

#### Clustering <a href="#anonymous_element_34" id="anonymous_element_34"></a>

</details>

