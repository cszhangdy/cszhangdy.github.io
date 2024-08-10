---
title: "Generalizing Factorization of Gans by Characterizing Convolutional Layers"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about Generalizing Factorization of Gans by Characterizing Convolutional Layers.'
date: 2022
venue: 'IEEE International Conference on Multimedia and Expo'
paperurl: 'http://cszhangdy.github.io/files/Generalizing_ICME2022.pdf'
citation: 'Yuehui Wang, Qing Wang, and Dongyu Zhang*. &quot;Generalizing Factorization of Gans by Characterizing Convolutional Layers (2022).&quot; <i>IEEE International Conference on Multimedia and Expo</i>. 1(1).'
---

Existing unsupervised disentanglement methods in latent space of the Generative Adversarial Networks (GANs) rely on the analysis and decomposition of pre-trained weight matrix.
However, they only consider the weight matrix of the fully connected layers, ignoring the convolutional layers which are indispensable for image processing in modern generative
models. This results in the learned latent semantics lack interpretability, which is unacceptable for image editing tasks. In this paper, we propose a more generalized closed-form factorization of latent semantics in GANs, which takes the convolutional layers into consideration when searching for the underlying variation factors. Our method can be applied to a wide range of deep generators with just a few lines of code. Extensive experiments on multiple GAN models trained on various datasets show that our approach is capable of not only finding semantically meaningful dimensions, but also maintaining the consistency and interpretability of image content.
