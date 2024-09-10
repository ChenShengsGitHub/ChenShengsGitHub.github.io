---
title: "SE (3) Equivalent Graph Attention Network as an Energy-Based Model for Protein Side Chain Conformation"
collection: publications
category: conferences
permalink: /publication/2023-12-paper-graphebm-number-7
excerpt: 'Protein side chain conformation prediction'
date: 2023-12-5
venue: 'IEEE BIBM 2023'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Liu, D., Chen, S., Zheng, S., Zhang, S., & Yang, Y. (2023, December). SE (3) Equivalent Graph Attention Network as an Energy-Based Model for Protein Side Chain Conformation. In 2023 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 120-123). IEEE.'
---

Protein design energy functions have been developed over decades by leveraging physical forces approximation and knowledge-derived features. However, manual feature engineering and parameter tuning might suffer from knowledge bias. Learning potential energy functions fully from crystal structure data is promising to automatically discover unknown or highorder features contributing to the protein’s energy. Here we propose a novel data-driven energy-based model based on SE(3)-equivariant model for protein conformation, namely GraphEBM. By combining with the graph attention network, GraphEBM improve the massage passing on the chemical bond and capture the interatomic interaction and overlap. GraphEBM was benchmarked on the local rotamer recovery task and found to outperform both Rosetta and the state-of-the-art deep learning based methods. Furthermore, GraphEBM also yielded promising results on combinatorial side chain optimization, improving 13.8% X1 rotamer recovery to the Atom Transformer method on average.
