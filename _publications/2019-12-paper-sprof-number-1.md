---
title: "To Improve Protein Sequence Profile Prediction through Image Captioning on Pairwise Residue Distance Map"
collection: publications
category: manuscripts
permalink: /publication/2019-12-paper-sprof-number-1
excerpt: 'protein design/ protein sequence profile prediction.'
date: 2019-12-4
venue: 'Journal of Chemical Information and Modeling'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Chen, S., Sun, Z., Lin, L., Liu, Z., Liu, X., Chong, Y., ... & Yang, Y. (2019). To improve protein sequence profile prediction through image captioning on pairwise residue distance map. Journal of chemical information and modeling, 60(1), 391-399.'
---
Protein sequence profile prediction aims to generate multiple sequences from structural information to advance the protein design. Protein sequence profile can be computationally predicted by energy-based or fragment-based methods. By integrating these methods with neural networks, our previous method, SPIN2, has achieved a sequence recovery rate of 34%. However, SPIN2 employed only one-dimensional (1D) structural properties that are not sufficient to represent three-dimensional (3D) structures. In this study, we represented 3D structures by 2D maps of pairwise residue distances and developed a new method (SPROF) to predict protein sequence profiles based on an image captioning learning frame. To our best knowledge, this is the first method to employ a 2D distance map for predicting protein properties. SPROF achieved 39.8% in sequence recovery of residues on the independent test set, representing a 5.2% improvement over SPIN2. We also found the sequence recovery increased with the number of their neighbored residues in 3D structural space, indicating that our method can effectively learn long-range information from the 2D distance map. Thus, such network architecture using a 2D distance map is expected to be useful for other 3D structure-based applications, such as binding site prediction, protein function prediction, and protein interaction prediction. The online server and the source code is available at http://biomed.nscc-gz.cn and https://github.com/biomed-AI/SPROF, respectively.
