---
title:  "Privacy-preserving quality control of neuroimaging datasets in federated environment"
image: "images/post/Tranking Brain.png"
author: "Sergey Plis"
date: 2014-03-01T05:00:00Z
description: "This is meta description"
categories: ["Publications"]
tags: ["Paper", "Publications"]
featured: true

---
Title: Privacy-preserving quality control of neuroimaging datasets in federated environment
  
Authors: Debbrata K Saha, VD Calhoun, Y Du, Z Fu, Sandeep R Panta, S Kwon, AD Sarwate, SM Plis
  
Year: 2021
  
Journal: bioRxiv
  
Pages: 826974
  
Publisher: Cold Spring Harbor Laboratory
  
Description:
  
Privacy concerns for rare disease data, institutional or IRB policies, access to local computational or storage resources or download capabilities are among the reasons that may preclude analyses that pool data to a single site. A growing number of multi-site projects and consortia were formed to function in the federated environment to conduct productive research under constraints of this kind. In this scenario, a quality control tool that visualizes decentralized data in its entirety via global aggregation of local computations is especially important, as it would allow the screening of samples that cannot be jointly evaluated otherwise. To solve this issue, we present two algorithms: decentralized data stochastic neighbor embedding, dSNE, and its differentially private counterpart, DP-dSNE. We leverage publicly available datasets to simultaneously map data samples located at different sites according to their similarities. Even though the data never leaves the individual sites, dSNE does not provide any formal privacy guarantees. To overcome that, we rely on differential privacy: a formal mathematical guarantee that protects individuals from being identified as contributors to a dataset. We implement DP-dSNE with AdaCliP, a method recently proposed to add less noise to the gradients per iteration. We introduce metrics for measuring the embedding quality and validate our algorithms on these metrics against their centralized counterpart on two toy datasets. Our validation on six multi-site neuroimaging datasets shows promising results for the quality control tasks of visualization and outlier detection, highlighting the potential of our private, decentralized …

  
[View article](https://www.biorxiv.org/content/10.1101/826974.abstract)  
