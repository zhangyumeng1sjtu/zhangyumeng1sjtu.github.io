---
title: "Supervised contrastive learning enhances MHC-II peptide binding affinity prediction"
collection: publications
category: preprints
permalink: /publication/2023-12-21-supervised-contrastive-learning
excerpt: ''
date: 2023-12-21
venue: 'bioRxiv'
slidesurl: ''
paperurl: 'http://zhangyumeng1sjtu.github.io/files/2023.12.21.572942v3.full.pdf'
citation: 'LC Shen, L Yan, Z Liu, <b>Y Zhang</b>, Z Wang, Y Guo, J Rossjohn, J Song & DJ Yu. (2023) ConBoTNet: supervised contrastive learning enhances MHC-II peptide binding affinity prediction. <i>bioRxiv</i>, 2023.12.21.572942.'
---
Accurate prediction of major histocompatibility complex (MHC)-peptide binding affinity can improve our understanding of cellular immune responses and guide personalized immunotherapies. Nevertheless, the existing deep learning-based approaches for predicting MHC-II peptide interactions fall short of satisfactory performance and offer restricted model interpretability. In this study, we propose a novel deep neural network, termed ConBoTNet, to address the above issues by introducing the designed supervised contrastive learning and bottleneck transformer extractors. Specifically, the supervised contrastive learning pre-training enhances the model’s representative and generalizable capabilities on MHC-II peptides by pulling positive pairs closer and pushing negative pairs further in the feature space, while the bottleneck transformer module focuses on MHC-II peptide interactions to precisely identify binding cores and anchor positions in an unsupervised manner. Extensive experiments on benchmark datasets under 5-fold cross-validation, leave-one-molecule-out validation, independent testing, and binding core prediction settings highlighted the superiority of our proposed ConBoTNet over current state-of-the-art methods. Data distribution analysis in the latent feature space demonstrated that supervised contrastive learning can aggregate MHC-II-peptide samples with similar affinity labels and learn common features of similar affinity. Additionally, we interpreted the trained neural network by associating the attention weights with peptides and innovatively find both well-established and potential peptide motifs. This work not only introduces an innovative tool for accurately predicting MHC-II peptide affinity, but also provides new insights into a new paradigm for modeling essential biological interactions, advancing data-driven discovery in biomedicine.
