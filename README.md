## Introduction

There is a recent trend of learning a generalizable 6DoF object pose estimator. Generalizable object pose estimator is able to estimate 6DoF poses for unseen objects without training or finetuning on the test object. In comparison, previous 6DoF object pose estimators are mainly targeted to a specific object or a specific object category. Below are papers related about generalizable 6DoF object estimator in recent years, especially on ECCV2022 or CVPR2022. Feel free to add any related papers by issues or pull requests. :)

## Paper List

### CVPR2022

Templates for 3D Object Pose Estimation Revisited: Generalization to New Objects and Robustness to Occlusions \[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Nguyen_Templates_for_3D_Object_Pose_Estimation_Revisited_Generalization_to_New_CVPR_2022_paper.pdf)\] \[[code](https://github.com/nv-nguyen/template-pose)\]

OnePose: One-Shot Object Pose Estimation without CAD Models \[[paper](https://arxiv.org/pdf/2205.12257.pdf)\] \[[code](https://github.com/zju3dv/OnePose)\]

OVE6D: Object Viewpoint Encoding for Depth-based 6D Object Pose Estimation \[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Cai_OVE6D_Object_Viewpoint_Encoding_for_Depth-Based_6D_Object_Pose_Estimation_CVPR_2022_paper.pdf)\] \[[code](https://github.com/dingdingcai/OVE6D-pose)\]

FS6D: Few-Shot 6D Pose Estimation of Novel Objects \[[paper](https://arxiv.org/pdf/2203.14628.pdf)\] \[[code](https://github.com/ethnhe/FS6D-PyTorch)\]

OSOP: A Multi-Stage One Shot Object Pose Estimation Framework \[[paper](https://arxiv.org/pdf/2203.15533.pdf)\]

### ECCV2022

ShAPO :tophat:: Implicit Representations for Multi Object Shape Appearance and Pose Optimization, *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.13691.pdf)] [[Webpage](https://zubair-irshad.github.io/projects/ShAPO.html)] [[Video](https://youtu.be/LMg7NDcLDcA)] 

Gen6D: Generalizable Model-Free 6-DoF Object Pose Estimation from RGB Images \[[paper](https://arxiv.org/pdf/2204.10776.pdf)\] \[[code](https://github.com/liuyuan-pal/Gen6D)\]

Fusing Local Similarities for Retrieval-based 3D Orientation Estimation of Unseen Objects \[[paper](https://arxiv.org/pdf/2203.08472.pdf)\] \[[code](https://github.com/sailor-z/Unseen_Object_Pose)\]

### Others

[ICRA2022] CenterSnap: Single-Shot Multi-Object 3D Shape Reconstruction and Categorical 6D Pose and Size Estimation. [\[PDF\]](https://arxiv.org/pdf/2203.01929) [\[Project\]](https://zubair-irshad.github.io/projects/CenterSnap.html) [\[Code\]](https://github.com/zubair-irshad/CenterSnap) [\[Video\]](https://www.youtube.com/watch?v=Bg5vi6DSMdM)

[Arxiv2022] Unseen Object 6D Pose Estimation: A Benchmark and Baselines \[[paper](https://arxiv.org/pdf/2206.11808.pdf)\] \[[dataset](https://graspnet.net/unseen6d)\]

[IROS2021] BundleTrack: 6D Pose Tracking for Novel Objects without Instance or Category-Level 3D Models \[[paper](https://arxiv.org/abs/2108.00516)\] \[[code](https://github.com/wenbowen123/BundleTrack)\]

[ICRA2021] ZePHyR: Zero-shot Pose Hypothesis Rating \[[paper](https://arxiv.org/pdf/2104.13526.pdf)\] \[[code](https://github.com/r-pad/zephyr)\]

[ICCVW2021] CorNet: Generic 3D Corners for 6D Pose Estimation of New Objects without Retraining \[[paper](https://arxiv.org/pdf/1908.11457.pdf)\]

[WACV2021] 3DPoseLite: A Compact 3D Pose Estimation Using Node Embeddings \[[paper](https://openaccess.thecvf.com/content/WACV2021/papers/Dani_3DPoseLite_A_Compact_3D_Pose_Estimation_Using_Node_Embeddings_WACV_2021_paper.pdf)\]

[ECCV2020] Geometric correspondence fields: Learned differentiable rendering for 3d pose refinement in the wild \[[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123610103.pdf)\]

[CVPR2020] Multi-path Learning for Object Pose Estimation Across Domains \[[paper](https://arxiv.org/pdf/1908.00151.pdf)\] \[[code](https://github.com/DLR-RM/AugmentedAutoencoder/tree/multipath)\]

[CVPR2020] LatentFusion: End-to-End Differentiable Reconstruction and Rendering for Unseen Object Pose Estimation \[[paper](https://arxiv.org/pdf/1912.00416.pdf)\] \[[code](https://github.com/NVlabs/latentfusion)\]

[ACCV2020] 3D Object Detection and Pose Estimation of Unseen Objects in Color Images with Local Surface Embeddings \[[paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Pitteri_3D_Object_Detection_and_Pose_Estimation_of_Unseen_Objects_in_ACCV_2020_paper.pdf)\] 

[BMVC2019] Pose from Shape: Deep Pose Estimation for Arbitrary 3D Objects \[[paper](https://arxiv.org/pdf/1906.05105.pdf)\] \[[code](https://github.com/YoungXIAO13/PoseFromShape)\]

[ECCV2018] DeepIM: Deep Iterative Matching for 6D Pose Estimation \[[paper](https://arxiv.org/pdf/1804.00175)\] \[[code](https://github.com/liyi14/mx-DeepIM)\]

[CVPR2015] Learning Descriptors for Object Recognition and 3D Pose Estimation \[[paper](https://arxiv.org/pdf/1502.05908)\]

[ICCV2011] Multimodal templates for real-time detection of texture-less objects in heavily cluttered scenes \[[paper](https://campar.in.tum.de/pub/hinterstoisser2011linemod/hinterstoisser2011linemod.pdf)\]

### NeRF for 6D Object Pose
[ECCV2022] Neural Correspondence Field for Object Pose Estimation \[[paper](https://arxiv.org/abs/2208.00113)\] \[[project](https://linhuang17.github.io/NCF/)\] \[[code](https://github.com/LinHuang17/NCF-code)\]

[ECCV2022] Neural-Sim: Learning to Generate Training Data with NeRF \[[paper](https://arxiv.org/abs/2207.11368)\] \[[code](https://github.com/gyhandy/Neural-Sim-NeRF)\]

[ICRA2022] NeRF-Supervision: Learning Dense Object Descriptors from Neural Radiance Fields \[[paper](https://arxiv.org/pdf/2203.01913.pdf)\] \[[code](https://github.com/yenchenlin/nerf-supervision-public)\]

[ArXiv2022] NeRF-Pose: A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation \[[paper](https://arxiv.org/pdf/2203.04802.pdf)\]

[ArXiv2021] Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation \[[paper](https://yilundu.github.io/ndf/)\]

[IROS2021] iNeRF Inverting Neural Radiance Fields for Pose Estimation \[[paper](https://arxiv.org/pdf/2012.05877.pdf)\] \[[code](https://github.com/yenchenlin/iNeRF-public)\]




