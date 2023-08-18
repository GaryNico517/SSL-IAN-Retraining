# SSL-IAN-Retraining for MICCAI FAIRY2023 Challenge
Champion Solution of [MICCAI FAIRY2023 Challenge](https://toothfairy.grand-challenge.org/) based on Self-training with Selective Re-training.

**Inferior Alveolar Nerve Segmentation in CBCT images using Connectivity-Based Selective Re-training**  
_Yusheng Liu(lys_sjtu@sjtu.edu.cn), Rui Xin(xr1999@sjtu.edu.cn), Tao Yang(yangtao22@sjtu.edu.cn) and Lisheng Wang(lswang@sjtu.edu.cn)_

Institute of Image Processing and Pattern Recognition, Department of Automation,  
Shanghai Jiao Tong University, Shanghai 200240, People’s Republic of China  

The pipeline of the proposed segmentation framework is shown in Fig.1. We adopt
nnUNet as the basic network models for IAN segmentation. Self-training method
is adopted for semi-supervised semantic segmentation. In addition, a connectivity-based
selective re-training strategy is designed to screen more plausible pseudo-labels.  

## Environments and Requirements:
### 1. Install and deploy nnUNet
