# Awesome-BFM-Papers

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/yuanmingqi/awesome-bfm-papers) 

A curated list of behavior(al) foundation model (BFM) papers, articles, tutorials, slides, and projects.


# What is the Behavior Foundation Model?

<div align=center>
<br>
<img src='./assets/preface.png' style="width: 70%">
<br>
</div>

A behavior foundation model learns **broad behavior priors** from **large-scale and diverse behavior data**, which can then be conveniently adapted to a wide range of downstream tasks.

# Paper List

## Pre-training

### Forward-backward Representation Learning

#### 2025

- Zero-shot Whole-body Humanoid Control via Behavioral Foundation Models | **ICLR** | [[Paper]()] | [[Code]()]  |

#### 2024
- Finer Behavioral Foundation Models via Auto-regressive Features and Advantage Weighting | **arXiv** | [[Paper](https://arxiv.org/abs/2412.04368)] | [[Code]()]  |

#### 2023
- Fast Imitation via Behavior Foundation Models | **NeurIPS** | [[Paper]()] | [[Code]()]  |


### Goal-conditioned Learning
#### 2025
- HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots  | **ICRA** | [[Paper]()] | [[Code]()] |  
- InterMimic: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions  | **CVPR** | [[Paper]()] | [[Code]()] |
- ModSkill: Physical Character Skill Modularization  | **arXiv** | [[Paper](https://arxiv.org/abs/2502.14140)] | [[Code]()] |

#### 2024
- MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting | **TOG** | [[Paper]()] | [[Code]()] |
- MoConVQ: Unified Physics-Based Motion Control via Scalable Discrete Representations  | **TOG** | [[Paper]()] | [[Code]()] | 
- CALM: Conditional Adversarial Latent Models for Directable Virtual Characters  | **SIGGRAPH** | [[Paper]()] | [[Code]()]  |
- CASE: Learning Conditional Adversarial Skill Embeddings for Physics-Based Characters  | **SIGGRAPH Asia** | [[Paper]()] | [[Code]()]  |
- PHC: Perpetual Humanoid Control for Real-Time Simulated Avatars  | **ICCV** | [[Paper]()] | [[Code]()]  |

#### 2023
- TeamPlay: From Motor Control to Team Play in Simulated Humanoid Football | **Science Robotics** | [[Paper]()] | [[Code]()]  |

- MTM: Masked Trajectory Models for Prediction, Representation, and Control| **ICML** | [[Paper]()] | [[Code]()]  |

#### 2022
- ASE: Large-scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters  | **TOG** | [[Paper]()] | [[Code]()]  |


### Intrinsic Reward-driven Learning

#### 2021
- Active Pretraining with Successor Features | **ICML** | [[Paper](https://arxiv.org/abs/2106.14910)] | [[Code]()]  |
- Reinforcement Learning with Prototypical Representations | **ICML** | [[Paper](https://arxiv.org/abs/2103.01975)] | [[Code]()]  |
#### 2020
- State Entropy Maximization with Random Encoders for Efficient Exploration | **ICML** | [[Paper](https://arxiv.org/abs/2102.05561)] | [[Code]()]  |

#### 2019
- Exploration by Random Network Distillation | **ICLR** | [[Paper](https://arxiv.org/abs/1810.12894)] | [[Code]()]  
- Diversity is All You Need: Learning Skills without a Reward Function | **ICLR** | [[Paper](https://arxiv.org/abs/1802.06070)] | [[Code]()]  |

## Adaptation
### Fine-tuning Techniques

#### 2025

- Task tokens: A flexible approach to adapting behavior foundation models | **arXiv** | [[Paper]()] | [[Code]()] |
- Zero-shot adaptation of behavioral foundation models to unseen dynamics | **arXiv** | [[Paper]()] | [[Code]()] |
- Fast adaptation with behavioral foundation models  | **CoRL** | [[Paper]()] | [[Code]()] |


### Towards Hierarchical Control

#### 2025
- Leverb: Humanoid whole-body control with latent vision-language instruction | **arXiv** | [[Paper]()] | [[Code]()] |
- Langwbc: Language-directed humanoid whole-body control via end-to-end learning | **arXiv** | [[Paper]()] | [[Code]()] |
- Tokenhsi: Unified synthesis of physical human-scene interactions through task tokenization | **arXiv** | [[Paper]()] | [[Code]()] |
- Closd: Closing the loop between simulation and diffusion for multi-task character control | **ICLR** | [[Paper]()] | [[Code]()] |

#### 2024

- Unified human-scene interaction via prompted chain-of-contacts | **ICLR** | [[Paper]()] | [[Code]()] |
- UniPhys: Unified planner and controller with diffusion for flexible physics-based character control  | **arXiv** | [[Paper]()] | [[Code]()] |



# Cite Us
If this project helped your work, please cite us by
``` bib
@article{yuan2025bfm,
    title={Behavior Foundation Model: Towards Next-Generation Whole-Body Control System of Humanoid Robots},
    author={Yuan, Mingqi and Yu, Tao and Ge, Wenqi and Yao, Xiuyong and Li, Dapeng and Wang, Huijiang and Chen, Jiayu and Jin, Xin and Li, Bo and Chen, Hua and Zhang, Wei and Zeng, Wenjun},
    journal={arXiv preprint.},
    year={2025}
}
```
