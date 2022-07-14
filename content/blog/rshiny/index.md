---
author: Yunran Chen
categories:
- Network
- Time series
date: "2018-07-13"
draft: false
excerpt: A toy website for movie recommendation and performer search 
layout: single
subtitle: Course project for STA 532 Statistical Programming
title: Using Rshiny to create a website for movies recommendation

links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/Sta523-Fa17/Project-Drama_Queens
- icon: newspaper
  icon_pack: far
  name: slides
  url: /blog/rshiny.pdf
---

We use Rshiny to create an interface to display information of interesting movies and performers. It also supports movies recommendation and search. The main challeges are two parts: to obtain information from [TMDB](https://www.themoviedb.org/) based on API requests, and then display it in an interactive platform.

Our shiny app supports:

- get the information from the latest movies and popular movies
- ask for movie recommendations based on the genre you prefer
- search for your favorite actors or directors to get their movies and personal information


