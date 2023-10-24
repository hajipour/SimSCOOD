# SimSCOOD: Systematic Analysis of Out-of-Distribution Generalization in Fine-tuned Source Code Models

This repository is the official implementation of [SimSCOOD: Systematic Analysis of Out-of-Distribution Generalization in Fine-tuned Source Code Models](https://arxiv.org/abs/2210.04802). 

## Code and Data
Under construction :construction_worker::construction:

## Abstract
Large code datasets have become increasingly accessible for pre-training source code models. However, for the fine-tuning phase, obtaining representative training data that fully covers the code distribution for specific downstream tasks remains challenging due to the task-specific nature and limited labeling resources. Moreover, fine-tuning pretrained models can result in forgetting previously acquired pre-training knowledge. These lead to out-of-distribution (OOD) generalization issues with unexpected model inference behaviors that have not been systematically studied yet.
In this paper, we contribute the first systematic approach that simulates various OOD scenarios along different dimensions of source code data properties and study the fine-tuned model behaviors in such scenarios. We investigate the behaviors of models under different fine-tuning methodologies, including full fine-tuning and Low-Rank Adaptation (LoRA) fine-tuning methods. Our comprehensive analysis, conducted on four state-of-the-art pretrained models and applied to two code generation tasks, exposes multiple failure modes attributed to OOD generalization issues. Additionally, our analysis uncovers that LoRA fine-tuning consistently exhibits significantly better OOD generalization performance than full fine-tuning across various scenarios.

## Citation

  ```
  @article{hajipour22simscood,
  title={SimSCOOD: Systematic Analysis of Out-of-Distribution Generalization in Fine-tuned Source Code Models},
  author={Hajipour, Hossein and Yu, Ning and Staicu, Cristian-Alexandru and Fritz, Mario},
  journal={arXiv preprint arXiv:2210.04802},
  year={2022}
}
  ```

