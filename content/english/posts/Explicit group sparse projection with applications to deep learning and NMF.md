---
title:  "Explicit group sparse projection with applications to deep learning and NMF"
image: "images/post/Tranking Brain.png"
author: "Sergey Plis"
date: 2014-03-01T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications"]
featured: true

---
Title: Explicit group sparse projection with applications to deep learning and NMF
  
Authors: Riyasat Ohib, Nicolas Gillis, Niccolò Dalmasso, Sameena Shah, Vamsi K Potluru, Sergey Plis
  
Year: 2019
  
Journal: Transactions on Machine Learning Research
  
Description:
  
We design a new sparse projection method for a set of vectors that guarantees a desired average sparsity level measured leveraging the popular Hoyer measure (an affine function of the ratio of the  and  norms). Existing approaches either project each vector individually or require the use of a regularization parameter which implicitly maps to the average -measure of sparsity. Instead, in our approach we set the sparsity level for the whole set explicitly and simultaneously project a group of vectors with the sparsity level of each vector tuned automatically. We show that the computational complexity of our projection operator is linear in the size of the problem. Additionally, we propose a generalization of this projection by replacing the  norm by its weighted version. We showcase the efficacy of our approach in both supervised and unsupervised learning tasks on image datasets including CIFAR10 and ImageNet. In deep neural network pruning, the sparse models produced by our method on ResNet50 have significantly higher accuracies at corresponding sparsity values compared to existing competitors. In nonnegative matrix factorization, our approach yields competitive reconstruction errors against state-of-the-art algorithms.

  
[View article](https://openreview.net/forum?id=jIrOeWjdpc)  
