---
author: Yunran Chen
categories:
- Causal Inference
- Network
date: "2019-01-02"
draft: false
excerpt: In observation studies, interference may occur if our target population has a network structure. Basic idea is to extend traditional framework and assumptions to take neighbors into consideration. We reproduced simulations by Forastiere et al. (2016) to construct propensity score based estimator in a Facebook network.
layout: single
subtitle: Course project for STA 640 Causal Inference
title: Causal Inference with Interference
links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/YunranChen/Interference_in_CI
- icon: newspaper
  icon_pack: far
  name: slides
  url: /blog/ci_slides.pdf
- icon: file
  icon_pack: far
  name: report
  url: /blog/ci_report.pdf
---

In observation studies, our target population may have a network structure. Interference may occur if the potential outcome of one unit depends on both individual treatment and neighborhood treatment. The present of interference will break down the traditional assumptions and framework. In this project, we review the paper by Forastiere et al.(2016), which provides a extended framework and solution for the existence of interference. The basic idea for the framework and assumption extension is to take neighbors into consideration, which means to extend potential outcomes, assignment mechanism and average does-response function as a function of both individual and neighborhood treatment. Accordingly, propensity score is generalized to a joint propensity score then decomposed to individual and neighborhood propensity score, from which a estimating procedure is proposed. Here we focus only on causal inference on main effect (individual effect) when interference presents. We reproduced the simulations by Forastiere et al. (2016) based on Facebook data obtained from Stanford Network Analysis Project (SNAP) (Leskovec and Mcaule, 2012).

