---
title: "Predicting the effects of mutations on protein solubility using graph convolution network and protein language model representation"
collection: publications
category: manuscripts
permalink: /publication/2023-11-paper-deepmutsol-number-6
excerpt: 'Mutation-caused protein solubility change prediction'
date: 2023-11-7
venue: 'Journal of Computational Chemistry'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Wang, J., Chen, S., Yuan, Q., Chen, J., Li, D., Wang, L., & Yang, Y. (2024). Predicting the effects of mutations on protein solubility using graph convolution network and protein language model representation. Journal of Computational Chemistry, 45(8), 436-445.'
---

Solubility is one of the most important properties of protein. Protein solubility can be greatly changed by single amino acid mutations and the reduced protein solubility could lead to diseases. Since experimental methods to determine solubility are time-consuming and expensive, in-silico methods have been developed to predict the protein solubility changes caused by mutations mostly through protein evolution information. However, these methods are slow since it takes long time to obtain evolution information through multiple sequence alignment. In addition, these methods are of low performance because they do not fully utilize protein 3D structures due to a lack of experimental structures for most proteins. Here, we proposed a sequence-based method DeepMutSol to predict solubility change from residual mutations based on the Graph Convolutional Neural Network (GCN), where the protein graph was initiated according to predicted protein structure from Alphafold2, and the nodes (residues) were represented by protein language embeddings. To circumvent the small data of solubility changes, we further pretrained the model over absolute protein solubility. DeepMutSol was shown to outperform state-of-the-art methods in benchmark tests. In addition, we applied the method to clinically relevant genes from the ClinVar database and the predicted solubility changes were shown able to separate pathogenic mutations. All of the data sets and the source code are available at https://github.com/biomed-AI/DeepMutSol.
