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

[1] Cai M, Xu Q, Chen C, et al. Multi-lane unsignalized intersection cooperation with flexible lane direction based on multi-vehicle formation control[J]. IEEE Transactions on Vehicular Technology, 2022, 71(6): 5787-5798. (https://ieeexplore.ieee.org/abstract/document/9740423/)

[2] Xu Q, Cai M, Li K, et al. Coordinated formation control for intelligent and connected vehicles in multiple traffic scenarios[J]. IET Intelligent Transport Systems, 2021, 15(1): 159-173. (https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/itr2.12022)

[3] Cai M, Xu Q, Li K, et al. Multi-lane formation assignment and control for connected vehicles[C]//2019 IEEE Intelligent Vehicles Symposium (IV). IEEE, 2019: 1968-1973. (https://ieeexplore.ieee.org/abstract/document/8813792)

[4] Cai M, Xu Q, Chen C, et al. Formation control with lane preference for connected and automated vehicles in multi-lane scenarios[J]. Transportation research part C: emerging technologies, 2022, 136: 103513. (https://www.sciencedirect.com/science/article/pii/S0968090X21004964)

[5] Cai M, Xu Q, Chen C, et al. Formation control for connected and automated vehicles on multi‐lane roads: Relative motion planning and conflict resolution[J]. IET Intelligent Transport Systems, 2023, 17(1): 211-226. (https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/itr2.12249)

[6] Cai M, Xu Q, Chen C, et al. Formation control for multiple connected and automated vehicles on multi-lane roads[C]//2021 IEEE International Intelligent Transportation Systems Conference (ITSC). IEEE, 2021: 1940-1945. (https://ieeexplore.ieee.org/abstract/document/9564760)


Corresponding E-mail: 

caimengchi@mail.tsinghua.edu.cn

qingxu@tsinghua.edu.cn

likq@tsinghua.edu.cn

Follow my updates on Researchgate: https://www.researchgate.net/profile/Mengchi-Cai

