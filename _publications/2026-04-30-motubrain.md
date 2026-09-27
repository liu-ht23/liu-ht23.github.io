---
title: "Motubrain: An Advanced World Action Model for Robot Control"
collection: publications
category: preprints
permalink: /publication/2026-04-30-motubrain
excerpt: 'A world action model built on a unified video-action backbone with a three-stream Mixture-of-Transformers architecture. Haitian Liu is a core contributor to post-training and evaluation.'
date: 2026-04-30
venue: 'arXiv preprint'
venue_display: 'arXiv preprint, 2026'
authors: 'Motubrain Team &nbsp;(<b>Haitian Liu</b>: core contributor, post-training &amp; evaluation)'
video: /images/motubrain-demo.mp4
teaser: /images/motubrain-poster.jpg
paperurl: 'https://arxiv.org/abs/2604.27792'
project: 'https://www.genspi.com/en/motubrain'
code: 'https://github.com/shengshu-ai/Motubrain'
selected: true
selected_order: 2
citation: 'Motubrain Team (2026). &quot;Motubrain: An Advanced World Action Model for Robot Control.&quot; <i>arXiv preprint arXiv:2604.27792</i>.'
abstract: |
  Vision-Language-Action (VLA) models generalize semantically well but often lack fine-grained modeling of world dynamics. We present Motubrain, a unified World Action Model that jointly models video and action under a UniDiffuser formulation with a three-stream Mixture-of-Transformers architecture. A single model supports policy learning, world modeling, video generation, inverse dynamics, and joint video-action prediction, while scaling to heterogeneous multimodal data such as video-only, task-agnostic, and cross-embodiment robot data. Building on Motus, Motubrain further introduces unified multiview modeling, an independent text stream for stronger language-action coupling, a shared cross-embodiment action representation, and an efficient post-training and deployment recipe for long-horizon real-world control. Our inference stack combines step reduction, compilation, FP8 quantization, DiT caching, V2A-style action-only inference, and real-time chunked closed-loop execution, achieving over 50x speedup over a naive baseline and up to 11 Hz inference. Experimentally, Motubrain achieves 95.8% and 96.1% average success on RoboTwin 2.0 under clean and randomized settings, respectively, attains the strongest reported EWMScore in our WorldArena comparison, and adapts to new humanoid embodiments with only 50–100 trajectories. These results show that unified world action models can scale in generality, predictive accuracy, and real-world deployability.
bibtex: |
  @misc{motubrainteam2026motubrainadvancedworldaction,
        title={Motubrain: An Advanced World Action Model for Robot Control},
        author={Motubrain Team and Chendong Xiang and Fan Bao and Haitian Liu and Hengkai Tan and Hongzhe Bi and James Li and Jiabao Liu and Jingrui Pang and Kiro Jing and Louis Liu and Mengchen Cai and Rongxu Cui and Ruowen Zhao and Runqing Wang and Shuhe Huang and Yao Feng and Yinze Rong and Zeyuan Wang and Jun Zhu},
        year={2026},
        eprint={2604.27792},
        archivePrefix={arXiv},
        primaryClass={cs.RO},
        url={https://arxiv.org/abs/2604.27792},
  }
---
