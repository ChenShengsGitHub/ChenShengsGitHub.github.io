---
title: "DiffDec: Structure-Aware Scaffold Decoration with an End-to-End Diffusion Model"
collection: publications
category: manuscripts
permalink: /publication/2024-1-paper-diffdec-number-8
excerpt: 'Pocket-conditioned molecular generation.'
date: 2024-1-24
venue: 'Journal of Chemical Information and Modeling'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Xie, J., Chen, S., Lei, J., & Yang, Y. (2024). DiffDec: structure-aware scaffold decoration with an end-to-end diffusion model. Journal of Chemical Information and Modeling, 64(7), 2554-2564.'
---

In molecular optimization, one popular way is R-group decoration on molecular scaffolds, and many efforts have been made to generate R-groups based on deep generative models. However, these methods mostly use information on known binding ligands, without fully utilizing target structure information. In this study, we proposed a new method, DiffDec, to involve 3D pocket constraints by a modified diffusion technique for optimizing molecules through molecular scaffold decoration. For end-to-end generation of R-groups with different sizes, we designed a novel fake atom mechanism. DiffDec was shown to be able to generate structure-aware R-groups with realistic geometric substructures by the analysis of bond angles and dihedral angles and simultaneously generate multiple R-groups for one scaffold on different growth anchors. The growth anchors could be provided by users or automatically determined by our model. DiffDec achieved R-group recovery rates of 69.67% and 45.34% in the single and multiple R-group decoration tasks, respectively, and these values were significantly higher than competing methods (37.33% and 26.85%). According to the molecular docking study, our decorated molecules obtained a better average binding affinity than baseline methods. The docking pose analysis revealed that DiffDec could decorate scaffolds with R-groups that exhibited improved binding affinities and more favorable interactions with the pocket. These results demonstrated the potential and applicability of DiffDec in real-world scaffold decoration for molecular optimization.
