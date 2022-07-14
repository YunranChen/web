---
author: Yunran Chen
categories:
- lda
- varitional inference
date: "2018-05-03"
draft: false
excerpt: Build a Python pacakge for application of variational inference on latent dirichlet allocation.
layout: single
title: A python package for variational inference on latent dirichlet allocation
links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/YunranChen/VIonLDA
- icon: file
  icon_pack: far
  name: report
  url: /blog/vi.pdf
---

One of the core problems of modern statistics is to approximate hard-to-compute probability densities. This problem is especially important in Bayesian statistics for posterior density approximate under complex hierarchical structure setting (the one that includes latent variables). Variational Inference (VI) is a method that approximates probability densities through optimization. VI is faster and easier to scale to large data compared to classical methods, such as MCMC sampling. Here we implemented variantional EM algorithm on Latent Dirichlet allocation (LDA). Latent Dirichlet allocation (LDA) is a three-level hierarchical Bayesian model for collections of discrete data, such as text corpora. We present Variational EM on LDA model based on Blei et al. (2003). We present detailed introduction and proof, detailed psudocode, and a package (VIonLDA). We also present the algorithm optimization based on vectorizaiton version which can be extended to not only one-hot-coding matrix. Then we provide an application on a real dataset and get reasonable result. In addition, we present detailed VI algorithm for smoothing LDA. At last, we provide a detailed discussion on ideal data structure.