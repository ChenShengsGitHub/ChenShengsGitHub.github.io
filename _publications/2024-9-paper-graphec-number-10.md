---
title: "Accurately predicting enzyme functions through geometric graph learning on ESMFold-predicted structures"
collection: publications
category: manuscripts
permalink: /publication/2024-9-paper-graphec-number-10
excerpt: 'Protein function prediction'
date: 2024-9-19
venue: 'Nature Communications'
paperurl: '/files/graphec.pdf'
citation: 'Song, Y., Yuan, Q., Chen, S., Zeng, Y., Zhao, H., & Yang, Y. (2024). Accurately predicting enzyme functions through geometric graph learning on ESMFold-predicted structures. Nature Communications, 15(1), 8180.'
---

Enzymes are crucial in numerous biological processes, with the Enzyme Commission (EC) number being a commonly used method for defining enzyme function. However, current EC number prediction technologies have not fully recognized the importance of enzyme active sites and structural characteristics. Here, we propose GraphEC, a geometric graph learning-based EC number predictor using the ESMFold-predicted structures and a pre-trained protein language model. Specifically, we first construct a model to predict the enzyme active sites, which is utilized to predict the EC number. The prediction is further improved through a label diffusion algorithm by incorporating homology information. In parallel, the optimum pH of enzymes is predicted to reflect the enzyme-catalyzed reactions. Experiments demonstrate the superior performance of our model in predicting active sites, EC numbers, and optimum pH compared to other state-of-the-art methods. Additional analysis reveals that GraphEC is capable of extracting functional information from protein structures, emphasizing the effectiveness of geometric graph learning. This technology can be used to identify unannotated enzyme functions, as well as to predict their active sites and optimum pH, with the potential to advance research in synthetic biology, genomics, and other fields.
