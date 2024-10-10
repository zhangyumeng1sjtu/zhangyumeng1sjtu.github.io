---
title: "Unbiased curriculum learning enhanced global-local graph neural network for protein thermodynamic stability prediction"
collection: publications
category: articles
permalink: /publication/2023-10-07-unbiased-curriculum-learning
excerpt: ''
date: 2023-10-07
venue: 'Bioinformatics'
slidesurl: ''
paperurl: 'http://zhangyumeng1sjtu.github.io/files/btad589.pdf'
citation: 'H Gong†, <b>Y Zhang†</b>, C Dong, Y Wang, G Chen, B Liang, H Li, L Liu, J Xu & G Li. (2023). Unbiased curriculum learning enhanced global-local graph neural network for protein thermodynamic stability prediction. <i>Bioinformatics</i>, 39(10), btad589.'
---
Proteins play crucial roles in biological processes, with their functions being closely tied to thermodynamic stability. However, measuring stability changes upon point mutations of amino acid residues using physical methods can be time-consuming. In recent years, several computational methods for protein thermodynamic stability prediction (PTSP) based on deep learning have emerged. Nevertheless, these approaches either overlook the natural topology of protein structures or neglect the inherent noisy samples resulting from theoretical calculation or experimental errors. We propose a novel Global-Local Graph Neural Network powered by Unbiased Curriculum Learning for the PTSP task. Our method first builds a Siamese graph neural network to extract protein features before and after mutation. Since the graph’s topological changes stem from local node mutations, we design a local feature transformation module to make the model focus on the mutated site. To address model bias caused by noisy samples, which represent unavoidable errors from physical experiments, we introduce an unbiased curriculum learning method. This approach effectively identifies and re-weights noisy samples during the training process. Extensive experiments demonstrate that our proposed method outperforms advanced protein stability prediction methods, and surpasses state-of-the-art learning methods for regression prediction tasks.
