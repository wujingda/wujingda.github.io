---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am currently a Postdoc researcher at the Hong Kong Polytechnic University. I received my Ph.D. degree from Nanyang Technological University (NTU).

I focus on the intersection between reinforcement learning (RL) and autonomous vehicles. My study aims to harness human intelligence to optimize the training cost and performance of reinforcement learning algorithms. In particular, my research points include behavior planning of autonomous vehicles and energy management of electrified vehicles. I have published more than 30 papers in top journals and conferences.


# 🔥 News
- *2022.09*: &nbsp;🎉🎉 I will give a talk at the IEEE ITSC 2023 Workshop with the theme of human-guided reinforcement learning (24 September 2023 @ Bilbao, Bizkaia, Spain).
- *2022.09*: &nbsp;🎉🎉 Our paper on efficient reinforcement learning through preference-guided stochastic exploration has been accepted by IEEE Transactions on Neural Networks and Learning Systems (TNNLS)!
- *2022.08*: &nbsp;🎉🎉 Our team won the 2nd place award in Track 1, IEEE ITSS Student Competition in Pedestrian Behavior Prediction! We will give a talk at the IEEE ITSC 2023 Workshop.
- *2022.07*: &nbsp;🎉🎉 Our papers on predictive decision-making/planning have been accepted by the International Conference on Intelligent Transportation Systems (ITSC)!
- *2022.06*: &nbsp;🎉🎉 Our paper on human-guided reinforcement learning for autonomous navigation has been accepted by IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)!
- *2022.06*: &nbsp;🎉🎉 Our paper on differentiable integrated prediction and planning has been accepted by IEEE Transactions on Neural Networks and Learning Systems (TNNLS)!
- *2022.05*: &nbsp;🎉🎉 Our paper on driver cognitive workload recognition has been accepted by IEEE Transactions on Industrial Electronics (TIE)!
- *2022.04*: &nbsp;🎉🎉 Our paper on energy-efficient behavioral planning of autonomous vehicles has been accepted by IEEE Transactions on Transportation Electrification (TTE)!
- *2022.03*: &nbsp;🎉🎉 Our paper on combining conditional motion prediction, inverse RL, and behavior planning has been accepted by IEEE Transactions on Intelligent Transportation Systems (TITS)!
- *2022.12*: &nbsp;🎉🎉 Our team won the 2nd Place in the Algorithm Track at Aliyun "Future Car" Smart Scenario Innovation Challenge [official site](https://tianchi.aliyun.com/competition/entrance/531996/rankingList).
- *2022.12*: &nbsp;🎉🎉 Our team won the Most Innovative Award and 3rd Place in both Track 1 and Track 2 at NeurIPS Driving SMARTS Competition! Check out our presentation on predictive decision-making at the [official competition site](https://smarts-project.github.io/).
- *2022.07*: &nbsp;🎉🎉 I was certified in the 2022 Imperial-TUM-NTU Global Fellows Programme: The role of robotics in well-being and the workplace!
- *2022.06*: &nbsp;🎉🎉 Two papers on behavioral decision-making based on safe RL and graph RL have been accepted by ITSC 2022!
- *2022.06*: &nbsp;🎉🎉 Our paper on RL with prioritized human guidance replay has been accepted by IEEE Transactions on Neural Networks and Learning Systems (TNNLS)!
- *2022.05*: &nbsp;🎉🎉 Our paper on human-in-the-loop RL has been accepted by Engineering, the official journal of the Chinese Academy of Engineering!
- *2022.04*: &nbsp;🎉🎉 Our paper on RL with expert demonstrations has been accepted by IV 2022!



# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><img src='png_tpami.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Human-guided Reinforcement Learning with Sim-to-real Transfer for Autonomous Navigation](https://www.researchgate.net/publication/373907062_Human-Guided_Reinforcement_Learning_With_Sim-to-Real_Transfer_for_Autonomous_Navigation), **Jingda Wu**, Yanxin Zhou, Haohan Yang, Zhiyu Huang, Chen Lv

**IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023** \| [**Project**](https://wujingda.github.io/Multi-Hug-RL/)
-  We propose a human-guided RL framework for UGVs, incorporating a series of human guidance mechanisms to enhance RL's efficiency and effectiveness during both simulations and real-world experiments. The developed method demonstrates improved performance in goal-reaching and safety while navigating in diverse environments using tiny neural networks and image inputs, and showcases favorable physical fine-tuning ability via online human guidance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='png_tte.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Deep Reinforcement Learning based Energy-efficient Decision-making for Autonomous Electric Vehicle in Dynamic Traffic Environments](https://ieeexplore.ieee.org/abstract/document/10164154), **Jingda Wu**, Ziyou Song, Chen Lv

**IEEE Transactions on Transportation Electrification, 2023**
- We propose a deep RL strategy for autonomous electrified vehicles (EVs) that takes as input the bird's-eye-view (BEV) images and enhances energy efficiency through smart lane-changing and car-following behaviors, incorporating a safety system for safer lane changes. Simulations show the strategy improves energy economy without compromising safety or traffic efficiency.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/engineering.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Towards Human-in-the-loop AI: Enhancing Deep Reinforcement Learning via Real-time Human Guidance for Autonomous Driving](https://www.sciencedirect.com/science/article/pii/S2095809922004878), **Jingda Wu**, Zhiyu Huang, Zhongxu Hu, Chen Lv

**Engineering, 2022** \| [**Project**](https://github.com/wujingda/Human-in-the-loop-Deep-Reinforcement-Learning) 
-  We propose a real-time human guidance-based deep reinforcement learning method for improving policy training performance. The newly designed actor-critic architecture enabled the DRL policy to approach human guidance, and a 40 subjects-involved human-in-the-loop experimental validation confirms its superior performance for end-to-end autonomous driving cases.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/tnnls_jingda.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
  
[Prioritized Experience-based Reinforcement Learning with Human Guidance for Autonomous Driving](https://arxiv.org/pdf/2109.12516.pdf), **Jingda Wu**, Zhiyu Huang, Wenhui Huang, Chen Lv

**IEEE Transactions on Neural Networks and Learning Systems, 2022** \| [**Project**](https://github.com/wujingda/Prioritized-Human-in-the-loop-End-to-end-Autonomous-Driving)
-  We propose a priority experience utilization method in the context of human guidance-based off-policy reinforcement learning (RL) algorithms, in which we establish an advantage measurement to highlight high-value human guidance data over the mixed experience buffer with both human demonstration and RL experience. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/tiv_jingda.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Uncertainty-Aware Model-Based Reinforcement Learning with Application to Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9802913), **Jingda Wu**, Zhiyu Huang, Chen Lv

**IEEE Transactions on Intelligent Vehicle, 2022** 
(<i><span style="color:red;">ESI Highly Cited Paper)
- We propose an uncertainty-aware model-based RL method to improve the performance in the context of highly uncertain environment models. Based on an action-conditioned ensemble model, we develop an adaptive truncation approach to determine the utilization extent of the environment model and improve RL’s training efficiency and performance. 

</div>
</div>

- Sampling Efficient Deep Reinforcement Learning through Preference-Guided Stochastic Exploration. Wenhui Huang, Cong Zhang, **Jingda Wu**, Xiangkun He, Jie Zhang, Chen Lv.  <span style="color:green;">IEEE TNNLS<span>, 2023
  
- [Real-time driver cognitive workload recognition: attention-enabled learning with multimodal information fusion](https://ieeexplore.ieee.org/abstract/document/10163920/). Haohan Yang, **Jingda Wu**, Zhongxu Hu, Chen Lv.  <span style="color:green;">IEEE TIE<span>, 2023

- [Differentiable integrated motion prediction and planning with learnable cost function for autonomous driving](https://ieeexplore.ieee.org/abstract/document/10154577/). Zhiyu Huang, Haochen Liu, **Jingda Wu**, Chen Lv.  <span style="color:green;">IEEE TNNLS<span>, 2023

- [Conditional predictive behavior planning with inverse reinforcement learning for human-like autonomous driving](https://ieeexplore.ieee.org/abstract/document/10073960/). Zhiyu Huang, Haochen Liu, **Jingda Wu**, Chen Lv. <span style="color:green;">IEEE TITS<span>, 2023

- [Safe Decision-making for Lane-change of Autonomous Vehicles via Human Demonstration-aided Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9921872), **Jingda Wu**, Wenhui Huang, Niels de Boer, Yanghui Mo, Xiangkun He, Chen Lv, <span style="color:green;">IEEE ITSC<span>, 2022
  
- [Graph Convolution-Based Deep Reinforcement Learning for Multi-Agent Decision-Making in Mixed Traffic Environments](https://arxiv.org/pdf/2201.12776v1.pdf), Qi Liu, Zirui Li, Xueyuan Li, **Jingda Wu**, Shihua Yuan, <span style="color:green;">IEEE ITSC<span>, 2022
  
- [Improved Deep Reinforcement Learning with Expert Demonstrations for Urban Autonomous Driving](https://arxiv.org/pdf/2102.09243.pdf), Haochen Liu, Zhiyu Huang, **Jingda Wu**, Chen Lv, <span style="color:green;">IEEE IV<span>, 2022
  
- [Efficient Deep Reinforcement Learning with Imitative Expert Priors for Autonomous Driving](https://arxiv.org/pdf/2103.10690.pdf), Zhiyu Huang, **Jingda Wu**, Chen Lv, <span style="color:green;">IEEE TNNLS<span>, 2022
  
- [Driving Behavior Modeling using Naturalistic Human Driving Data with Inverse Reinforcement Learning](https://arxiv.org/pdf/2010.03118.pdf), Zhiyu Huang, **Jingda Wu**, Chen Lv, <span style="color:green;">IEEE TITS<span>, 2021
  
- [Deep deterministic policy gradient-drl enabled multiphysics-constrained fast charging of lithium-ion battery](https://ieeexplore.ieee.org/abstract/document/9398552/), Zhongbao Wei, Zhongyi Quan, **Jingda Wu***, Yang Li, Josep Pou, Hao Zhong, <span style="color:green;">IEEE TIE<span>, 2021 (<i>ESI Hot Paper)
  
- [Digital Twin-enabled Reinforcement Learning for End-to-end Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9540179), **Jingda Wu**, Zhiyu Huang, Peng Hang, Chao Huang, Niels De Boer, Chen Lv, <span style="color:green;">IEEE DTPI<span>, 2021 (<i><span style="color:red;">Outstanding Student Paper Award)
  
- [Personalized Trajectory Planning and Control of Lane-Change Maneuvers for Autonomous Driving](https://ieeexplore.ieee.org/abstract/document/9419761/), Chao Huang, Hailong Huang, Peng Hang, Hongbo Gao, **Jingda Wu**, Zhiyu Huang, Chen Lv, <span style="color:green;">IEEE TVT<span>, 2021
  
- Confidence-based Reinforcement Learning for Energy Management of a Hybrid Electric Vehicle, **Jingda Wu**, Zhiyu Huang, Junzhi Zhang, Chen Lv, <span style="color:green;">EVS34<span>, 2021 (<i><span style="color:red;">Excellent Paper Award</span></i>)
  
- [Battery-involved energy management for hybrid electric bus based on expert-assistance deep deterministic policy gradient algorithm](https://ieeexplore.ieee.org/abstract/document/9201478), **Jingda Wu**, Zhongbao Wei, Kailong Liu, Zhongyi Quan, Yunwei Li, <span style="color:green;">IEEE TVT<span>, 2021 (<i><span style="color:red;">ESI Highly Cited Paper)
  
- [Battery thermal-and health-constrained energy management for hybrid electric bus based on soft actor-critic DRL algorithm](https://ieeexplore.ieee.org/abstract/document/9160869), **Jingda Wu**, Zhongbao Wei, Weihan Li, Yu Wang, Yunwei Li, Dirk Uwe Sauer, <span style="color:green;">IEEE TII<span>, 2020 (<i><span style="color:red;">ESI Hot Paper)
  
- [Multi-modal sensor fusion-based deep neural network for end-to-end autonomous driving with scene understanding](https://arxiv.org/pdf/2005.09202.pdf), Zhiyu Huang, Chen Lv, Yang Xing, **Jingda Wu**, <span style="color:green;">IEEE Sensors Journal<span>, 2020
  
- [Energy management based on reinforcement learning with double deep Q-learning for a hybrid electric tracked vehicle](https://www.sciencedirect.com/science/article/abs/pii/S0306261919313959), Xuefeng Han, Hongwen He, **Jingda Wu**, Jiankun Peng, Yuecheng Li, <span style="color:green;">Applied energy<span>, 2019  (<i><span style="color:red;">ESI Highly Cited Paper)
  
- [Continuous reinforcement learning of energy management with deep Q network for a power split hybrid electric bus](https://www.sciencedirect.com/science/article/abs/pii/S0306261918304422), **Jingda Wu**, Hongwen He, Jiankun Peng, Yuecheng Li, Zhanjiang Li, <span style="color:green;">Applied energy<span>, 2018 (<i><span style="color:red;">ESI Hot Paper)



# 🎖 Recent Honors and Awards
- *2023.08* 2nd Place Winner at [Track 1](https://psi-intention2022.github.io/), IEEE ITSS Student Competition in Pedestrian Behavior Prediction
- *2022.12* 2nd Place Winner at [Algorithm Track](https://tianchi.aliyun.com/competition/entrance/531996/rankingList), Aliyun "Future Car" Smart Scenario Innovation Challenge
- *2022.12* 3rd Place Winner at [Track 1 and Track 2, Most Innovative Award, NeurIPS Driving SMARTS Competition](https://smarts-project.github.io/), NeurIPS Competition Track
- *2022.07* Participant, Imperial-TUM-NTU Global Fellows Programme
- *2022.03* Winner, IEEE [VTS Motor Vehicles](https://oraprdnt.uqtr.uquebec.ca/pls/public/gscw031?owa_no_site=6851) Challenge
- *2021.06* Excellent Student Paper Award in IEEE International Conference on Digital Twins and Parallel Intelligence (DTPI), 2021
- *2021.06* Excellent Paper Award in 34th World Electric Vehicle Symposium & Exhibition (EVS34), 2021


# 📖 Educations
- *2019.08 - 2023.04*, Doctor of Philosophy, Robotics and Autonomous Systems, Nanyang Technological University, Singapore 
- *2016.09 - 2019.06*, Master by Research, Mechanical Engineering, Beijing Institute of Technology, Beijing, China
- *2012.09 - 2016.06*, Bachelor of Engineering, Vehicle Engineering, Beijing Institute of Technology, Beijing, China

# 💻 Internships
- *2018.05 - 2018.09*, Visiting Scholar, University of Waterloo, Canada

# 📚 Academic Services
- Journal Reviewer: IEEE Transactions on Neural Networks and Learning Systems (TNNLS), IEEE Transactions on Intelligent Transportation Systems (TITS), IEEE Transactions on Industrial Electronics (TIE), IEEE Transactions on Intelligent Vehicles (TIV), IEEE Transactions on Transportation Electrification (TTE), Applied Energy, Computational Intelligence and Neuroscience, IET Intelligent Transport Systems, Proceedings of IMechE, Part D, Control Engineering Practice, et al.
- Conference Reviewer: IV'22, ITSC'22.
