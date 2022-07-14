---
author: Yunran Chen
categories:
- teaching
date: "2019-01-09"
date_end: "2019-05-04"
draft: false
event: Duke University (Spring 2019)
event_url: ""
excerpt: Graduate-level course introducing statistical theory and methods for social network analysis
featured: true
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: http://www2.stat.duke.edu/courses/Spring19/sta650.001/
- icon: newspaper
  icon_pack: far
  name: lab materials
  url: https://yunranchen.github.io/intro-net-r/
location: Durham, USA
show_post_time: false
subtitle: Graduate-level course introducing statistical theory and methods for social network analysis
title: STA450/650 Theory and Methods for Social Network Analysis
---

I served as a teaching assistant, holding a 75-min lab and 2-hr office hour weekly. I prepared a detailed tutorial for my lab and knitted it using `bookdown` package, which covers the basic network analysis using R.

## Outline

- Basic introduction on network objects.
  - R packages including `igraph`, `statnet` (including `sna`, `network` packages).
- Collect network data:
  - API requests using R packages (`rtweet`, `Rfacebook`, `RedditExtractoR`, `imdbapi`, `omdbapi`).
  - API requests from R directly (`rjson`, `jsonlite`)
  - Useful websites: (SNAP, [Awesome Network Analysis](https://github.com/briatte/awesome-network-analysis))
- Fancy visualization (static and dynamic networks):
  - ggplot2 version: `ggnet2`, `geomnet`, `ggnetwork`
  - Interactive network visualization: `ggplot2` + `plotly`, `visNetwork`
  - Dynamic network visualization: `ggnetwork`, `ggplot2` + `gganimate`, `ndtv`
- Network analysis using package `amen`, `statnet`.


