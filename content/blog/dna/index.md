---
author: Yunran Chen
categories:
- Network
- Time series
date: "2018-12-12"
draft: false
excerpt: Fit a dynamic international relationship to explore the time-varying relational structure 
layout: single
subtitle: Course project for STA 642 Time Series
title: Dynamic Network Analysis on International Relationship
links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/YunranChen/DynamicRelationship
- icon: newspaper
  icon_pack: far
  name: slides
  url: /blog/dna_slides.pdf
- icon: file
  icon_pack: far
  name: report
  url: /blog/dna_report.pdf
---

I am interested in modeling dynamic networks, where each edge between pairs of nodes can be seen as a time series. Here I am trying to fit a dynamic international relationship to explore the time-varying relational structure instead of making prediction.

For social networks, the latent space model proposed by Hoff et al. (2002, 2005) is widely used. The basic idea is to introduce a multiplicative random effect to the mix effect model. Such multiplicative random effect can induce a third dependence structure, which accommodates some typical dyadic characteristics, such as homophily and stochastic equivalence (“friends of my friends are my friends”, “enemies of enemies are my friends”) (Hoff 2008). However, the latent space model is for static networks. Durante and Dunson (2014) extended this model to a model for dynamic networks evolving in continuous time by setting Gaussian process for each element. Instead of considering continuous time, I consider discrete time series. Explicitly, I assume each element as a stationary AR(1) process. First, I explored the properties of product of two stationary AR(1) processes. Based on this, I derived Gibbs sampling scheme with Polya-Gamma augmentation for posterior computation. Then I did extensive simulations on the choice of parameters and applied the proposed model to analyze the real dataset. At the end I provide detailed discussion on the limitations and further directions.