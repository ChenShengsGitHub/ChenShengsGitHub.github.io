---
title: "AlphaFold2-aware protein–DNA binding site prediction using graph transformer"
collection: publications
category: manuscripts
permalink: /publication/2022-1-paper-graphsite-number-4
excerpt: 'identification of Protein–DNA interactions'
date: 2022-1-17
venue: 'Briefings in bioinformatics'
paperurl: '/files/graphsite.pdf'
citation: 'Yuan, Q., Chen, S., Rao, J., Zheng, S., Zhao, H., & Yang, Y. (2022). AlphaFold2-aware protein–DNA binding site prediction using graph transformer. Briefings in Bioinformatics, 23(2), bbab564.'
---

Protein–DNA interactions play crucial roles in the biological systems, and identifying protein–DNA binding sites is the first step for mechanistic understanding of various biological activities (such as transcription and repair) and designing novel drugs. How to accurately identify DNA-binding residues from only protein sequence remains a challenging task. Currently, most existing sequence-based methods only consider contextual features of the sequential neighbors, which are limited to capture spatial information. Based on the recent breakthrough in protein structure prediction by AlphaFold2, we propose an accurate predictor, GraphSite, for identifying DNA-binding residues based on the structural models predicted by AlphaFold2. Here, we convert the binding site prediction problem into a graph node classification task and employ a transformer-based variant model to take the protein structural information into account. By leveraging predicted protein structures and graph transformer, GraphSite substantially improves over the latest sequence-based and structure-based methods. The algorithm is further confirmed on the independent test set of 181 proteins, where GraphSite surpasses the state-of-the-art structure-based method by 16.4% in area under the precision-recall curve and 11.2% in Matthews correlation coefficient, respectively. We provide the datasets, the predicted structures and the source codes along with the pre-trained models of GraphSite at https://github.com/biomed-AI/GraphSite. The GraphSite web server is freely available at https://biomed.nscc-gz.cn/apps/GraphSite.
