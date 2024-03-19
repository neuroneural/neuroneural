---
title:  "Grouped sparse projection"
image: "images/post/Tranking Brain.png"
author: "Sergey Plis"
date: 2014-03-01T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications"]
featured: true

---
Title: Grouped sparse projection
  
Authors: Nicolas Gillis, Riyasat Ohib, Sergey Plis, Vamsi Potluru
  
Year: 2019
  
Journal: arXiv preprint arXiv:1912.03896
  
Description:
  
As evident from deep learning, very large models bring improvements in training dynamics and representation power. Yet, smaller models have benefits of energy efficiency and interpretability. To get the benefits from both ends of the spectrum we often encourage sparsity in the model. Unfortunately, most existing approaches do not have a controllable way to request a desired value of sparsity in an interpretable parameter. In this paper, we design a new sparse projection method for a set of vectors in order to achieve a desired average level of sparsity which is measured using the ratio of the  and  norms. Most existing methods project each vector individuality trying to achieve a target sparsity, hence the user has to choose a sparsity level for each vector (e.g., impose that all vectors have the same sparsity). Instead, we project all vectors together to achieve an average target sparsity, where the sparsity levels of the vectors is automatically tuned. We also propose a generalization of this projection using a new notion of weighted sparsity measured using the ratio of a weighted  and the  norms. These projections can be used in particular to sparsify the columns of a matrix, which we use to compute sparse nonnegative matrix factorization and to learn sparse deep networks.

  
[View article](https://arxiv.org/abs/1912.03896)  
