---
title: "SEGEM: A fast and accurate automated protein backbone structure modeling method for cryo-EM"
collection: publications
category: conferences
permalink: /publication/2021-12-paper-segem-number-3
excerpt: 'cryo-EM protein structure modeling'
date: 2021-12-9
venue: 'IEEE BIBM 2021'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Chen, S., Zhang, S., Li, X., Liu, Y., & Yang, Y. (2021, December). SEGEM: A fast and accurate automated protein backbone structure modeling method for cryo-EM. In 2021 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 24-31). IEEE.'
---

Cryo-electron microscopy (cryo-EM) technique has been widely used in protein structure determination, whereas it remains a challenge to automatically build accurate protein backbone structure from cryo-EM density map. A typical pipeline to automatically build a structure model from cryo-EM map is to first predict \mathrm{C}\alpha sites and then assign them to protein sequence, which is a typical combinatorial optimization task of extremely high computational complexity. Here we propose SEGEM, a fast and accurate automated protein backbone structure modeling method for cryo-EM. We employed 3D Convolutional Neural Networks to predict \mathrm{C}\alpha sites with their amino acid types from cryo-EM, and developed a highly parallel pipeline to assign \mathrm{C}\alpha sites with their predicted amino acid types to protein sequence. We tested SEGEM on three benchmark datasets where it significantly outperformed several state-of-the-art prediction methods including MAINMAST, C-CNN and DeepTracer. In our method plus version SEGEM++, we combined SEGEM with the protein structure prediction algorithm AlphaFold2. SEGEM++is capable to identify whether AlphaFold2 folds a good structure, and rectify the incorrectly folded region through protein threading on cryo-EM map. In our curated dataset of hard targets where AlphaFold2 predicted structures obtained an average RMSD of 7. 87A and GDT-TS score of 0.652 when superimposed to the native structure, SEGEM++ achieved a significantly better RMSD of 2.46A and 0.676 GDT-TS score on average. Furthermore, with our highly parallel pipeline on 30 cores CPU, both SEGEM and SEGEM++ finished structure modeling within 10 minutes on average in our test datasets, indicating their potential in high throughout automated accurate backbone structure modeling for cryo-EM.
