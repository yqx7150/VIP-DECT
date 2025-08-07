# VIP-DECT

**Paper:** Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction

**Authors:** Zini Chen, Yao Xiao, Junyan Zhang, Shaoyu Wang, Liu Shi, Qiegen Liu

Sparse-view sampling in dual-energy computed tomography (DECT) significantly reduces radiation dose and increases imaging speed, yet is highly prone to artifacts. Although diffusion models have demonstrated potential in effectively handling incomplete data, most existing methods in this field focus on the image domain and lack global constraints, which consequently leads to insufficient reconstruction quality. In this study, we propose a dual-domain virtual-mask informed diffusion model for sparse-view reconstruction by leveraging the high inter-channel correlation in DECT. Specifically, the study designs a virtual mask and applies it to the high-energy and low-energy data to perform perturbation operations, thus constructing high-dimensional tensors that serve as the prior information of the diffusion model. In addition, a dual-domain collaboration strategy is adopted to integrate the information of the randomly selected high-frequency components in the wavelet domain with the information in the projection domain, for the purpose of optimizing the global structures and local details. The experimental results show that the method exhibits excellent performance on multiple datasets. Under 30-view sparse sampling conditions, VIP-DECT improves PSNR by at least 1.67 dB and enhances SSIM by 3.5%.

![Fig. 5](https://github.com/yqx7150/VIP-DECT/blob/main/fig%206.svg)



## Experiment Result

To validate the performance of VIP-DECT, this section compares it with FBP (Brenner and Hall, 2007), FBPConvNet (Jin et al., 2017), HDNet(Hu et al., 2020), NCSN++ (Song et al., 2020) , GMSD(Guan et al., 2023) and SWORD(Xu et al., 2024) in reconstruction tasks.

### Reconstruction Results Under Head DECT Dataset

![Fig. 6](https://github.com/yqx7150/VIP-DECT/blob/main/fig%206.svg)

### Reconstruction Results Under Mouse Thoracic DECT Dataset

![Fig. 7](https://github.com/yqx7150/VIP-DECT/blob/main/fig%207.svg)

### Material Decomposition

![Fig. 8](https://github.com/yqx7150/VIP-DECT/blob/main/fig%208.svg)

