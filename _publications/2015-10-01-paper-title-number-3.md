---
title: "EVE: Efficient Vision-Language Pre-training with Masked Prediction and Modality-Aware MoE"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2024-01-01
venue: 'AAAI 2024'
paperurl: 'http://cszhangdy.github.io/files/EVE-AAAI2024.pdf'
citation: 'Junyi Chen,  Longteng Guo, Jia Sun,  Suai Shao,  Zehuan Yuan,  Liang Lin,  Dongyu Zhang*. &quot;Eve: Efficient vision-language pre-training with masked prediction and modality-aware moe.&quot; <i>AAAI 2024</i>.'
---
Building scalable vision-language models to learn from diverse, multimodal data remains an open challenge. In this paper, we introduce an Efficient Vision-languagE foundation model, namely EVE, which is one unified multimodal Transformer pre-trained solely by one unified pre-training task. Specifically, EVE encodes both vision and language within a shared Transformer network integrated with modality-aware sparse Mixture-of-Experts (MoE) modules, which capture modality-specific information by selectively switching to different experts. To unify pre-training tasks of vision and language, EVE performs masked signal modeling on image-text pairs to reconstruct masked signals, i.e., image pixels and text tokens, given visible signals. This simple yet effective pre-training objective accelerates training by 3.5x compared to the model pre-trained with Image-Text Contrastive and Image-Text Matching losses. Owing to the combination of the unified architecture and pre-training task, EVE is easy to scale up, enabling better downstream performance with fewer resources and faster training speed. Despite its simplicity, EVE achieves state-of-the-art performance on various vision-language downstream tasks, including visual question answering, visual reasoning, and image-text retrieval.
