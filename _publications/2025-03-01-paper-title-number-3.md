---
title: "EfficientMorph: Parameter-Efficient Transformer-Based Architecture for 3D Image Registration"
collection: publications
permalink: /publication/2025-03-01-paper-title-number-3
excerpt: 'Transformers have emerged as the state-of-the-art architecture in medical image registration, outperforming convolutional neural networks (CNNs) by addressing their limited receptive fields and overcoming gradient instability in deeper models. Despite their success, transformer-based models require substantial resources for training, including data, memory, and computational power, which may restrict their applicability for end users with limited resources. In particular, existing transformer-based 3D image registration architectures face two critical gaps that challenge their efficiency and effectiveness. Firstly, although window-based attention mechanisms reduce the quadratic complexity of full attention by focusing on local regions, they often struggle to effectively integrate both local and global information. Secondly, the granularity of tokenization, a crucial factor in registration accuracy, presents a performance trade-off: smaller voxel-size tokens enhance detail capture but come with increased computational complexity, higher memory usage, and a greater risk of overfitting. We present \name, a transformer-based architecture for unsupervised 3D image registration that balances local and global attention in 3D volumes through a plane-based attention mechanism and employs a Hi-Res tokenization strategy with merging operations, thus capturing finer details without compromising computational efficiency. Notably, \name sets a new benchmark for performance on the OASIS dataset with 16-27x fewer parameters.'
date: 2025-03-01
venue: 'WACV 2025: IEEE/CVF Winter Conference on Applications of Computer Vision'
paperurl: 'https://arxiv.org/abs/2403.11026'
citation: 'Aziz, Abu Zahid Bin, Mokshagna Sai Teja Karanam, Tushar Kataria, and Shireen Y. Elhabian. "EfficientMorph: Parameter-Efficient Transformer-Based Architecture for 3D Image Registration." arXiv preprint arXiv:2403.11026 (2024).'
---
[Download paper here](https://arxiv.org/abs/2403.11026)

<!-- Recommended citation: Your Name, You. (20). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->