# Research-Group-Progress
Weekly discussion (https://uqz.zoom.us/j/7488132500)

## 2022-11-10
#### Zixin: 
- paper: **Cycle Self-Training for Domain Adaptation**
- link: [https://arxiv.org/abs/2103.03571](https://arxiv.org/abs/2103.03571)
- progress:

#### Ivan:


## 2022-11-3
#### Zixin: 
- paper: **Low-confidence Samples Matter for Domain Adaptation**
- Next week: Cycle selftraining for domain adaptation
- link: [https://arxiv.org/abs/2202.02802](https://arxiv.org/abs/2202.02802)
- progress: 
- [X] Adjust the learning rate to 0.0001
- [X] Change the schedular to CosineAnnealingWarmRestarts
- [X] Double-check the target adaptation code
- [X] Double-check the dataloader
- todolist: re-load model weights and see the finetuning performance? lodge pseudo label accuracy and validation scores to wandb; polyloss to cross entropy + negative cross entropy
- use sweeper to search the best lr; adam; for the first round



#### Ivan: 
- paper: 
- link:
- progress: 
- [ ] Self-train: ROS + multi-head (8/40, 12/48, 12/48 w/t ROS for self-train)
- [ ] Self-train: ROS + soft labeling + multi-head
- [ ] Self-train: Soft labeling + negtive objects 
- [X] Pre-train + Self-train: ST3D Baseline (ROS + memory bank + single head)
- Todo list: soft labeling (12/8) -> select a proper interval -> single head hard pseudo labeling as a baseline -> pareto

## 2022-10-27
#### Zixin: 
- paper: **Variational Model Perturbation for Source-Free Domain Adaptation**
- link: [https://arxiv.org/abs/2210.10378](https://arxiv.org/abs/2210.10378)
- progress: (1). ran the poly-loss adaptation w/o freeze encoder but performance is not good. (2). decide to adjust rl to larger one and change the schedular



#### Ivan: 
- paper:**PMAL: Open Set Recognition via Robust Prototype Mining**
- link: https://github.com/Luoyadan/Research-Group-Progress/issues/2#issue-1431203420
- progress: running experiments on (1) multi-head, (2) + ROS (3) soft labeling


