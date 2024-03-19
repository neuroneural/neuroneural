---
title: "Geometrically Guided Saliency Maps"
image: "images/post/Map.png"
author: "Sergey Plis"
date: 2022-03-05T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications"]
featured: false

---

Authors : Md Mahfuzur Rahman, Noah Lewis, Sergey Plis

Publication date : 2014/3/1

Conference : ICLR 2022 Workshop on PAIR {\textasciicircum

Description

Interpretability methods for deep neural networks mainly focus on modifying the rules of automatic differentiation or perturbing the input and observing the score drop to determine the most relevant features. Among them, gradient-based attribution methods, such as saliency maps, are arguably the most popular. Still, the produced saliency maps may often lack intelligibility. We address this problem based on recent discoveries in geometric properties of deep neural networks' loss landscape that reveal the existence of a multiplicity of local minima in the vicinity of a trained model's loss surface. We introduce two methods that leverage the geometry of the loss landscape to improve interpretability: 1)" Geometrically Guided Integrated Gradients", applying gradient ascent to each interpolation point of the linear path as a guide. 2)" Geometric Ensemble Gradients", generating ensemble saliency maps by sampling proximal iso-loss models. Compared to vanilla and integrated gradients, these methods significantly improve saliency maps in quantitative and visual terms. We verify our findings on MNIST and Imagenet datasets across convolutional, ResNet, and Inception V3 architectures.


[View article](https://openreview.net/forum?id=rtIeCBr8W-5)
