# VIP-DECT

**Paper:** Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction

**Authors:** Zini Chen, Yao Xiao, Junyan Zhang, Shaoyu Wang, Liu Shi, Qiegen Liu

Sparse-view sampling in dual-energy computed tomography (DECT) significantly reduces radiation dose and increases imaging speed, yet is highly prone to artifacts. Although diffusion models have demonstrated potential in effectively handling incomplete data, most existing methods in this field focus on the image domain and lack global constraints, which consequently leads to insufficient reconstruction quality. In this study, we propose a dual-domain virtual-mask informed diffusion model for sparse-view reconstruction by leveraging the high inter-channel correlation in DECT. Specifically, the study designs a virtual mask and applies it to the high-energy and low-energy data to perform perturbation operations, thus constructing high-dimensional tensors that serve as the prior information of the diffusion model. In addition, a dual-domain collaboration strategy is adopted to integrate the information of the randomly selected high-frequency components in the wavelet domain with the information in the projection domain, for the purpose of optimizing the global structures and local details. The experimental results show that the method exhibits excellent performance on multiple datasets. Under 30-view sparse sampling conditions, VIP-DECT improves PSNR by at least 1.67 dB and enhances SSIM by 3.5%.

![](D:\HuaweiMoveData\Users\肖瑶\Desktop\论文作图\Group 236.png)

![](D:\HuaweiMoveData\Users\肖瑶\Desktop\论文作图\Group 237.png)

![](D:\HuaweiMoveData\Users\肖瑶\Desktop\VIP-DECT method.png)



## Experiment Result

To validate the performance of VIP-DECT, this section compares it with FBP (Brenner and Hall, 2007), FBPConvNet (Jin et al., 2017), HDNet(Hu et al., 2020), NCSN++ (Song et al., 2020) , GMSD(Guan et al., 2023) and SWORD(Xu et al., 2024) in reconstruction tasks.

### Reconstruction Results Under Head DECT Dataset

![]()![Group 427](D:\HuaweiMoveData\Users\肖瑶\Desktop\Group 427.png)

### Reconstruction Results Under Mouse Thoracic DECT Dataset

![](D:\HuaweiMoveData\Users\肖瑶\Desktop\Group 418.png)

### Material Decomposition

![](D:\HuaweiMoveData\Users\肖瑶\Desktop\Group 419.png)

