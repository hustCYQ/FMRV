# FMRV: a Fast Multiview point cloud Registration method with Variance constraint




# Abstract
In 3D scanning of large-sized industrial parts, it is more common to collect point cloud datas in multiple views by using industrial robots with 3D sensors to obtain complete point cloud datas due to excessive size or self occlusion of the parts. Considering the influence of robot positioning error, to ensure the geometric accuracy of collected entire industrial part point clouds, fine registration is required after rough registration of multi view point clouds using the pose of collection. This paper propose a fast multiview point cloud registration method with variance constraint (FMRV) to register multiview point cloud datas of industrial parts with partial overlapping, layered and uneven density. The overlapping relationship between multiview point clouds are determined by 3D bounding box firstly. Then a point cloud slicing method is proposed to speed up the search of corresponding points between multiview point clouds and an objective function take advantage of point distance and distance variance is established. Finally, the pose of multiview point clouds are optimized by iteratively solving the objective function. The complexity of the point cloud slicing method is theoretically analyzed, and the experiment proves it has a significant acceleration effect. The accuracy of registration is tested qualitatively and quantitatively in the experiments, and the results show that FMRV performs better in the registration of multiview point clouds, especially for the point clouds of uneven density compared with the Multiview ICP.


# Citation
If you are interested in our paper and code or you find this project useful in your research, please consider cite:
`@article{CAO2022108846,
title = {Informative knowledge distillation for image anomaly segmentation},
journal = {Knowledge-Based Systems},
volume = {248},
pages = {108846},
year = {2022},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2022.108846},
url = {https://www.sciencedirect.com/science/article/pii/S0950705122004038},
author = {Yunkang Cao and Qian Wan and Weiming Shen and Liang Gao},
keywords = {Image anomaly segmentation, Knowledge distillation, Context similarity, Hard sample mining},
abstract = {Unsupervised anomaly segmentation methods based on knowledge distillation have recently been developed and have shown superior segmentation performance. However, little attention has been paid to the overfitting problem caused by the inconsistency between the capacity of a neural network and the amount of knowledge in this scheme. This study proposes a novel method called informative knowledge distillation (IKD) to address the overfitting problem by distilling informative knowledge and offering a strong supervisory signal. Technically, a novel context similarity loss method is proposed to capture context information from normal data manifolds. In addition, a novel adaptive hard sample mining method is proposed to encourage more attention on hard samples with valuable information. With IKD, informative knowledge can be distilled such that the overfitting problem can be effectively mitigated, and the performance can be further increased. The proposed method achieved better results on several categories of the well-known MVTec AD dataset than state-of-the-art methods in terms of AU-ROC, achieving 97.81% overall in 15 categories. Extensive experiments on ablation have also been conducted to demonstrate the effectiveness of IKD in alleviating the overfitting problem.}
}`


# Installation


# Demo


# Some results















