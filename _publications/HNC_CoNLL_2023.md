---
title: "HNC: Leveraging Hard Negative Captions towards Models with Fine-Grained Visual-Linguistic Comprehension Capabilities"
collection: publications
permalink: /publication/HNC_CoNLL_2023
excerpt: 'Esra Dönmez\*, Pascal Tilli\*, **Hsiu-Yu Yang**, Ngoc Thang Vu, Carina Silberer (\*=equal contribution)'
date: 2023-12-06
venue: 'the 27th Conference on Computational Natural Language Learning (CoNLL)'
paperurl: 'https://aclanthology.org/2023.conll-1.24/'
---
Image-Text-Matching (ITM) is one of the defacto methods of learning generalized representations from a large corpus in Vision and Language (VL). However, due to the weak association between the web-collected image–text pairs, models fail to show fine-grained understanding of the combined semantics of these modalities. To this end, we propose Hard Negative Captions (HNC): an automatically created dataset containing foiled hard negative captions for ITM training towards achieving fine-grained cross-modal comprehension in VL. Additionally, we provide a challenging manually-created test set for benchmarking models on a fine-grained cross-modal mismatch with varying levels of compositional complexity. Our results show the effectiveness of training on HNC by improving the models’ zero-shot capabilities in detecting mismatches on diagnostic tasks and performing robustly under noisy visual input scenarios. Also, we demonstrate that HNC models yield a comparable or better initialization for fine-tuning. Our code and data are publicly available.
