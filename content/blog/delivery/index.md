---
author: Yunran Chen
categories:
- regression
- correlated predictors
date: "2020-01-23"
draft: false
excerpt: Case study of effects of DDE and PCB exposure on premature delivery
layout: single
subtitle: Case study of effects of DDE and PCB exposure on premature delivery
title: Regression analysis for highly correlated predictors 
links:
- icon: file
  icon_pack: far
  name: report
  url: /blog/delivery.pdf
---

DDE and PCB chemicals were proven to be toxic and may relate to premature delivery risk. The dataset contains concentration doses for DDE and 12 PCB members, which are highly correlated. Here we consider a two-stage regression analysis to apply PCA to extract the main components (decorrelate) of 12 PCB members and apply regression analysis.