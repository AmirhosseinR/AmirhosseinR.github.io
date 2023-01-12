---
layout: single
title:  "Publications"
date:   2023-01-12 15:55:55 +0200
tags: [paper]
categories: PROJECTS
header:
  teaser: /assets/images/paper.jpeg
  overlay_image: /assets/images/paper.jpg
  caption: "Photo credit: [**blende12 @ pexels**](https://pixabay.com/photos/book-read-old-literature-books-1659717/)"
show_date: true
excerpt: "Papers and codes"
comment_issue_id: 1
---

**1- E-prop on SpiNNaker 2**  

  [E-prop on SpiNNaker 2: Exploring online learning in spiking RNNs on neuromorphic hardware](https://www.frontiersin.org/articles/10.3389/fnins.2022.1018006/full)  
  A Rostami, B Vogginger, Y Yexin, C G Mayr  
  Frontiers in Neuroscience, November 2022  

- Summary:  
  We implement the E-prop algorithm on a prototype of the SpiNNaker 2 neuromorphic system. A parallelization strategy is developed to split and train networks on the ARM cores of SpiNNaker 2 to make efficient use of both memory and compute resources. We trained an SRNN from scratch on SpiNNaker 2 in real-time on the Google Speech Command dataset for keyword spotting.

- TensorFlow v2 and C codes are available publicly at:  
[https://gitlab.com/tud-hpsn/public/e-prop-on-gsc/](https://gitlab.com/tud-hpsn/public/e-prop-on-gsc/)


![image](/assets/images/parallelization.jpg)

