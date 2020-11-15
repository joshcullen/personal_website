---
date: "2020-11-15T00:00:00Z"
external_link: ""
image:
  caption: Photo by Russ on Wikimedia Commons
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: 
  url: 
slides: 
summary: Developing new methods to extract more from animal movement data.
tags:
- Movement Ecology
- Quantitative Ecology
- Bayesian Statistics
title: Identifying Latent Behavioral States From Animal Biotelemetry Data Using Non-parametric Bayesian Methods
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Movement decisions of an organism can impact habitat use, foraging strategies, reproductive success, and survival, which ultimately affects population dynamics of a species. The study of animal movement has increased in the past few decades, along with the increased capacity of telemetry devices to record locations with greater accuracy and over longer durations. Although there are a wide variety of existing methods that estimate latent behavioral states, many of these methods have limitations for their use and inference (e.g., only analyze one data stream, require parametric distributions).

We have developed a non-parametric Bayesian framework that addresses some of the limitations of these existing methods for the estimation of animal behavioral states. This framework uses a two-stage approach: 1) Multiple data streams (e.g., step length, turning angle, temperature, depth) are partitioned into track segments for each ID; 2) Track segments are pooled across IDs and clustered to determine the optimal number of states and their distributions per data stream. This proposed framework provides a fast and flexible method to characterize latent states at the level of track segments, which may be particularly useful when time steps are short (and therefore behavior is highly autocorrelated) and when distributions of data streams are not well fit by parametric distributions.