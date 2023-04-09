---
title: "A Study on Criteria for Training Collaborator Selection in Federated Learning"
collection: publications
permalink: /publication/2022-07-15-Federated-learning-number-1
excerpt: ''
date: 2022-07-15
venue: 'MICCAI BrainLes 2021'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-09002-8_41'
citation: 'Shambhat, V., Maurya, A., Danannavar, S.S., Kalla, R., Anand, V.K., Krishnamurthi, G. (2022). A Study on Criteria for Training Collaborator Selection in Federated Learning. In: Crimi, A., Bakas, S. (eds) Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries. BrainLes 2021. Lecture Notes in Computer Science, vol 12963. Springer, Cham. https://doi.org/10.1007/978-3-031-09002-8_41'
---
Federated learning is an important aspect of enabling the deployment of deep learning. It addresses data privacy and security concerns by decentralizing data. In a federated learning setup, models are trained locally in the data center called collaborators, and the model weights are aggregated by a central server. We present our work towards the efficient aggregation of trained model weights from multiple institutions which is Task 1 in the federated learning challenge (FeTS 2021). We devised a scoring system for selecting appropriate collaborators every round and aggregating their weight by simple averaging. We calculate the score based on the sensitivity, dice coefficient, and Hausdorff distance of each segmentation class on validation data from every collaborator. The best collaborators are chosen serially based on the scores with higher scores indicating better performing networks. Our approach gave mean dice score of 0.58 ± 0.259 & 0.639 ± 0.176 & 0.55 ± 0.201 on Enhancing Tumor, Whole Tumor and Tumor Core respectively.

