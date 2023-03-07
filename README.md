# Domain Randomization for Robust, Affordable and Effective Closed-loop Control of Soft Robots

[Preprint]() / [Website](https://andreaprotopapa.github.io/dr-soro/) / [Video](https://andreaprotopapa.github.io/dr-soro/)

##### Gabriele Tiboni, Andrea Protopapa, Tatiana Tommasi, Giuseppe Averta.

This repository contains the code for the paper "Domain Randomization for Robust, Affordable and Effective Closed-loop Control of Soft Robots".

*Abstract:* Soft robots are becoming extremely popular thanks to their intrinsic safety to contacts and adaptability. However, the potentially infinite number of Degrees of Freedom makes their modeling a daunting task, and in many cases only an approximated description is available. 
This challenge makes reinforcement learning (RL) based approaches inefficient when deployed on a realistic scenario, due to the large domain gap between models and the real platform. 
In this work, we demonstrate, for the first time, how Domain Randomization (DR) can solve this problem by enhancing RL policies with: i) a higher robustness w.r.t. environmental changes; ii) a higher affordability of learned policies when the target model differs significantly from the training model; iii) a higher effectiveness of the policy, which can even autonomously learn to exploit the environment to increase the robot capabilities (environmental constraints exploitation). 
Moreover, we introduce a novel algorithmic extension of previous adaptive domain randomization methods for the automatic inference of dynamics parameters for deformable objects.
We provide results on four different tasks and two soft robot designs, opening interesting perspectives for future research on Reinforcement Learning for closed-loop soft robot control. [Watch video](https://andreaprotopapa.github.io/dr-soro/)

<img src="https://www.gabrieletiboni.com/assets/online_vs_offline_adr_compact.png" style="width: 90%; max-width: 900px;" />

Our release is **under construction**, you can track its progress below:

- [ ] SOFA gym environments (TrunkReach, TrunkPush, TrunkLift)
- [ ] Code
	- [ ] RL training
	- [ ] DR compatibility
	- [ ] Reset-free DROPO


<!-- ## Cite us
If you use this repository, please consider citing
```
``` -->

