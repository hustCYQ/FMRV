# FMRV: a Fast Multiview point cloud Registration method with Variance constraint




# Abstract
In 3D scanning of large-sized industrial parts, it is more common to collect point cloud datas in multiple views by using industrial robots with 3D sensors to obtain complete point cloud datas due to excessive size or self occlusion of the parts. Considering the influence of robot positioning error, to ensure the geometric accuracy of collected entire industrial part point clouds, fine registration is required after rough registration of multi view point clouds using the pose of collection. This paper propose a fast multiview point cloud registration method with variance constraint (FMRV) to register multiview point cloud datas of industrial parts with partial overlapping, layered and uneven density. The overlapping relationship between multiview point clouds are determined by 3D bounding box firstly. Then a point cloud slicing method is proposed to speed up the search of corresponding points between multiview point clouds and an objective function take advantage of point distance and distance variance is established. Finally, the pose of multiview point clouds are optimized by iteratively solving the objective function. The complexity of the point cloud slicing method is theoretically analyzed, and the experiment proves it has a significant acceleration effect. The accuracy of registration is tested qualitatively and quantitatively in the experiments, and the results show that FMRV performs better in the registration of multiview point clouds, especially for the point clouds of uneven density compared with the Multiview ICP.


# Citation
If you are interested in our paper and code or you find this project useful in your research, please consider cite:<br>
```
@article{}
```


# Installation
```
Clone this repository: tested on Python 3.7
Install PyTorch: tested on v1.7
```

# Demo


# Some results















