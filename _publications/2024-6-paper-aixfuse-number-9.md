---
title: "Structure-aware dual-target drug design through collaborative learning of pharmacophore combination and molecular simulation"
collection: publications
category: manuscripts
permalink: /publication/2024-6-paper-aixfuse-number-9
excerpt: 'Dual-target drug design'
date: 2024-6-13
venue: 'Chemical Science'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Chen, S., Xie, J., Ye, R., Xu, D. D., & Yang, Y. (2024). Structure-aware dual-target drug design through collaborative learning of pharmacophore combination and molecular simulation. Chemical Science, 15(27), 10366-10380.'
---

Dual-target drug design has gained significant attention in the treatment of complex diseases, such as cancers and autoimmune disorders. A widely employed design strategy is combining pharmacophores to leverage the knowledge of structure–activity relationships of both targets. Unfortunately, pharmacophore combination often struggles with long and expensive trial and error, because the protein pockets of the two targets impose complex structural constraints. In this study, we propose AIxFuse, a structure-aware dual-target drug design method that learns pharmacophore fusion patterns to satisfy the dual-target structural constraints simulated by molecular docking. AIxFuse employs two self-play reinforcement learning (RL) agents to learn pharmacophore selection and fusion by comprehensive feedback including dual-target molecular docking scores. Collaboratively, the molecular docking scores are learned by active learning (AL). Through collaborative RL and AL, AIxFuse learns to generate molecules with multiple desired properties. AIxFuse is shown to outperform state-of-the-art methods in generating dual-target drugs against glycogen synthase kinase-3 beta (GSK3β) and c-Jun N-terminal kinase 3 (JNK3). When applied to another task against retinoic acid receptor-related orphan receptor γ-t (RORγt) and dihydroorotate dehydrogenase (DHODH), AIxFuse exhibits consistent performance while compared methods suffer from performance drops, leading to a 5 times higher performance in success rate. Docking studies demonstrate that AIxFuse can generate molecules concurrently satisfying the binding mode required by both targets. Further free energy perturbation calculation indicates that the generated candidates have promising binding free energies against both targets.
