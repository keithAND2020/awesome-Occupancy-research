### occupancy

## 起源

#### 1  最开始的文章

Occupancy Networks: Learning 3D Reconstruction in Function Space

Occupancy Networks 系列的**开山之作**，在这篇论文中，作者提出了占据网络 Occupancy Network，一种新的基于学习的三维重建方法。目前引用【2275】



#### 2  tesla的AI day

[1] [聊一聊Tesla 的Occupancy Network - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/575953155)

[2]https://www.youtube.com/watch?v=ODSJsviD_SU&t=12s

[3]https://www.youtube.com/watch?v=KC8e0oTFUcw



## 发展

#### 时间顺序

##### 【2023】

> ##### 1、**[ICCV 2023]** OccNet: Scene as Occupancy
>
> **2、PanoOcc: Unified Occupancy Representation for Camera-based 3D Panoptic Segmentation**
>
> **3、Occ-BEV: Multi-Camera Unified Pre-training via 3D Scene Reconstruction**
>
> **4、[CVPR 2023] Tri-Perspective View for Vision-Based 3D Semantic Occupancy Prediction**
>
> **5、OccFormer: Dual-path Transformer for Vision-based 3D Semantic Occupancy Prediction**
>
> **6、SurroundOcc: Multi-Camera 3D Occupancy Prediction for Autonomous Driving**
>
> **7、Learning Occupancy for Monocular 3D Object Detection**
>
> **8、**【2023-survey】https://arxiv.org/abs/2303.01212
>
> **9、A Simple Attempt for 3D Occupancy Estimation in Autonomous Driving**
>
> **10、UniOcc: Unifying Vision-Centric 3D Occupancy Prediction with Geometric and Semantic Rendering** 
>
> **11、RenderOcc: Vision-Centric 3D Occupancy Prediction with 2D Rendering Supervision**
>
> **12、OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection**
>
> **13、PointOcc: Cylindrical Tri-Perspective View for Point-based 3D Semantic Occupancy Prediction**
>
> **14、【ICCV2023】OccNeRF：Rendering Humans from Object-Occluded Monocular Videos**
>
> **15、SelfOcc: Self-Supervised Vision-Based 3D Occupancy Prediction、**
>
> **16、SOccDPT: Semi-Supervised 3D Semantic Occupancy from Dense Prediction Transformers trained under memory constraints**
>
> **17、【2023CVPR】Behind the Scenes: Density Fields for Single View Reconstruction【13】**
> 
> **18、OccupancyM3D：Learning Occupancy for Monocular 3D Object Detection**
> 
>**19、VoxFormer：Voxformer: Sparse voxel transformer for camera-based 3d semantic scene completion**
> 
>**20、OccDepth：Occdepth: A depth-aware method for 3d semantic scene completion**
> 
>**21、TPVFormer：Tri-perspective view for vision-based 3d semantic occupancy prediction**
> 
>**22、OccBEV：Occ-BEV: Multi-Camera Unified Pre-training via 3D Scene Reconstruction**
> 
>**23、Occupancy-MAE：Occupancy-MAE: Self-Supervised Pre-Training Large-Scale LiDAR Point Clouds With Masked Occupancy Autoencoders**

**【2022】**

> 1、**[CVPR 2022]** MonoScene: Monocular 3D Semantic Scene Completion

**【2021】**

> 1、Sparse Single Sweep LiDAR Point Cloud Segmentation via Learning Contextual Shape Priors from Scene Completion【https://ojs.aaai.org/index.php/AAAI/article/view/16419】分割



#### 在自动驾驶按照**输入分类**：（后标注的是引用次数）

> **single image**：MonoScene【72】、OccupancyM3D【1】、VoxFormer【43】、A Simple Attempt for 3D Occupancy Estimation in Autonomous Driving【5】、OccupancyDETR【1】、SOccDPT【0】
>
> **depth image**：2023-OccDepth【22】
>
> **multiview**：TPVFormer【59】、SurroundOcc【31】、OccFormer【16】、OccBEV【2】、PanoOcc【6；好像目前nuscenes基于camera分割榜单第2】、UniOcc【4】、SelfOcc【1】、OccNeRF【0】
>
> **lidar：**PointOcc【2】

#### 利用Pre-training

> Occupancy-MAE: Self-supervised Pre-training Large-scale LiDAR Point Clouds with Masked Occupancy Autoencoders【8】
>
> Occ-BEV【2】

#### Efficient Occupancy 

