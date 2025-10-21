---
title: "Accurately Predicting Protein Mutational Effects via a Hierarchical Many-Body Attention Network"
collection: publications
category: conferences
permalink: /publication/NeurIPS2025-H3-DDG
excerpt: We propose H3-DDG, a Hypergraph-driven Hierarchical network to capture Higher-order many-body interactions across multiple scales. By introducing a hierarchical communication mechanism, H3-DDG effectively models both local and global mutational effects.
date: 2025-10-30
venue: 'Annual Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: ''
bibtexurl: ''
---

Predicting changes in binding free energy ($\Delta\Delta G$) is essential for understanding protein-protein interactions, which are critical in drug design and protein engineering. However, existing methods often rely on pre-trained knowledge and heuristic features, limiting their ability to accurately model complex mutation effects, particularly higher-order and many-body interactions.
To address these challenges, we propose \textbf{H3-DDG}, a \textbf{H}ypergraph-driven \textbf{H}ierarchical network to capture \textbf{H}igher-order many-body interactions across multiple scales. By introducing a hierarchical communication mechanism, H3-DDG effectively models both local and global mutational effects.
Experimental results demonstrate state-of-the-art performance on multiple benchmarks. On the SKEMPI v2 dataset, H3-DDG achieves a Pearson correlation of 0.75, improving multi-point mutations prediction by 12.10\%. On the challenging BindingGYM dataset, it outperforms Prompt-DDG and BA-DDG by 62.61\% and 34.26\%, respectively.
Ablation and efficiency analyses demonstrate its robustness and scalability, while a case study on SARS-CoV-2 antibodies highlights its practical value in improving binding affinity for therapeutic design.
