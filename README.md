# CVPR 2022 论文和开源项目合集(Papers with Code)

[CVPR 2022](https://cvpr2022.thecvf.com/) 论文和开源项目合集(papers with code)！

CVPR 2022 收录列表ID：https://drive.google.com/file/d/15JFhfPboKdUcIH9LdbCMUFmGq_JhaxhC/view

> 注1：欢迎各位大佬提交issue，分享CVPR 2022论文和开源项目！
>
> 注2：关于往年CV顶会论文以及其他优质CV论文和大盘点，详见： https://github.com/amusi/daily-paper-computer-vision
>
> - [CVPR 2019](CVPR2019-Papers-with-Code.md)
> - [CVPR 2020](CVPR2020-Papers-with-Code.md)
> - [CVPR 2021](CVPR2021-Papers-with-Code.md)

如果你想了解最新最优质的的CV论文、开源项目和学习资料，欢迎扫码加入【CVer学术交流群】！互相学习，一起进步~ 

![](CVer学术交流群.png)

## 【CVPR 2022 论文开源目录】

- [Backbone](#Backbone)
- [CLIP](#CLIP)
- [NAS](#NAS)
- [NeRF](#NeRF)
- [Visual Transformer](#Visual-Transformer)
- [自监督学习(Self-supervised Learning)](#SSL)
- [数据增强(Data Augmentation)](#DA)
- [目标检测(Object Detection)](#Object-Detection)
- [目标跟踪(Visual Tracking)](#VT)
- [语义分割(Semantic Segmentation)](#Semantic-Segmentation)
- [实例分割(Instance Segmentation)](#Instance-Segmentation)
- [视频理解(Video Understanding)](#VU)
- [图像编辑(Image Editing)](#Image-Editing)
- [Low-level Vision](#LLV)
- [超分辨率(Super-Resolution)](#Super-Resolution)
- [3D点云(3D Point Cloud)](#3D-Point-Cloud)
- [3D目标检测(3D Object Detection)](#3D-Object-Detection)
- [3D目标跟踪(3D Object Tracking)](#3D-Object-Tracking)
- [3D人体姿态估计(3D Human Pose Estimation)](#3D-Human-Pose-Estimation)
- [3D语义场景补全(3D Semantic Scene Completion)](#3DSSC)
- [3D重建(3D Reconstruction)](#3D-R)
- [深度估计(Depth Estimation)](#Depth-Estimation)
- [立体匹配(Stereo Matching)](#Stereo-Matching)
- [车道线检测(Lane Detection)](#Lane-Detection)
- [图像修复(Image Inpainting)](#Image-Inpainting)
- [人群计数(Crowd Counting)](#Crowd-Counting)
- [医学图像(Medical Image)](#Medical-Image)
- [场景图生成(Scene Graph Generation)](#Scene-Graph-Generation)
- [高光谱图像重建(Hyperspectral Image Reconstruction)](#HSI)
- [水印(Watermarking)](#Watermarking)
- [数据集(Datasets)](#Datasets)
- [新任务(New Tasks)](#New-Tasks)
- [其他(Others)](#Others)

<a name="Backbone"></a>

# Backbone

**A ConvNet for the 2020s**

- Paper: https://arxiv.org/abs/2201.03545

- Code: https://github.com/facebookresearch/ConvNeXt
- 中文解读：https://mp.weixin.qq.com/s/Xg5wPYExnvTqRo6s5-2cAw

**MPViT : Multi-Path Vision Transformer for Dense Prediction**

- Paper: https://arxiv.org/abs/2112.11010

- Code: https://github.com/youngwanLEE/MPViT

<a name="CLIP"></a>

# CLIP

**HairCLIP: Design Your Hair by Text and Reference Image**

- Paper: https://arxiv.org/abs/2112.05142

- Code: https://github.com/wty-ustc/HairCLIP

**PointCLIP: Point Cloud Understanding by CLIP**

- Paper: https://arxiv.org/abs/2112.02413
- Code: https://github.com/ZrrSkywalker/PointCLIP

**Blended Diffusion for Text-driven Editing of Natural Images**

- Paper: https://arxiv.org/abs/2111.14818

- Code: https://github.com/omriav/blended-diffusion

<a name="NAS"></a>

# NAS

**ISNAS-DIP: Image-Specific Neural Architecture Search for Deep Image Prior**

- Paper: https://arxiv.org/abs/2111.15362
- Code: None

<a name="NeRF"></a>

# NeRF

**Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields**

- Homepage: https://jonbarron.info/mipnerf360/
- Paper: https://arxiv.org/abs/2111.12077

- Demo: https://youtu.be/YStDS2-Ln1s

**Point-NeRF: Point-based Neural Radiance Fields**

- Homepage: https://xharlie.github.io/projects/project_sites/pointnerf/
- Paper: https://arxiv.org/abs/2201.08845
- Code: https://github.com/Xharlie/point-nerf

**NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images**

- Paper: https://arxiv.org/abs/2111.13679
- Homepage: https://bmild.github.io/rawnerf/

- Demo: https://www.youtube.com/watch?v=JtBS4KBcKVc

<a name="Visual-Transformer"></a>

# Visual Transformer

## Backbone

**MPViT : Multi-Path Vision Transformer for Dense Prediction**

- Paper: https://arxiv.org/abs/2112.11010

- Code: https://github.com/youngwanLEE/MPViT

## 应用(Application)

**Language-based Video Editing via Multi-Modal Multi-Level Transformer**

- Paper: https://arxiv.org/abs/2104.01122
- Code: None

**MixSTE: Seq2seq Mixed Spatio-Temporal Encoder for 3D Human Pose Estimation in Video**

- Paper: https://arxiv.org/abs/2203.00859
- Code: None

**Embracing Single Stride 3D Object Detector with Sparse Transformer**

- Paper: https://arxiv.org/abs/2112.06375
- Code: https://github.com/TuSimple/SST

**Multi-class Token Transformer for Weakly Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.02891
- Code: https://github.com/xulianuwa/MCTformer

**Spatio-temporal Relation Modeling for Few-shot Action Recognition**

- Paper: https://arxiv.org/abs/2112.05132
- Code: https://github.com/Anirudh257/strm

**Mask-guided Spectral-wise Transformer for Efficient Hyperspectral Image Reconstruction**

- Paper: https://arxiv.org/abs/2111.07910
- Code: https://github.com/caiyuanhao1998/MST

**Point-BERT: Pre-training 3D Point Cloud Transformers with Masked Point Modeling**

- Homepage: https://point-bert.ivg-research.xyz/

- Paper: https://arxiv.org/abs/2111.14819
- Code: https://github.com/lulutang0608/Point-BERT

<a name="VLL"></a>

# 视觉和语言(Vision-Language)

**Conditional Prompt Learning for Vision-Language Models**

- Paper: https://arxiv.org/abs/2203.05557
- Code: https://github.com/KaiyangZhou/CoOp

<a name="SSL"></a>

# 自监督学习(Self-supervised Learning)

**Crafting Better Contrastive Views for Siamese Representation Learning**

- Paper: https://arxiv.org/abs/2202.03278
- Code: https://github.com/xyupeng/ContrastiveCrop
- 中文解读：https://mp.weixin.qq.com/s/VTP9D5f7KG9vg30U9kVI2A

**HCSC: Hierarchical Contrastive Selective Coding**

- Homepage: https://github.com/gyfastas/HCSC
- Paper: https://arxiv.org/abs/2202.00455

- 中文解读: https://mp.weixin.qq.com/s/jkYR8mYp-e645qk8kfPNKQ

<a name="DA"></a>

# 数据增强(Data Augmentation)

**TeachAugment: Data Augmentation Optimization Using Teacher Knowledge**

- Paper: https://arxiv.org/abs/2202.12513
- Code: https://github.com/DensoITLab/TeachAugment

**AlignMix: Improving representation by interpolating aligned features**

- Paper: https://arxiv.org/abs/2103.15375
- Code: None

<a name="Object-Detection"></a>

# 目标检测(Object Detection)

**DN-DETR: Accelerate DETR Training by Introducing Query DeNoising**

- Paper: https://arxiv.org/abs/2203.01305
- Code: https://github.com/FengLi-ust/DN-DETR

**Localization Distillation for Dense Object Detection**

- Paper: https://arxiv.org/abs/2102.12252
- Code: https://github.com/HikariTJU/LD
- Code2: https://github.com/HikariTJU/LD
- 中文解读：https://mp.weixin.qq.com/s/dxss8RjJH283h6IbPCT9vg

**Focal and Global Knowledge Distillation for Detectors**

- Paper: https://arxiv.org/abs/2111.11837

- Code: https://github.com/yzd-v/FGD
- 中文解读：https://mp.weixin.qq.com/s/yDkreTudC8JL2V2ETsADwQ

<a name="VT"></a>

# 目标跟踪(Visual Tracking)

**Correlation-Aware Deep Tracking**

- Paper: https://arxiv.org/abs/2203.01666
- Code: None

**TCTrack: Temporal Contexts for Aerial Tracking**

- Paper: https://arxiv.org/abs/2203.01885

- Code: https://github.com/vision4robotics/TCTrack

<a name="Semantic-Segmentation"></a>

# 语义分割(Semantic Segmentation)

## 弱监督语义分割

**Class Re-Activation Maps for Weakly-Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.00962
- Code: https://github.com/zhaozhengChen/ReCAM

**Multi-class Token Transformer for Weakly Supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2203.02891
- Code: https://github.com/xulianuwa/MCTformer

## 半监督语义分割

**ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation**

- Paper: https://arxiv.org/abs/2106.05095
- Code: https://github.com/LiheYoung/ST-PlusPlus
- 中文解读：https://mp.weixin.qq.com/s/knSnlebdtEnmrkChGM_0CA

**Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels**

- Homepage: https://haochen-wang409.github.io/U2PL/
- Paper: https://arxiv.org/abs/2203.03884

- Code: https://github.com/Haochen-Wang409/U2PL
- 中文解读: https://mp.weixin.qq.com/s/-08olqE7np8A1XQzt6HAgQ

<a name="Instance-Segmentation"></a>

# 实例分割(Instance Segmentation)

**E2EC: An End-to-End Contour-based Method for High-Quality High-Speed Instance Segmentation**

- Paper: https://arxiv.org/abs/2203.04074
- Code: https://github.com/zhang-tao-whu/e2ec

## 自监督实例分割

**FreeSOLO: Learning to Segment Objects without Annotations**

- Paper: https://arxiv.org/abs/2202.12181
- Code: None

## 视频实例分割

**Efficient Video Instance Segmentation via Tracklet Query and Proposal**

- Homepage: https://jialianwu.com/projects/EfficientVIS.html
- Paper: https://arxiv.org/abs/2203.01853
- Demo: https://youtu.be/sSPMzgtMKCE

<a name="VU"></a>

# 视频理解(Video Understanding)

## 行为识别(Action Recognition)

**Spatio-temporal Relation Modeling for Few-shot Action Recognition**

- Paper: https://arxiv.org/abs/2112.05132
- Code: https://github.com/Anirudh257/strm

<a name="Image-Editing"></a>

# 图像编辑(Image Editing)

**Blended Diffusion for Text-driven Editing of Natural Images**

- Paper: https://arxiv.org/abs/2111.14818

- Code: https://github.com/omriav/blended-diffusion

<a name="LLV"></a>

# Low-level Vision

**ISNAS-DIP: Image-Specific Neural Architecture Search for Deep Image Prior**

- Paper: https://arxiv.org/abs/2111.15362
- Code: None

<a name="Super-Resolution"></a>

# 超分辨率(Super-Resolution)

## 图像超分辨率(Image Super-Resolution)

**Learning the Degradation Distribution for Blind Image Super-Resolution**

- Paper: https://arxiv.org/abs/2203.04962
- Code: https://github.com/greatlog/UnpairedSR

## 视频超分辨率(Video Super-Resolution)

**BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment**

- Paper: https://arxiv.org/abs/2104.13371
- Code: https://github.com/open-mmlab/mmediting
- Code: https://github.com/ckkelvinchan/BasicVSR_PlusPlus
- 中文解读：https://mp.weixin.qq.com/s/HZTwYfphixyLHxlbCAxx4g

<a name="3D-Point-Cloud"></a>

# 3D点云(3D Point Cloud)

**Point-BERT: Pre-training 3D Point Cloud Transformers with Masked Point Modeling**

- Homepage: https://point-bert.ivg-research.xyz/

- Paper: https://arxiv.org/abs/2111.14819
- Code: https://github.com/lulutang0608/Point-BERT

**A Unified Query-based Paradigm for Point Cloud Understanding**

- Paper: https://arxiv.org/abs/2203.01252
- Code: None 

**CrossPoint: Self-Supervised Cross-Modal Contrastive Learning for 3D Point Cloud Understanding**

- Paper: https://arxiv.org/abs/2203.00680
- Code: https://github.com/MohamedAfham/CrossPoint

**PointCLIP: Point Cloud Understanding by CLIP**

- Paper: https://arxiv.org/abs/2112.02413
- Code: https://github.com/ZrrSkywalker/PointCLIP

<a name="3D-Object-Detection"></a>

# 3D目标检测(3D Object Detection)

**Embracing Single Stride 3D Object Detector with Sparse Transformer**

- Paper: https://arxiv.org/abs/2112.06375

- Code: https://github.com/TuSimple/SST

**Canonical Voting: Towards Robust Oriented Bounding Box Detection in 3D Scenes** 

- Paper: https://arxiv.org/abs/2011.12001
- Code: https://github.com/qq456cvb/CanonicalVoting

<a name="3D-Object-Tracking"></a>

# 3D目标跟踪(3D Object Tracking)

**Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds**

- Paper: https://arxiv.org/abs/2203.01730
- Code: https://github.com/Ghostish/Open3DSOT

<a name="3D-Human-Pose-Estimation"></a>

# 3D人体姿态估计(3D Human Pose Estimation)

**MHFormer: Multi-Hypothesis Transformer for 3D Human Pose Estimation**

- Paper: https://arxiv.org/abs/2111.12707

- Code: https://github.com/Vegetebird/MHFormer

- 中文解读: https://zhuanlan.zhihu.com/p/439459426

**MixSTE: Seq2seq Mixed Spatio-Temporal Encoder for 3D Human Pose Estimation in Video**

- Paper: https://arxiv.org/abs/2203.00859
- Code: None

<a name="3DSSC"></a>

# 3D语义场景补全(3D Semantic Scene Completion)

**MonoScene: Monocular 3D Semantic Scene Completion**

- Paper: https://arxiv.org/abs/2112.00726
- Code: https://github.com/cv-rits/MonoScene

<a name="3D-R"></a>

# 3D重建(3D Reconstruction)

**BANMo: Building Animatable 3D Neural Models from Many Casual Videos**

- Homepage: https://banmo-www.github.io/
- Paper: https://arxiv.org/abs/2112.12761
- Code: https://github.com/facebookresearch/banmo
- 中文解读：https://mp.weixin.qq.com/s/NMHP8-xWwrX40vpGx55Qew

<a name="Depth-Estimation"></a>

# 深度估计(Depth Estimation)

## 单目深度估计

**NeW CRFs: Neural Window Fully-connected CRFs for Monocular Depth Estimation**

- Paper: https://arxiv.org/abs/2203.01502
- Code: None

**OmniFusion: 360 Monocular Depth Estimation via Geometry-Aware Fusion**

- Paper: https://arxiv.org/abs/2203.00838
- Code: None

**Toward Practical Self-Supervised Monocular Indoor Depth Estimation**

- Paper: https://arxiv.org/abs/2112.02306
- Code: None

<a name="Stereo-Matching"></a>

# 立体匹配(Stereo Matching)

**ACVNet: Attention Concatenation Volume for Accurate and Efficient Stereo Matching**

- Paper: https://arxiv.org/abs/2203.02146
- Code: https://github.com/gangweiX/ACVNet

<a name="Lane-Detection"></a>

# 车道线检测(Lane Detection)

**Rethinking Efficient Lane Detection via Curve Modeling**

- Paper: https://arxiv.org/abs/2203.02431

- Code: https://github.com/voldemortX/pytorch-auto-drive

- Demo：https://user-images.githubusercontent.com/32259501/148680744-a18793cd-f437-461f-8c3a-b909c9931709.mp4

<a name="Image-Inpainting"></a>

# 图像修复(Image Inpainting)

**Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding**

- Paper: https://arxiv.org/abs/2203.00867

- Code: https://github.com/DQiaole/ZITS_inpainting

<a name="Crowd-Counting"></a>

# 人群计数(Crowd Counting)

**Leveraging Self-Supervision for Cross-Domain Crowd Counting**

- Paper: https://arxiv.org/abs/2103.16291
- Code: None

<a name="Medical-Image"></a>

# 医学图像(Medical Image)

**BoostMIS: Boosting Medical Image Semi-supervised Learning with Adaptive Pseudo Labeling and Informative Active Annotation**

- Paper: https://arxiv.org/abs/2203.02533
- Code: None

<a name="Scene-Graph-Generation"></a>

# 场景图生成(Scene Graph Generation)

 **SGTR: End-to-end Scene Graph Generation with Transformer**

- Paper: https://arxiv.org/abs/2112.12970
- Code: None

<a name="ST"></a>

# 风格迁移(Style Transfer)

**StyleMesh: Style Transfer for Indoor 3D Scene Reconstructions**

- Homepage: https://lukashoel.github.io/stylemesh/
- Paper: https://arxiv.org/abs/2112.01530

- Code: https://github.com/lukasHoel/stylemesh
- Demo：https://www.youtube.com/watch?v=ZqgiTLcNcks

<a name="HSI"></a>

# 高光谱图像重建(Hyperspectral Image Reconstruction)

**Mask-guided Spectral-wise Transformer for Efficient Hyperspectral Image Reconstruction**

- Paper: https://arxiv.org/abs/2111.07910
- Code: https://github.com/caiyuanhao1998/MST

<a name="Watermarking"></a>

# 水印(Watermarking)

**Deep 3D-to-2D Watermarking: Embedding Messages in 3D Meshes and Extracting Them from 2D Renderings**

- Paper: https://arxiv.org/abs/2104.13450
- Code: None

<a name="Datasets"></a>

# 数据集(Datasets)

**It's About Time: Analog Clock Reading in the Wild**

- Homepage: https://charigyang.github.io/abouttime/
- Paper: https://arxiv.org/abs/2111.09162
- Code: https://github.com/charigyang/itsabouttime
- Demo: https://youtu.be/cbiMACA6dRc

**Toward Practical Self-Supervised Monocular Indoor Depth Estimation**

- Paper: https://arxiv.org/abs/2112.02306
- Code: None

**Kubric: A scalable dataset generator**

- Paper: https://arxiv.org/abs/2203.03570

- Code: https://github.com/google-research/kubric

<a name="New-Tasks"></a>

# 新任务(New Task)

**Language-based Video Editing via Multi-Modal Multi-Level Transformer**

- Paper: https://arxiv.org/abs/2104.01122
- Code: None

**It's About Time: Analog Clock Reading in the Wild**

- Homepage: https://charigyang.github.io/abouttime/
- Paper: https://arxiv.org/abs/2111.09162

- Code: https://github.com/charigyang/itsabouttime

- Demo: https://youtu.be/cbiMACA6dRc

<a name="Others"></a>

# 其他(Others)

**Kubric: A scalable dataset generator**

- Paper: https://arxiv.org/abs/2203.03570

- Code: https://github.com/google-research/kubric
