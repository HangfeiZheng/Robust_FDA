# Robust Discriminant Subspace Learning with $\alpha$-divergence for Image Classification
This paper has been published at IEEE Transactions on Image Processing (https://doi.org/10.1109/TIP.2026.3700924)\\
Hangfei Zheng, Abd-Krim Seghouane, and Djamal Merad

# Overview
This paper proposes a novel robust Fisher Discriminant Analysis (FDA) for discriminative subspace learning in the presence of outliers. The proposed approach is motivated by the maximum-likelihood perspective on FDA and its connection to Kullback-Leibler (KL) divergence minimization. Within the probabilistic FDA framework, we develop a robust model by adopting the $\alpha$-divergence as a flexible alternative to the KL divergence. The resulting method induces an adaptive redescending weighting scheme, in which each observation is weighted according to its statistical compatibility with the model, where the robustness level continuously controlled by $\alpha$. 

# Code
1. The proposed algorithm is provided in alpha_RFDA.m file
2. The main_example.m is provided as a demo to implement the alph_RFDA algorith.
3. The Umist.mat facial image data is provided as the demo example.


# Citation:
If you use this code for your research, please cite our paper:
@ARTICLE{11559223,
  author={Zheng, Hangfei and Seghouane, Abd-Krim and Merad, Djamal},
  journal={IEEE Transactions on Image Processing},
  title={Robust Discriminant Subspace Learning with $\alpha$-Divergence for Image Classification},
  year={2026},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TIP.2026.3700924}}

