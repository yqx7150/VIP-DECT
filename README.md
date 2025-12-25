# VIP-DECT

**Paper:** Virtual-mask Informed Prior for Sparse-view Dual-Energy CT Reconstruction

**Authors:** Zini Chen, Yao Xiao, Junyan Zhang, Shaoyu Wang, Liu Shi, Qiegen Liu

Sparse-view sampling in dual-energy computed tomography (DECT) significantly reduces radiation dose and increases imaging speed, yet is highly prone to artifacts. Although diffusion models have demonstrated potential in effectively handling incomplete data, most existing methods in this field focus on the image domain and lack global constraints, which consequently leads to insufficient reconstruction quality. In this study, we propose a dual-domain virtual-mask informed diffusion model for sparse-view reconstruction by leveraging the high inter-channel correlation in DECT. Specifically, the study designs a virtual mask and applies it to the high-energy and low-energy data to perform perturbation operations, thus constructing high-dimensional tensors that serve as the prior information of the diffusion model. In addition, a dual-domain collaboration strategy is adopted to integrate the information of the randomly selected high-frequency components in the wavelet domain with the information in the projection domain, for the purpose of optimizing the global structures and local details. The experimental results show that the method exhibits excellent performance on multiple datasets. Under 30-view sparse sampling conditions, VIP-DECT improves PSNR by at least 1.67 dB and enhances SSIM by 3.5%.

![Fig. 5](https://github.com/yqx7150/VIP-DECT/blob/main/VIP-DECT%20method.svg)



## Experiment Result

To validate the performance of VIP-DECT, this section compares it with FBP (Brenner and Hall, 2007), FBPConvNet (Jin et al., 2017), HDNet(Hu et al., 2020), NCSN++ (Song et al., 2020) , GMSD(Guan et al., 2023) and SWORD(Xu et al., 2024) in reconstruction tasks.

### Reconstruction Results Under Head DECT Dataset

![Fig. 6](https://github.com/yqx7150/VIP-DECT/blob/main/fig%206.svg)

### Reconstruction Results Under Mouse Thoracic DECT Dataset

![Fig. 7](https://github.com/yqx7150/VIP-DECT/blob/main/fig%207.svg)

### Material Decomposition

![Fig. 8](https://github.com/yqx7150/VIP-DECT/blob/main/fig%208.svg)


### Other Related Projects
<div align="center"><img src="https://github.com/yqx7150/OSDM/blob/main/All-CT.png" >  </div>   
    
  * Generative Modeling in Sinogram Domain for Sparse-view CT Reconstruction      
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/10233041)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/GMSD)

  * One Sample Diffusion Model in Projection Domain for Low-Dose CT Imaging  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/10506793)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/OSDM)

  * Iterative Reconstruction for Low-Dose CT using Deep Gradient Priors of Generative Model  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/9703672)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/EASEL)   [<font size=5>**[PPT]**</font>](https://github.com/yqx7150/HGGDP/tree/master/Slide)
    
  * REDAEP: Robust and Enhanced Denoising Autoencoding Prior for Sparse-View CT Reconstruction  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/9076295)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/REDAEP)   [<font size=5>**[PPT]**</font>](https://github.com/yqx7150/HGGDP/tree/master/Slide)

  * Wavelet-improved score-based generative model for medical imaging  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/10288274)

  * 基于深度能量模型的低剂量CT重建  
[<font size=5>**[Paper]**</font>](http://cttacn.org.cn/cn/article/doi/10.15953/j.ctta.2021.077)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/EBM-LDCT)  

 * Stage-by-stage Wavelet Optimization Refinement Diffusion Model for Sparse-view CT Reconstruction  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/10403850)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/SWORD)

  * Dual-Domain Collaborative Diffusion Sampling for Multi-Source Stationary Computed Tomography Reconstruction  
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/10577271)   [<font size=5>**[Code]**</font>](https://github.com/lizrzr/DCDS-Dual-domain_Collaborative_Diffusion_Sampling)

  * Low-rank Angular Prior Guided Multi-diffusion Model for Few-shot Low-dose CT Reconstruction     
[<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/abstract/document/10776993)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/PHD)

  * Physics-informed DeepCT: Sinogram Wavelet Decomposition Meets Masked Diffusion  
[<font size=5>**[Paper]**</font>](https://arxiv.org/abs/2501.09935)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/SWARM)    
                    
  * MSDiff: Multi-Scale Diffusion Model for Ultra-Sparse View CT Reconstruction  
[<font size=5>**[Paper]**</font>](https://arxiv.org/pdf/2405.05763)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/MSDiff)

  * Ordered-subsets Multi-diffusion Model for Sparse-view CT Reconstruction      
[<font size=5>**[Paper]**</font>](https://arxiv.org/abs/2505.09985)

  * Raw_data_generation  [<font size=5>**[Code]**</font>](https://github.com/yqx7150/Raw_data_generation)

  * PRO: Projection Domain Synthesis for CT Imaging  [<font size=5>**[Paper]**</font>](https://arxiv.org/pdf/2506.13443)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/PRO)
       
  * UniSino: Physics-Driven Foundational Model for Universal CT Sinogram Standardization[<font size=5>**[Paper]**</font>](https://arxiv.org/abs/2508.17816)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/UniSino)

  * Diffusion Models for Medical Imaging
[<font size=5>**[Paper]**</font>](https://github.com/yqx7150/Diffusion-Models-for-Medical-Imaging)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/Diffusion-Models-for-Medical-Imaging)   [<font size=5>**[PPT]**</font>](https://github.com/yqx7150/HKGM/tree/main/PPT) 
