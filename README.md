# Formation-control-with-lane-preference

Multi-lane roads are typical scenarios in the real-world traffic system. Vehicles usually have preference on lanes according to their routes and destinations. Few of the existing studies looks into the problem of controlling vehicles to drive on their desired lanes. This paper proposes a formation control method that considers vehicles' preference on different lanes. The bi-level formation control framework is utilized to plan collision-free motion for vehicles, where relative target assignment and path planning are performed in the upper level, and trajectory planning and tracking are performed in the lower level. The collision-free multi-vehicle path planning problem considering lane preference is decoupled into two sub problems: calculating assignment list with non-decreasing cost and  planning collision-free paths according to given assignment result. The Conflict-based Searching (CBS) method is utilized to plan collision-free paths for vehicles based on given assignment results. Case study is conducted and simulations are carried out in a three-lane road scenario. The results indicate that the proposed formation control method significantly reduces congestion and improves traffic efficiency at high traffic volumes, compared to the rule-based method.

## The videos can be seen in the attachments, and here we provide some GIFs.

### Case study
<img src="https://github.com/cmc623/Formation-control-with-lane-preference/blob/main/case_study.gif" width="1000" />

### Simulation without formation control
<img src="https://github.com/cmc623/Formation-control-with-lane-preference/blob/main/result_REF.gif" width="1000" />

### Simulation with formation control
<img src="https://github.com/cmc623/Formation-control-with-lane-preference/blob/main/result_FRC.gif" width="1000" />


For further details, please refer to:

[1] Cai M, Xu Q, Chen C, et al. Formation Control for Multiple Connected and Automated Vehicles on Multi-lane Roads[C]. Accepted by IEEE International Conference on Intelligent Transportation Systems, 2021. (https://arxiv.org/abs/2103.10287)

[2] Cai M, Xu Q, Chen C, et al. Formation Control for Connected and Automated Vehicles on Multi-lane Roads: Relative Motion Planning and Conflict Resolution[J]. arXiv preprint arXiv:2103.10287v3, 2021. (https://arxiv.org/abs/2103.10287)

[3] Cai M, Chen C, Wang J, et al. Formation Control with Lane Preference for Connected and Automated Vehicles in Multi-lane Scenarios[J]. arXiv preprint arXiv:2106.11763, 2021. (https://arxiv.org/abs/2106.11763)

[4] Cai M, Xu Q, Chen C, et al. Multi-lane Unsignalized Intersection Cooperation with Flexible Lane Direction based on Multi-vehicle Formation Control[J]. arXiv preprint arXiv:2108.11112, 2021. (https://arxiv.org/abs/2108.11112)


Corresponding E-mail: 

cmc18@mails.tsinghua.edu.cn

qingxu@tsinghua.edu.cn

likq@tsinghua.edu.cn

Follow my updates on Researchgate: https://www.researchgate.net/profile/Mengchi-Cai

This work was supported by the National Key Research and Development Program of China under Grant 2018YFE0204302, the National Natural Science Foundation of China under Grant 52072212, and Intel Collaborative Research Institute Intelligent and Automated Connected Vehicles. 
