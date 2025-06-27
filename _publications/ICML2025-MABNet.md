---
title: "Quadruple Attention in Many-body Systems for Accurate Molecular Property Predictions"
collection: publications
category: conferences
permalink: /publication/ICML2025-MABNet
date: 2025-07-17
venue: 'ICML'
paperurl: '[ICML Poster](https://icml.cc/virtual/2025/poster/44950)'
---

While Graph Neural Networks and Transformers have shown promise in predicting molecular properties, they struggle with directly modeling complex many-body interactions. Current methods often approximate interactions like three- and four-body terms in message passing, while attention-based models, despite enabling direct atom communication, are typically limited to triplets, making higher-order interactions computationally demanding. To address the limitations, we introduce MABNet, a geometric attention framework designed to model four-body interactions by facilitating direct communication among atomic quartets. This approach bypasses the computational bottlenecks associated with traditional triplet-based attention mechanisms, allowing for the efficient handling of higher-order interactions. MABNet achieves state-of-the-art performance on benchmarks like MD22 and SPICE. These improvements underscore its capability to accurately capture intricate many-body interactions in large molecules. By unifying rigorous many-body physics with computational efficiency, MABNet advances molecular simulations for applications in drug design and materials discovery, while its extensible framework paves the way for modeling higher-order quantum effects.
