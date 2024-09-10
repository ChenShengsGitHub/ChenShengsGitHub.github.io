---
title: "Alignment-free metal ion-binding site prediction from protein sequence through pretrained language model and multi-task learning"
collection: publications
category: manuscripts
permalink: /publication/2023-11-paper-deepmutsol-number-6
excerpt: 'Mutation-caused protein solubility change prediction'
date: 2024-1
venue: 'Journal of Computational Chemistry'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Wang, J., Chen, S., Yuan, Q., Chen, J., Li, D., Wang, L., & Yang, Y. (2024). Predicting the effects of mutations on protein solubility using graph convolution network and protein language model representation. Journal of Computational Chemistry, 45(8), 436-445.'
---

More than one-third of the proteins contain metal ions in the Protein Data Bank. Correct identification of metal ion-binding residues is important for understanding protein functions and designing novel drugs. Due to the small size and high versatility of metal ions, it remains challenging to computationally predict their binding sites from protein sequence. Existing sequence-based methods are of low accuracy due to the lack of structural information, and time-consuming owing to the usage of multi-sequence alignment. Here, we propose LMetalSite, an alignment-free sequence-based predictor for binding sites of the four most frequently seen metal ions in BioLiP (Zn2+, Ca2+, Mg2+ and Mn2+). LMetalSite leverages the pretrained language model to rapidly generate informative sequence representations and employs transformer to capture long-range dependencies. Multi-task learning is adopted to compensate for the scarcity of training data and capture the intrinsic similarities between different metal ions. LMetalSite was shown to surpass state-of-the-art structure-based methods by more than 19.7, 14.4, 36.8 and 12.6% in area under the precision recall on the four independent tests, respectively. Further analyses indicated that the self-attention modules are effective to learn the structural contexts of residues from protein sequence. We provide the data sets, source codes and trained models of LMetalSite at https://github.com/biomed-AI/LMetalSite.
