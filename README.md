<h1 align="center">
  AUTONOMOUS LUNAR LANDER<br />Deep Reinforcement Learning for Control Application
</h1>
<h2 align="center">
  Master's degree thesis in Computer Science Engineering<br /> in collaboration with AIKO company
</h2>

### Abstract

This thesis aims to analyze the application of a Deep Reinforcement Learning algorithm to a case study in the field of control. The algorithm chosen is the Proximal Policy Optimization, which in recent years has reached the state-of-the-art in various fields of application, the control problem taken under consideration is the powered descent phase of a lander and the subsequent pinpoint landing, the Apollo 11 mission was taken as guideline for some aspects in the creation of the model. The framework Unity was used for the modeling and simulation part, the library ML-Agents for the management of the DRL part. The implementation of the fidelity of the model has been undertaken with an incremental approach, this has allowed to understand and face gradually the criticalities since the increasing of the physical complexity of the problem grows notably the difficulty in reaching the desired result. The main problems faced and analyzed deal with the interaction between the physical model, the reward function through which the agent learns and the numerous hyperparameters that manage the PPO algorithm. The main features implemented in the first three scenarios carried out are realistic and randomized initial conditions, realistic landing constraints, limited fuel and mass loss caused by its consumption. In these three scenarios, the movement constraint in only three degrees-of-freedom is present as the main simplification; agents with success rates higher than 90% were obtained. In the fourth and last scenario the lander has the possibility to move in six degrees-of-freedom, here the best policy obtained has about 90% of accuracy, the conditions in which the lander fails are half of mild severity and half disastrous. Analyses were also conducted on the inference phase affected by observation noise or physical alterations. The major contribution of this work is considered to be the analysis of the hyperparameters tuning of the PPO algorithm and its benchmarks, the complex structuring of the reward function combined with strategies applied during training that have determined its effectiveness, all related to different and comparable physical conditions. Overall, the results achieved are considered satisfactory, may represent a guideline to implement this methodology in other similar applications, or to continue the development of this case study.

<p align="center">
<a href="https://www.youtube.com/watch?v=g2a_b1DM224" target="_blank"><img src="http://img.youtube.com/vi/g2a_b1DM224/0.jpg" 
alt="Video" width="600" height="450" border="10" /></a>
</p>
