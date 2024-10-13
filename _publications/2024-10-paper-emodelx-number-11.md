---
title: "Protein complex structure modeling by cross-modal alignment between cryo-EM maps and protein sequences"
collection: publications
category: manuscripts
permalink: /publication/2024-10-paper-emodelx-number-11
excerpt: 'Protein structure prediction'
date: 2024-10-11
venue: 'Nature Communications'
paperurl: '/files/emodelx.pdf'
citation: 'Chen, S., Zhang, S., Fang, X. et al. Protein complex structure modeling by cross-modal alignment between cryo-EM maps and protein sequences. Nat Commun 15, 8808 (2024). https://doi.org/10.1038/s41467-024-53116-5'
---

Cryo-electron microscopy (cryo-EM) technique is widely used for protein structure determination. Current automatic cryo-EM protein complex modeling methods mostly rely on prior chain separation. However, chain separation without sequence guidance often suffers from errors caused by cross-chain interaction or noise densities, which would accumulate and mislead the subsequent steps. Here, we present EModelX, a fully automated cryo-EM protein complex structure modeling method, which achieves sequence-guiding modeling through cross-modal alignments between cryo-EM maps and protein sequences. EModelX first employs multi-task deep learning to predict Cα atoms, backbone atoms, and amino acid types from cryo-EM maps, which is subsequently used to sample Cα traces with amino acid profiles. The profiles are then aligned with protein sequences to obtain initial structural models, which yielded an average RMSD of 1.17 Å in our test set, approaching atomic-level precision in recovering PDB-deposited structures. After filling unmodeled gaps through sequence-guiding Cα threading, the final models achieved an average TM-score of 0.808, outperforming the state-of-the-art method. The further combination with AlphaFold can improve the average TM-score to 0.911. Analyzes conducted by comparing some EModelX-built models and PDB structures highlight its potential to improve PDB structures. EModelX is accessible at https://bio-web1.nscc-gz.cn/app/EModelX.
