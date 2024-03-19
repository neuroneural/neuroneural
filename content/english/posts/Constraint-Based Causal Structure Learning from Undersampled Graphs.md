---
title: "Constraint-Based Causal Structure Learning from Undersampled Graphs"
image: "images/post/Constraint.png"
author: "Sergey Plis"
date: 2022-05-18T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications"]
featured: true

---

Authors : Mohammadsajad Abavisani, David Danks, Sergey Plis

Publication date : 2022/5/18

Journal : arXiv preprint arXiv:2205.09235


Description

Graphical structures estimated by causal learning algorithms from time series data can provide highly misleading causal information if the causal timescale of the generating process fails to match the measurement timescale of the data. Although this problem has been recently recognized, practitioners have limited resources to respond to it, and so must continue using models that they know are likely misleading. Existing methods either (a) require that the difference between causal and measurement timescales is known; or (b) can handle only very small number of random variables when the timescale difference is unknown; or (c) apply to only pairs of variables, though with fewer assumptions about prior knowledge; or (d) return impractically too many solutions. This paper addresses all four challenges. We combine constraint programming with both theoretical insights into the problem structure and prior information about admissible causal interactions. The resulting system provides a practical approach that scales to significantly larger sets (>100) of random variables, does not require precise knowledge of the timescale difference, supports edge misidentification and parametric connection strengths, and can provide the optimum choice among many possible solutions. The cumulative impact of these improvements is gain of multiple orders of magnitude in speed and informativeness.


[View article](https://arxiv.org/abs/2205.09235)