> FlashOcc：Fast and Memory-Efficient Occupancy Prediction via Channel-to-Height Plugin【0】
>
> SOccDPT: Semi-Supervised 3D Semantic Occupancy from Dense Prediction Transformers trained under memory constraints【0】



#### occupancy with anything！

> RenderOcc: Vision-Centric 3D Occupancy Prediction with 2D Rendering Supervision【4】
>
> OccupancyDETR: Making Semantic Scene Completion as Straightforward as Object Detection【1】
>
> OccNeRF: Self-Supervised Multi-Camera Occupancy Prediction with Neural Radiance Fields【0】
>
> Behind the Scenes: Density Fields for Single View Reconstruction【13】



#### Occupanc比赛

> 比赛：The world's First 3D Occupancy Benchmark for Scene Perception in Autonomous Driving【https://github.com/CVPR2023-3D-Occupancy-Prediction/CVPR2023-3D-Occupancy-Prediction】
>
> <img src="https://github.com/CVPR2023-3D-Occupancy-Prediction/CVPR2023-3D-Occupancy-Prediction/raw/main/figs/leaderboard-06-10-2023.png" alt="teaser" style="zoom:50%;" />





#### Occupancy数据集

> Occ3D: A Large-Scale 3D Occupancy Prediction Benchmark for Autonomous Driving 【32】
>
> OpenOccupancy: A Large Scale Benchmark for Surrounding Semantic Occupancy Perception【15】
>
> SurroundOcc【31】
>
> SSCBench: A Large-Scale 3D Semantic Scene Completion Benchmark for Autonomous Driving【5】
>
> Scene as Occupancy【15】













## 参考链接

【2019-occupancy network】http://openaccess.thecvf.com/content_CVPR_2019/html/Mescheder_Occupancy_Networks_Learning_3D_Reconstruction_in_Function_Space_CVPR_2019_paper.html

【2022-MonoScene】http://openaccess.thecvf.com/content/CVPR2022/html/Cao_MonoScene_Monocular_3D_Semantic_Scene_Completion_CVPR_2022_paper.html

【2023-OccupancyM3D】https://arxiv.org/abs/2305.15694

【2023-VoxFormer】http://openaccess.thecvf.com/content/CVPR2023/html/Li_VoxFormer_Sparse_Voxel_Transformer_for_Camera-Based_3D_Semantic_Scene_Completion_CVPR_2023_paper.html

【2023-OccDepth】https://arxiv.org/abs/2302.13540

【2023-TPVFormer】http://openaccess.thecvf.com/content/CVPR2023/html/Huang_Tri-Perspective_View_for_Vision-Based_3D_Semantic_Occupancy_Prediction_CVPR_2023_paper.html

【2023-SurroundOcc】http://openaccess.thecvf.com/content/ICCV2023/html/Wei_SurroundOcc_Multi-camera_3D_Occupancy_Prediction_for_Autonomous_Driving_ICCV_2023_paper.html

【2023-OccFormer】https://arxiv.org/abs/2304.05316

【2023-OccBEV】https://arxiv.org/abs/2305.18829

【2023-PanoOcc】https://arxiv.org/abs/2306.10013

【2022-LOPR】https://arxiv.org/abs/2210.01249

【A Simple Attempt for 3D Occupancy Estimation in Autonomous Driving】https://arxiv.org/abs/2303.10076

【2023-UniOcc】https://arxiv.org/abs/2306.09117

【2023-Occ3D】https://arxiv.org/abs/2304.14365

【2023-OpenOccupancy】https://arxiv.org/abs/2303.03991

【2023-SSCBench】https://arxiv.org/abs/2306.09001

【Occupancy-MAE】https://ieeexplore.ieee.org/abstract/document/10273603/?casa_token=RKAYiCgprDgAAAAA:eq6K85lc3pij8TkcyH8UXCVn2_iy-vNZ04ywQaDt6Nbk70Chbzx8SvZ5I1MPEgyc2K4BtEXW7Att

【2023FlashOcc】https://arxiv.org/abs/2311.12058

【2023-OccupancyDETR】https://arxiv.org/abs/2309.08504

【2023-RenderOcc】https://arxiv.org/abs/2309.09502

【2023-PointOcc】https://arxiv.org/abs/2308.16896

【2023-OccNeRF】https://arxiv.org/abs/2312.09243

【2023-SelfOcc】https://arxiv.org/abs/2311.12754



【2023-Behind the Scenes】http://openaccess.thecvf.com/content/CVPR2023/html/Wimbauer_Behind_the_Scenes_Density_Fields_for_Single_View_Reconstruction_CVPR_2023_paper.html
