# Awesome-BFM-Papers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/yuanmingqi/awesome-bfm-papers) <a href="https://arxiv.org/pdf/2506.20487"><img src="https://img.shields.io/badge/Paper-arXiv-b31b1b" alt="Paper"></a> 

A curated list of behavior(al) foundation model (BFM) papers, articles, tutorials, slides, and projects.

# Table of Contents
- [Awesome-BFM-Papers](#awesome-bfm-papers)
- [Table of Contents](#table-of-contents)
- [What is the Behavior Foundation Model?](#what-is-the-behavior-foundation-model)
- [Paper List](#paper-list)
  - [Pre-training](#pre-training)
    - [Forward-backward Representation Learning](#forward-backward-representation-learning)
    - [Goal-conditioned Learning](#goal-conditioned-learning)
    - [Intrinsic Reward-driven Learning](#intrinsic-reward-driven-learning)
  - [Adaptation](#adaptation)
    - [Fine-tuning Techniques](#fine-tuning-techniques)
    - [Towards Hierarchical Control](#towards-hierarchical-control)
- [Cite Us](#cite-us)


# What is the Behavior Foundation Model?

<div align=center>
<br>
<img src='./assets/preface.png' style="width: 90%">
<br>
</div>

A behavior foundation model learns **broad behavior priors** from **large-scale and diverse behavior data**, which can then be conveniently adapted to a wide range of downstream tasks.

# Paper List

## Pre-training

### Forward-backward Representation Learning

| 📅Year 	|   🗃️Archive  	|                                          🔤Title                                         	|                   📜Paper                  	|   🖥️Code  	|
|:-----:	|:-----------:	|:---------------------------------------------------------------------------------------:	|:-----------------------------------------:	|:--------:	|
|  2025 	|   **ICLR**  	|          Zero-shot Whole-body Humanoid Control via Behavioral Foundation Models         	|                 [Paper](https://arxiv.org/abs/2504.11054)                 	| [Code](https://github.com/facebookresearch/metamotivo) 	|
|  2024 	|  **arXiv**  	| Finer Behavioral Foundation Models via Auto-regressive Features and Advantage Weighting 	| [Paper](https://arxiv.org/abs/2412.04368) 	| N/A 	|
|  2024 	| **NeurIPS** 	|                      Fast Imitation via Behavior Foundation Models                      	|                 [Paper](https://openreview.net/pdf?id=qnWtw3l0jb)                 	| N/A 	|

### Goal-conditioned Learning


| 📅Year 	|       🗃️Archive       	|                                            🔤Title                                            	|                   📜Paper                  	|   🖥️Code  	|
|:-----:	|:--------------------:	|:--------------------------------------------------------------------------------------------:	|:-----------------------------------------:	|:--------:	|
|  2025 	|       **ICRA**       	|               HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots              	|                 [Paper](https://arxiv.org/abs/2410.21229)                 	| [Code](https://github.com/NVlabs/HOVER/) 	|
|  2025 	|       **CVPR**       	| InterMimic: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions 	|                 [Paper](https://arxiv.org/abs/2502.20390)                 	| [Code](https://github.com/Sirui-Xu/InterMimic) 	|
|  2025 	|       **arXiv**      	|                       ModSkill: Physical Character Skill Modularization                      	| [Paper](https://arxiv.org/abs/2502.14140) 	| [Code]() 	|
|  2024 	|        **TOG**       	|     MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting    	|                 [Paper](https://research.nvidia.com/labs/par/maskedmimic/assets/SIGGRAPHAsia2024_MaskedMimic.pdf)                 	| [Code](https://github.com/NVlabs/ProtoMotions) 	|
|  2023 	|        **TOG**       	|      MoConVQ: Unified Physics-Based Motion Control via Scalable Discrete Representations     	|                 [Paper](https://arxiv.org/pdf/2310.10198)                 	| N/A 	|
|  2024 	|     **SIGGRAPH**     	|         CALM: Conditional Adversarial Latent Models for Directable Virtual Characters        	|                 [Paper](https://research.nvidia.com/labs/par/calm/assets/SIGGRAPH2023_CALM.pdf)                 	| [Code](https://github.com/NVlabs/CALM) 	|
|  2023 	|   **SIGGRAPH Asia**  	|     CASE: Learning Conditional Adversarial Skill Embeddings for Physics-Based Characters     	|                 [Paper](https://arxiv.org/abs/2309.11351)                 	| [Code](https://github.com/Frank-ZY-Dou/CASE) 	|
|  2023 	|       **ICCV**       	|                PHC: Perpetual Humanoid Control for Real-Time Simulated Avatars               	|                 [Paper](https://arxiv.org/abs/2305.06456)                 	| [Code](https://github.com/ZhengyiLuo/PHC) 	|
|  2021 	| **Science Robotics** 	|           TeamPlay: From Motor Control to Team Play in Simulated Humanoid Football           	|                 [Paper](https://arxiv.org/abs/2105.12196)                 	| N/A	|
|  2023 	|       **ICML**       	|           MTM: Masked Trajectory Models for Prediction, Representation, and Control          	|                 [Paper](https://arxiv.org/abs/2305.02968)                 	| [Code](https://github.com/facebookresearch/mtm) 	|
|  2022 	|        **TOG**       	|  ASE: Large-scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters  	|                 [Paper](https://arxiv.org/abs/2205.01906)                 	| [Code](https://github.com/nv-tlabs/ASE) 	|


### Intrinsic Reward-driven Learning

| 📅Year 	| 🗃️Archive 	|                                   🔤Title                                  	|                   📜Paper                  	|   🖥️Code  	|
|:-----:	|:--------:	|:-------------------------------------------------------------------------:	|:-----------------------------------------:	|:--------:	|
|  2021 	| **ICML** 	|                 Active Pretraining with Successor Features                	| [Paper](https://arxiv.org/abs/2106.14910) 	| N/A 	|
|  2021 	| **ICML** 	|          Reinforcement Learning with Prototypical Representations         	| [Paper](https://arxiv.org/abs/2103.01975) 	| [Code](https://github.com/denisyarats/proto) 	|
|  2020 	| **ICML** 	| State Entropy Maximization with Random Encoders for Efficient Exploration 	| [Paper](https://arxiv.org/abs/2102.05561) 	| [Code](https://github.com/younggyoseo/RE3) 	|
|  2019 	| **ICLR** 	|                 Exploration by Random Network Distillation                	| [Paper](https://arxiv.org/abs/1810.12894) 	| [Code](https://github.com/openai/random-network-distillation) 	|
|  2018 	| **ICLR** 	|    Diversity is All You Need: Learning Skills without a Reward Function   	| [Paper](https://arxiv.org/abs/1802.06070) 	| [Code](https://github.com/alirezakazemipour/DIAYN-PyTorch) 	|

## Adaptation
### Fine-tuning Techniques


| 📅Year 	|  🗃️Archive 	|                                  🔤Title                                 	|   📜Paper  	|   🖥️Code  	|
|:-----:	|:---------:	|:-----------------------------------------------------------------------:	|:---------:	|:--------:	|
|  2025 	| **arXiv** 	| Task tokens: A flexible approach to adapting behavior foundation models 	| [Paper](https://arxiv.org/abs/2503.22886) 	| N/A	|
|  2025 	| **arXiv** 	| Zero-shot adaptation of behavioral foundation models to unseen dynamics 	| [Paper](https://arxiv.org/abs/2505.13150) 	| N/A	|
|  2025 	|  **CoRL** 	|            Fast adaptation with behavioral foundation models            	| [Paper](https://arxiv.org/abs/2504.07896) 	| N/A 	|

### Towards Hierarchical Control

| 📅Year 	|  🗃️Archive 	|                                                🔤Title                                               	|   📜Paper  	|   🖥️Code  	|
|:-----:	|:---------:	|:---------------------------------------------------------------------------------------------------:	|:---------:	|:--------:	|
|  2025 	| **arXiv** 	|             Leverb: Humanoid whole-body control with latent vision-language instruction             	| [Paper](https://arxiv.org/abs/2506.13751) 	| N/A 	|
|  2025 	| **arXiv** 	|            Langwbc: Language-directed humanoid whole-body control via end-to-end learning           	| [Paper](https://arxiv.org/abs/2504.21738) 	| N/A 	|
|  2025 	| **CVPR** 	|      Tokenhsi: Unified synthesis of physical human-scene interactions through task tokenization     	| [Paper](https://arxiv.org/abs/2503.19901) 	| [Code](https://github.com/liangpan99/TokenHSI) 	|
|  2024 	|  **ICLR** 	|      Closd: Closing the loop between simulation and diffusion for multi-task character control      	| [Paper](https://arxiv.org/abs/2410.03441) 	| [Code](https://github.com/GuyTevet/CLoSD) 	|
|  2023 	|  **ICLR** 	|                    Unified human-scene interaction via prompted chain-of-contacts                   	| [Paper](https://arxiv.org/abs/2309.07918) 	| [Code](https://github.com/OpenRobotLab/UniHSI) 	|
|  2024 	| **arXiv** 	| UniPhys: Unified planner and controller with diffusion for flexible physics-based character control 	| [Paper](https://arxiv.org/abs/2504.12540) 	| [Code](https://wuyan01.github.io/uniphys-project/) 	|


# Cite Us
If this project helped your work, please cite us by
``` bib
@article{yuan2025bfm,
    title={Behavior Foundation Model: Towards Next-Generation Whole-Body Control System of Humanoid Robots},
    author={Yuan, Mingqi and Yu, Tao and Ge, Wenqi and Yao, Xiuyong and Li, Dapeng and Wang, Huijiang and Chen, Jiayu and Jin, Xin and Li, Bo and Chen, Hua and Zhang, Wei and Zeng, Wenjun},
    journal={arXiv preprint arXiv:2506.20487},
    year={2025}
}
```
