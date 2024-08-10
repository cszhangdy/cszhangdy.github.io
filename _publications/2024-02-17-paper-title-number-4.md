---
title: "Image restoration through generalized ornstein-uhlenbeck bridge"
collection: publications
permalink: /publication/2024-02-17-Image restoration through generalized ornstein-uhlenbeck bridge-number-4
excerpt: 'This paper is about a new bridge diffusion model'
date: 2024-02-17
paperurl: 'http://cszhangdy.github.io/files/GOUB-ICML2024.pdf'
citation: 'Conghan Yue, Zhengwei Peng, Junlong Ma,Shiyan Du, Pengxu Wei, and Dongyu Zhang*. (2024). &quot;Image restoration through generalized ornstein-uhlenbeck bridge&quot; <i>ICML 2024</i>. 1(3).'
---


Diffusion models exhibit powerful generative capabilities enabling noise mapping to data via reverse stochastic differential equations. However, in image restoration, the focus is on the mapping relationship from low-quality to high-quality images. Regarding this issue, we introduce the Generalized Ornstein-Uhlenbeck Bridge (GOUB) model. By leveraging the natural mean-reverting property of the generalized OU process and further eliminating the variance of its steady-state distribution through the Doob’s h–transform, we achieve diffusion mappings from point to point enabling the recovery of high-quality images from low-quality ones. Moreover, we unravel the fundamental mathematical essence shared by various bridge models, all of which are special instances of GOUB and empirically demonstrate the optimality of our proposed models. Additionally, we present the corresponding MeanODE model adept at capturing both pixel-level details and structural perceptions. Experimental outcomes showcase the state-of-the-art performance achieved by both models across diverse tasks, including inpainting, deraining, and super-resolution. Code is available at [https: //github.com/Hammour-steak/GOUB](https: //github.com/Hammour-steak/GOUB).
