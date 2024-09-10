---
title: "Predicting drug–protein interaction using quasi-visual question answering system"
collection: publications
category: manuscripts
permalink: /publication/2020-2-paper-drugvqa-number-2
excerpt: 'Identifying drug–protein interactions'
date: 2020-2-14
venue: 'Nature Machine Intelligence'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Zheng, S., Li, Y., Chen, S., Xu, J., & Yang, Y. (2020). Predicting drug–protein interaction using quasi-visual question answering system. Nature Machine Intelligence, 2(2), 134-140.'
---
Identifying novel drug–protein interactions is crucial for drug discovery. For this purpose, many machine learning-based methods have been developed based on drug descriptors and one-dimensional protein sequences. However, protein sequences cannot accurately reflect the interactions in three-dimensional space. However, direct input of three-dimensional structure is of low efficiency due to the sparse three-dimensional matrix, and is also prevented by the limited number of co-crystal structures available for training. Here we propose an end-to-end deep learning framework to predict the interactions by representing proteins with a two-dimensional distance map from monomer structures (Image) and drugs with molecular linear notation (String), following the visual question answering mode. For efficient training of the system, we introduce a dynamic attentive convolutional neural network to learn fixed-size representations from the variable-length distance maps and a self-attentional sequential model to automatically extract semantic features from the linear notations. Extensive experiments demonstrate that our model obtains competitive performance against state-of-the-art baselines on the directory of useful decoys, enhanced (DUD-E), human and BindingDB benchmark datasets. Further attention visualization provides biological interpretation to depict highlighted regions of both protein and drug molecules.
