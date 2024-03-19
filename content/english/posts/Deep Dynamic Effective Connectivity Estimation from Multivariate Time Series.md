---
title: "Deep Dynamic Effective Connectivity Estimation from Multivariate Time Series"
image: "images/post/Time.png"
author: "Sergey Plis"
date: 2022-02-04T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications", "2022"]
featured: true

---

Authors : Usman Mahmood, Zening Fu, Vince Calhoun, Sergey Plis

Publication date : 2022/2/4

Journal : arXiv preprint arXiv:2202.02393

Description

Recently, methods that represent data as a graph, such as graph neural networks (GNNs) have been successfully used to learn data representations and structures to solve classification and link prediction problems. The applications of such methods are vast and diverse, but most of the current work relies on the assumption of a static graph. This assumption does not hold for many highly dynamic systems, where the underlying connectivity structure is non-stationary and is mostly unobserved. Using a static model in these situations may result in sub-optimal performance. In contrast, modeling changes in graph structure with time can provide information about the system whose applications go beyond classification. Most work of this type does not learn effective connectivity and focuses on cross-correlation between nodes to generate undirected graphs. An undirected graph is unable to capture direction of an interaction which is vital in many fields, including neuroscience. To bridge this gap, we developed dynamic effective connectivity estimation via neural network training (DECENNT), a novel model to learn an interpretable directed and dynamic graph induced by the downstream classification/prediction task. DECENNT outperforms state-of-the-art (SOTA) methods on five different tasks and infers interpretable task-specific dynamic graphs. The dynamic graphs inferred from functional neuroimaging data align well with the existing literature and provide additional information. Additionally, the temporal attention module of DECENNT identifies time-intervals crucial for predictive downstream task from multivariate time series data.


[View article](https://arxiv.org/abs/2202.02393)
