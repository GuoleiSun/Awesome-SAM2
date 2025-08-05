# Awesome SAM2 ( Segment Anything in Images and Videos)
This repo aims to include materials (papers, codes, slides) about [SAM2](https://arxiv.org/abs/2408.00714) (segment anything in images and videos), <ins>a vision foundation model released by Meta AI </ins>. We are continuously improving the project. Welcome to PR the works (papers, repos) that are missed.

## SAM2

- **[SAM2](https://arxiv.org/abs/2408.00714)**  [🔗 [**Code**](https://github.com/facebookresearch/segment-anything-2) | 🖥️ [**Demo**](https://sam2.metademolab.com/) | 📖 [**Explanation**](https://www.sievedata.com/blog/meta-segment-anything-2-sam2-introduction)]
- **[SAM](https://arxiv.org/abs/2304.02643)**  [🔗 [**Code**](https://github.com/facebookresearch/segment-anything) | 🖥️ [**Demo**](https://segment-anything.com/) | 📖 [**Explanation**](https://www.v7labs.com/blog/segment-anything-model-sam)]


## Contents
- [Surveys & Reviews](#surveys--reviews)
- [Traditional Segmentation Tasks](#traditional-segmentation)
    - [Image Segmentation](#image-segmentation)
        - [Segmentation Applications](#segmentation-applications)
        - [Other Image Tasks](#other-image-tasks)
    - [Video Segmentation](#video-segmentation)
        - [Referring/Reasoning Video Object Segmentation](#referringreasoning-video-object-segmentation)
    - [Other Video Tasks](#other-video-tasks)
- [Medical Domain](#medical-domain)
    - [Medical Video & 3D Segmentation](#medical-video--3d-segmentation)
    - [Medical Image Segmentation](#medical-image-segmentation)
    - [Other Medical Applications](#other-medical-applications)
- [Camouflaged Object Detection (COD)](#camouflaged-object-detection-cod)
  - [Video COD](#video-cod)
  - [Image COD](#image-cod)
- [Audio-visual segmentation (AVS)](#audio-visual-segmentation-avs)
- [Remote Sensing](#remote-sensing)
- [Mesh or Point Cloud / 3D Processing](#mesh-or-point-cloud--3d-processing)
    - [Mesh or Point Cloud Segmentation](#mesh-or-point-cloud-segmentation)
    - [Mesh or Point Cloud Reconstruction](#mesh-or-point-cloud-reconstruction)
    - [Other Applications](#other-applications)
- [Image or Video Generation & Editing](#image-or-video-generation--editing)
- [Simultaneous Localization and Mapping (SLAM / VO)](#simultaneous-localization-and-mapping-slam--vo)
- [Light Field Segmentation](#light-field-segmentation)
- [Robotics](#robotics)
- [Adaptation, Compression & Edge Applications](#adaptation-compression--edge-applications)
- [Training](#training)
    - [Datasets](#datasets)
    - [Used for Data Augmentation (/Tool)](#used-for-data-augmentation-tool)
    - [Training Helper](#training-helper)
- [Performance Evaluations](#performance-evaluations)
    - [Post Processing](#post-processing)
- [Robustness](#robustness)
- [Unique Applications/Usage](#unique-applicationsusage)

## Papers/Projects

### **Surveys & Reviews**
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.07 | [Segment Anything for Videos: A Systematic Survey](https://arxiv.org/abs/2408.08315) | [📖 Repo](https://github.com/983632847/SAM-for-Videos) |
| 2024.08 | [Unleashing the Potential of SAM2 for Biomedical Images and Videos: A Survey](https://arxiv.org/abs/2408.12889) | [📖 Repo](https://github.com/YichiZhang98/SAM4MIS) |
| 2024.10 | [On Efficient Variants of Segment Anything Model: A Survey](https://arxiv.org/abs/2410.04960) | NA |
| 2025.03 | [SAM2 for Image and Video Segmentation: A Comprehensive Survey](https://arxiv.org/pdf/2503.12781)  | NA |
| 2025.07 | [Survey on deep learning-based weakly supervised salient object detection](https://www.sciencedirect.com/science/article/abs/pii/S0957417425011194) | NA |
<!-- | 2023.12 | [Large Scale Foundation Models for Intelligent Manufacturing Applications: A Survey](https://arxiv.org/abs/2312.06718) | [📖 Repo](https://github.com/NEUFS-MA/LSFMs-IM) | -->

### Traditional Segmentation
#### Image Segmentation
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.10 | [Towards Natural Image Matting in the Wild via Real-Scenario Prior](https://arxiv.org/abs/2410.06593) | [🔗 Code](https://github.com/XiaRho/SEMat) |
| 2024.11 | [CorrCLIP: Reconstructing Correlations in CLIP with Off-the-Shelf Foundation Models for Open-Vocabulary Semantic Segmentation](https://arxiv.org/abs/2411.10086) | NA |
| 2025.03 | [Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement](https://arxiv.org/pdf/2503.06520) | [🌐Project page](https://github.com/dvlab-research/Seg-Zero) | 
| 2025.04 | [MGD-SAM2: Multi-view Guided Detail-enhanced Segment Anything Model 2 for High-Resolution Class-agnostic Segmentation](https://arxiv.org/pdf/2503.23786) | [🔗 Code](https://github.com/sevenshr/MGD-SAM2)|
| 2025.04 | [Pixel-SAIL: Single Transformer For Pixel-Grounded Understanding](https://arxiv.org/pdf/2504.10465) | [🌐Project page](https://zhang-tao-whu.github.io/project/pixelsail) |

##### Segmentation Applications
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03 | [Unveiling the Potential of Segment Anything Model 2 for RGB-Thermal Semantic Segmentation with Language Guidance](https://arxiv.org/pdf/2503.02581) | [🔗 Code](https://github.com/iAsakiT3T/SHIFNet) | 
| 2025.03 | [MemorySAM: Memorize Modalities and Semantics with Segment Anything Model 2 for Multi-modal Semantic Segmentation](https://arxiv.org/pdf/2503.06700) | 🕒Soon |
| 2025.03 | [Segment Any-Quality Images with Generative Latent Space Enhancement](https://arxiv.org/pdf/2503.12507) | NA |
| 2025.03 | [Superpowering Open-Vocabulary Object Detectors for X-ray Vision](https://arxiv.org/pdf/2503.17071) | [🔗 Code](https://github.com/PAGF188/RAXO) | 
| 2025.04 | [Semi-automated segmentation of magnitude images in 4D flow MR scans using segment anything model 2 (SAM 2)](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13410/1341026/Semi-automated-segmentation-of-magnitude-images-in-4D-flow-MR/10.1117/12.3051724.short) | NA |
| 2025.04 | [S4M: Boosting Semi-Supervised Instance Segmentation with SAM](https://arxiv.org/pdf/2504.05301) | [🌐Project page](https://cvlab-kaist.github.io/S4M/) |
| 2025.04 | [KAN-SAM: Kolmogorov-Arnold Network Guided Segment Anything Model for RGB-T Salient Object Detection](https://arxiv.org/pdf/2504.05878) | NA |
| 2025.04 | [MovSAM: A Single-image Moving Object Segmentation Framework](https://arxiv.org/pdf/2504.06863) | [🔗 Code](https://github.com/IRMVLab/MovSAM)|
| 2025.04 | [Few-Shot Adaptation of Grounding DINO for Agricultural Domain](https://arxiv.org/pdf/2504.07252) | NA |
| 2025.10 | [SinkSAM-Net: Knowledge-driven self-supervised sinkhole segmentation using topographic priors and Segment Anything Model](https://www.sciencedirect.com/science/article/abs/pii/S0924271625002618) | [🌐Project page](https://osherr1996.github.io/SinkSAMNet/) |

##### Other Image Tasks
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Unleashing the Temporal-Spatial Reasoning Capacity of GPT for Training-Free Audio and Language Referenced Video Object Segmentation](https://arxiv.org/abs/2408.15876) | [🔗 Code](https://github.com/appletea233/AL-Ref-SAM2) |
| 2024.11| [SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation](https://arxiv.org/abs/2411.17646) | [🔗 Code](https://github.com/ClaudiaCuttano/SAMWISE) |
| 2024.11| [SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory](https://arxiv.org/abs/2411.11922) | [🔗 Code](https://github.com/yangchris11/samurai) |
| 2025.02| [Text-Promtable propagation for referring medical image sequence segmentation](https://arxiv.org/abs/2502.11093)| NA|
| 2025.04| [MovSAM: A Single-image Moving Object Segmentation Framework Based on Deep Thinking](https://arxiv.org/pdf/2504.06863) | [🔗 Code](https://github.com/IRMVLab/MovSAM)|
| 2025.05 | [Vision Foundation Model Embedding-Based Semantic Anomaly Detection](https://arxiv.org/pdf/2505.07998) | NA |
| 2025.05 | [Synthetic Data Pre-Training for Runway Damage Assessment](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13459/134590Z/Synthetic-data-pre-training-for-runway-damage-assessment/10.1117/12.3053672.short) | NA |
| 2025.05 | [Single-sided estimates of surface breaking porosity in additive manufacturing using multiple inspection techniques](https://www-spiedigitallibrary-org.remotexs.ntu.edu.sg/conference-proceedings-of-spie/13470/1347013/Single-sided-estimates-of-surface-breaking-porosity-in-additive-manufacturing/10.1117/12.3053745.full) | NA |
| 2025.05 | [TextRegion: Text-Aligned Region Tokens from Frozen Image-Text Models](https://arxiv.org/pdf/2505.23769) | [🔗 Code](https://github.com/avaxiao/TextRegion) |
| 2025.05 | [PixelThink: Towards Efficient Chain-of-Pixel Reasoning](https://arxiv.org/pdf/2505.23727) | [🌐Project page](https://pixelthink.github.io/) | 
| 2025.05 | [SAMamba: Adaptive State Space Modeling with Hierarchical Vision for Infrared Small Target Detection](https://arxiv.org/pdf/2505.23214) | [🔗 Code](https://github.com/zhengshuchen/SAMamba) |
| 2025.06 | [Mask-aware Text-to-Image Retrieval: Referring Expression Segmentation Meets Cross-modal Retrieval](https://dl.acm.org/doi/pdf/10.1145/3731715.3733484) | [🔗 Code](https://github.com/AI-Application-andIntegration-Lab/MaTIR.) |
| 2025.07 | [HFS-SAM2: Segment Anything Model 2 with High-Frequency Feature Supplementation for Camouflaged Object Detection](https://ieeexplore.ieee.org/document/11081899) | [🔗 Code](https://github.com/WZH0120/HFS-SAM2) |



#### Video Segmentation

| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Video Object Segmentation via SAM 2: The 4th Solution for LSVOS Challenge VOS Track](https://arxiv.org/abs/2408.10125) | NA |
| 2024.08| [The 2nd Solution for LSVOS Challenge RVOS Track: Spatial-temporal Refinement for Consistent Semantic Segmentation](https://arxiv.org/abs/2408.12447) | NA |
| 2024.08| [LSVOS Challenge 3rd Place Report: SAM2 and Cutie based VOS](https://arxiv.org/abs/2408.10469) | NA |
| 2024.09| [Temporally Propagated Masks and Boxes: Combining the Best of Both Worlds for Multi-Object Tracking](https://arxiv.org/abs/2409.14220) | NA |
| 2024.10 | [SAM2Long: Enhancing SAM 2 for Long Video Segmentation with a Training-Free Memory Tree](https://arxiv.org/abs/2410.16268) | [🔗 Code](https://github.com/Mark12Ding/SAM2Long) |
| 2024.11| [A Distractor-Aware Memory for Visual Object Tracking with SAM2](https://arxiv.org/abs/2411.17576) | [🔗 Code](https://github.com/jovanavidenovic/DAM4SAM) |
| 2024.11| [There is no SAMantics! Exploring SAM as a Backbone for Visual Understanding Tasks](https://arxiv.org/abs/2411.15288) | [🔗 Code](https://github.com/miquel-espinosa/samantics) |
|2024.12|[VideoRefer Suite: Advancing Spatial-Temporal Object Understanding with Video LLMs](https://arxiv.org/abs/2501.00599)|[🌐Project page](https://damo-nlp-sg.github.io/VideoRefer/)|
| 2025.02| [Towards Fine-grained Interactive Segmentation in Images and Videos](https://arxiv.org/pdf/2502.09660)| NA |
| 2025.03 | [WeGen: A Unified Model for Interactive Multimodal Generation as We Chat](https://arxiv.org/pdf/2503.01115) | [🔗 Code](https://github.com/hzphzp/WeGen)|
| 2025.03 | [Pseudo-LiDAR With Two-Dimensional Instance for Monocular Three-Dimensional Object Tracking](https://ieeexplore.ieee.org/document/10918939) | NA |
| 2025.03 | [WeakMedSAM: Weakly-Supervised Medical Image Segmentation via SAM with Sub-Class Exploration and Prompt Affinity Mining](https://arxiv.org/pdf/2503.04106) | [🔗 Code](https://github.com/wanghr64/WeakMedSAM)|
| 2025.03 | [Segment Any Motion in Videos](https://arxiv.org/pdf/2503.22268) | [🌐Project page](https://motion-seg.github.io/)|
| 2025.03| [MemorySAM: Memorize Modalities and Semantics with Segment Anything Model 2 for Multi-modal Semantic Segmentation](https://arxiv.org/pdf/2503.06700) | [🔗 Code](https://github.com/Chenfei-Liao/MemorySAM) |
| 2025.04 | [SAM2MOT: A Novel Paradigm of Multi-Object Tracking by Segmentation](https://arxiv.org/pdf/2504.04519)| [🔗 Code](https://github.com/TripleJoy/SAM2MOT) |
| 2025.04 | [DC-SAM: In-Context Segment Anything in Images and Videos via Dual Consistency](https://arxiv.org/pdf/2504.12080) | [🔗 Code](https://github.com/zaplm/DC-SAM) |
| 2025.07 | [HiM2SAM: Enhancing SAM2 with Hierarchical Motion Estimation and Memory Optimization towards Long-term Tracking](https://arxiv.org/pdf/2507.07603) | [🔗 Code](https://github.com/LouisFinner/HiM2SAM/tree/main) |


##### Referring/Reasoning Video Object Segmentation 

| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Unleashing the Temporal-Spatial Reasoning Capacity of GPT for Training-Free Audio and Language Referenced Video Object Segmentation](https://arxiv.org/abs/2408.15876) | [🔗 Code](https://github.com/appletea233/AL-Ref-SAM2) |
| 2024.11| [SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation](https://arxiv.org/abs/2411.17646) | [🔗 Code](https://github.com/ClaudiaCuttano/SAMWISE) |
| 2024.11| [SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory](https://arxiv.org/abs/2411.11922) | [🔗 Code](https://github.com/yangchris11/samurai) |
| 2025.02| [Text-Promtable propagation for referring medical image sequence segmentation](https://arxiv.org/abs/2502.11093)| NA|
| 2025.03| [Online Reasoning Video Segmentation with Just-in-Time Digital Twins](https://arxiv.org/pdf/2503.21056) | NA |
| 2025.04 | [The 1st Solution for 4th PVUW MeViS Challenge: Unleashing the Potential of Large Multimodal Models for Referring Video Segmentation](https://arxiv.org/pdf/2504.05178) | NA |
| 2025.04 | [GLUS: Global-Local Reasoning Unified into A Single Large Language Model for Video Segmentation](https://arxiv.org/pdf/2504.07962) | [🌐Project page](https://glus-video.github.io/) |

#### Other Video Tasks
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03 | [MMCD: Memory-Based Multimodal Change Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10889397) | NA |
| 2025.03 | [EgoSplat: Open-Vocabulary Egocentric Scene Understanding with Language Embedded 3D Gaussian Splatting](https://arxiv.org/pdf/2503.11345) | 🕒Soon |
| 2025.03 | [Learning 4D Panoptic Scene Graph Generation from Rich 2D Visual Scene](https://arxiv.org/pdf/2503.15019) | [🌐Project page](https://sqwu.top/PSG-4D-LLM/) |
| 2025.03 | [EgoDTM: Towards 3D-Aware Egocentric Video-Language Pretraining](https://arxiv.org/pdf/2503.15470) | [🔗 Code](https://github.com/xuboshen/EgoDTM)|
| 2025.03 | [High Temporal Consistency through Semantic Similarity Propagation in Semi-Supervised Video Semantic Segmentation for Autonomous Flight](https://arxiv.org/pdf/2503.15676) | [🔗 Code](https://github.com/FraunhoferIVI/SSP)|
| 2025.03 | [FusionSegReID: Advancing Person Re-Identification with Multimodal Retrieval and Precise Segmentation](https://arxiv.org/pdf/2503.21595)| NA |
| 2025.04 | [Segment Any Motion in Videos](https://arxiv.org/pdf/2503.22268) | [🌐Project page](https://motion-seg.github.io/) |
| 2025.05 | [SAM2MOT: A Novel Paradigm of Multi-Object Tracking by Segmentation](https://arxiv.org/pdf/2504.04519) | [🔗 Code](https://github.com/TripleJoy/SAM2MOT) | 
| 2025.04 | [Caption Anything in Video: Fine-grained Object-centric Captioning via Spatiotemporal Multimodal Prompting](https://arxiv.org/pdf/2504.05541) | [🔗 Code](https://github.com/yunlong10/CAT-V) |
| 2025.04 | [How Can Objects Help Video-Language Understanding?](https://arxiv.org/pdf/2504.07454) | 🕒Soon |
| 2025.04 | [SAMJAM:Zero-Shot Video Scene Graph Generation for Egocentric Kitchen Videos](https://arxiv.org/pdf/2504.07867) | NA |
| 2025.05 | [Research on a traffic flow statistical algorithm based on YBOVDT and SAM2](https://www.nature.com/articles/s41598-025-04336-2) | [📊 Data](https://github.com/kill7893/traffic) |
| 2025.05 | [One Trajectory, One Token: Grounded Video Tokenization via Panoptic Sub-object Trajectory](https://arxiv.org/pdf/2505.23617) | NA | 
| 2025.06 | [ConMo: Controllable Motion Disentanglement and Recomposition for Zero-Shot Motion Transfer](https://openaccess.thecvf.com/content/CVPR2025/papers/Gao_ConMo_Controllable_Motion_Disentanglement_and_Recomposition_for_Zero-Shot_Motion_Transfer_CVPR_2025_paper.pdf) | [🔗 Code](https://github.com/Andyplus1/ConMo) |
| 2025.06 | [Track Any Object:A Granular Video Anomaly Detection Pipeline](https://openaccess.thecvf.com/content/CVPR2025/papers/Huang_Track_Any_Anomalous_ObjectA_Granular_Video_Anomaly_Detection_Pipeline_CVPR_2025_paper.pdf) | [🌐Project page](https://tao-25.github.io/) |
| 2025.06 | [Open-World Object Counting in Videos](https://arxiv.org/pdf/2506.15368) | [🔗 Code](https://github.com/niki-amini-naieni/CountVid/) |
| 2025.06 | [Scene-R1: Video-Grounded Large Language Models for 3D Scene Reasoning without 3D Annotations](https://arxiv.org/pdf/2506.17545) | NA |
| 2025.06 | [SAM2RL:Towards Reinforcement Learning Memory Control in Segment Anything Model 2](https://openreview.net/pdf?id=nikfkVtih1) | NA |
| 2025.07 | [Visual tracking by matching points using diffusion model](https://www.sciencedirect.com/science/article/pii/S1110016825007914) | [🔗 Code](https://github.com/HamadYA/Stable-SAM2)|
| 2025.07 | [Intelligent and quantitative ligament breakup event analysis in 65 kHz off-axis holographic video of swirl spray](https://www.sciencedirect.com/science/article/abs/pii/S0301932225002150) | [🔗 Code](https://github.com/qm0426/Automatic-ligament-breakup-event-analysis) |
| 2025.07 | [Towards Blind Bitstream-corrupted Video Recovery: AVisual Foundation Model-driven Framework](https://arxiv.org/pdf/2507.22481) | NA |
| 2025.07 | [SAMITE: Position Prompted SAM2 with Calibrated Memory for Visual Object Tracking](https://arxiv.org/pdf/2507.21732) | [🔗 Code](https://github.com/Sam1224/SAMITE) |

### Audio-visual segmentation (AVS)
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [Audio visual segmentation through text embeddings](https://arxiv.org/pdf/2502.16359) | NA|


### Medical Domain

#### Medical Video & 3D Segmentation

| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Segment anything in medical images and videos: Benchmark and deployment](https://arxiv.org/abs/2408.03322) | [🔗 Code](https://github.com/bowang-lab/MedSAM) |
| 2024.08 | [SAM 2 in Robotic Surgery: An Empirical Evaluation for Robustness and Generalization in Surgical Video Segmentation](https://arxiv.org/abs/2408.04593) | NA|
| 2024.08| [Performance and Non-adversarial Robustness of the Segment Anything Model 2 in Surgical Video Segmentation](https://arxiv.org/abs/2408.04098) | NA |
| 2024.08| [Novel adaptation of video segmentation to 3D MRI: efficient zero-shot knee segmentation with SAM2](https://arxiv.org/abs/2408.04762) | NA |
| 2024.08| [Biomedical SAM 2: Segment anything in biomedical images and videos](https://arxiv.org/abs/2408.03286) | [🔗 Code](https://github.com/ZhilingYan/Biomedical-SAM-2) |
| 2024.08| [Polyp SAM 2: Advancing Zero-shot Polyp Segmentation in Colorectal Cancer Detection](https://arxiv.org/abs/2408.05892) | [🔗 Code](https://github.com/sajjad-sh33/Polyp-SAM-2) |
| 2024.08 | [Surgical SAM 2: Real-time Segment Anything in Surgical Video by Efficient Frame Pruning](https://arxiv.org/abs/2408.07931) | [🔗 Code](https://github.com/jinlab-imvr/Surgical-SAM-2) |
| 2024.08| [Performance and Non-adversarial Robustness of the Segment Anything Model 2 in Surgical Video Segmentation](https://arxiv.org/abs/2408.04098) | NA |
| 2024.09| [SAM-OCTA2: Layer Sequence OCTA Segmentation with Fine-tuned Segment Anything Model 2](https://arxiv.org/abs/2409.09286) | [🔗 Code](https://github.com/ShellRedia/SAM-OCTA2) |
| 2024.09| [Self-Prompting Polyp Segmentation in Colonoscopy using Hybrid Yolo-SAM 2 Model](https://arxiv.org/abs/2409.09484) | [🔗 Code](https://github.com/sajjad-sh33/YOLO_SAM2) |
| 2024.10| [A-MFST: Adaptive Multi-Flow Sparse Tracker for Real-Time Tissue Tracking Under Occlusion](https://arxiv.org/abs/2410.19996) | NA |
| 2024.10 |[ECHOPulse: ECG controlled echocardio-grams video generation](https://arxiv.org/abs/2410.03143) |[🔗 Code](https://github.com/levyisthebest/ECHOPulse_Prelease)|
| 2024.11| [Phase-Informed Tool Segmentation for Manual Small-Incision Cataract Surgery](https://arxiv.org/abs/2411.16794) | NA |
| 2025.02| [SASVi - Segment Any Surgical Video](https://arxiv.org/abs/2502.09653)| [🔗 Code](https://github.com/MECLabTUDA/SASVi) |
| 2025.02| [Less is More? Revisiting the Importance of Frame Rate in Real-Time Zero-Shot Surgical Video Segmentation ](https://arxiv.org/pdf/2502.20934)| | 
| 2025.03 | [SurgiSAM2: Fine-tuning a foundational model for surgical video anatomy segmentation and detection](https://arxiv.org/pdf/2503.03942) | [🔗 Code(& dataset)](https://github.com/Devanish31/SurgiSAM2) |
| 2025.03 | [Surgical Gaussian Surfels: Highly Accurate Real-time Surgical Scene Rendering](https://arxiv.org/pdf/2503.04079) | [🔗 Code](https://github.com/aloma85/SurgicalGaussianSurfels) |
| 2025.03 | [Rethinking Few-Shot Medical Image Segmentation by SAM2: A Training-Free Framework with Augmentative Prompting and Dynamic Matching](https://arxiv.org/pdf/2503.04826) | NA |
| 2025.03 | [Self-Prompting Driven SAM2 for 3D Medical Image Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10889344) | NA |
| 2025.04 | [RP-SAM2: Refining Point Prompts for Stable Surgical Instrument Segmentation](https://arxiv.org/pdf/2504.07117) | [🔗 Code](https://github.com/BioMedIA-MBZUAI/RP-SAM2)|
| 2025.04 | [Agglomerating Large Vision Encoders via Distillation for VFSS Segmentation](https://arxiv.org/pdf/2504.02351) | NA |
| 2025.04 | [MedSAM2: Segment Anything in 3D Medical Images and Videos](https://arxiv.org/pdf/2504.03600) | [🔗 Code](https://github.com/bowang-lab/MedSAM2) |
| 2025.05 | [Synergistic Bleeding Region and Point Detection in Laparoscopic Surgical Videos](https://arxiv.org/pdf/2503.22174) | 🕒Soon |
| 2025.05 | [Adapting Segment Anything 2 for Diabetic Retinopathy Lesion Segmentation](https://ieeexplore.ieee.org/document/10981048/) | NA |
| 2025.07 | [Beyond Rigid AI: Towards Natural Human-Machine Symbiosis for Interoperative Surgical Assistance](https://arxiv.org/pdf/2507.23088) | NA |
| 2025.07 | [Towards Affordable Tumor Segmentation and Visualization for 3D Breast MRI Using SAM2](https://arxiv.org/pdf/2507.23272) | NA |

#### Medical Image Segmentation

| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [SAM & SAM 2 in 3D Slicer: SegmentWithSAM Extension for Annotating Medical Images](https://arxiv.org/abs/2408.15224) | [🔗 Code](https://github.com/mazurowski-lab/SlicerSegmentWithSAM) |
| 2024.08| [SAM2-PATH: A better segment anything model for semantic segmentation in digital pathology](https://arxiv.org/abs/2408.03651) | [🔗 Code](https://github.com/simzhangbest/SAM2PATH) |
| 2024.08| [Is SAM 2 Better than SAM in Medical Image Segmentation?](https://arxiv.org/abs/2408.04212) | NA |
| 2024.08| [A Short Review and Evaluation of SAM2's Performance in 3D CT Image Segmentation](https://arxiv.org/abs/2408.11210) | [🔗 Code](https://github.com/Project-MONAI/VISTA) |
| 2024.08| [Interactive 3D Medical Image Segmentation](https://arxiv.org/abs/2408.02635) | [🔗 Code](https://github.com/Chuyun-Shen/SAM_2_Medical_3D) |
| 2024.08| [SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation](https://arxiv.org/abs/2408.08870) | [🔗 Code](https://github.com/WZH0120/SAM2-UNet) |
| 2024.08| [SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More](https://arxiv.org/abs/2408.04579) | [🔗 Code](http://tianrun-chen.github.io/SAM-Adaptor/) |
| 2024.08| [Retrieval-augmented Few-shot Medical Image Segmentation with Foundation Models](https://arxiv.org/abs/2408.08813) |  |
| 2024.10| [SAM-Swin: SAM-Driven Dual-Swin Transformers with Adaptive Lesion Enhancement for Laryngo-Pharyngeal Tumor Detection](https://arxiv.org/abs/2410.21813) | [🔗 Code](https://github.com/VVJia/SAM-Swin) |
| 2024.11| [A multi-task learning model for clinically interpretable sesamoiditis grading](https://www.sciencedirect.com/science/article/pii/S0010482524012642) | NA |
| 2024.11| [Zero-shot capability of SAM-family models for bone segmentation in CT scans](https://arxiv.org/abs/2411.08629) | NA |
| 2024.11| [SAM-I2I: Unleash the Power of Segment Anything Model for Medical Image Translation](https://arxiv.org/abs/2411.12755) | NA |
| 2024.12| [Medical SAM 2: Segment Medical Images As Video Via Segment Anything Model 2](https://arxiv.org/abs/2408.00874) | [🔗 Code](https://github.com/MedicineToken/Medical-SAM2?tab=readme-ov-file) |
| 2025.03| [Self-Prompting Driven SAM2 for 3D Medical Image Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10889344) | NA |
| 2025.03 | [Research on recognition of diabetic retinopathy hemorrhage lesions based on fine tuning of segment anything model](https://www.nature.com/articles/s41598-025-92665-7) | NA |
| 2025.03 | [RP-SAM2: Refining Point Prompts for Stable Surgical Instrument Segmentation](https://arxiv.org/pdf/2504.07117) | [🔗 Code](https://github.com/BioMedIA-MBZUAI/RP-SAM2) |
| 2025.04 | [HRMedSeg: Unlocking High-resolution Medical Image segmentation via Memory-efficient Attention Modeling](https://arxiv.org/pdf/2504.06205) | [🔗 Code](https://github.com/xq141839/HRMedSeg) |
| 2025.04 | [Prompt Once, Segment Everything: Leveraging SAM 2 Potential for Infinite Medical Image Segmentation with a Single Prompt](https://www.mdpi.com/1999-4893/18/4/227) | [🔗 Code](https://github.com/i3uex/prompt_once_segment_everything_code) |
| 2025.05 | [ReSurgSAM2: Referring Segment Anything in Surgical Video via Credible Long-term Tracking](https://arxiv.org/pdf/2505.08581) | [🔗 Code](https://github.com/jinlab-imvr/ReSurgSAM2) | 
| 2025.06 | [MorphSAM: Learning the Morphological Prompts from Atlases for Spine Image Segmentation](https://arxiv.org/pdf/2506.13094) | NA |
| 2025.06 | [SynPo: Boosting Training-Free Few-Shot Medical Segmentation via High-Quality Negative Prompts](https://arxiv.org/pdf/2506.15153) | [🌐Project page](https://liu-yufei.github.io/synpo-project-page/) |
| 2025.06 | [Detection of Breast Cancer Lumpectomy Margin with SAM-incorporated Forward-Forward Contrastive Learning](https://arxiv.org/pdf/2506.21006) | [🔗 Code](https://github.com/tbwa233/FFCL-SAM/) |
| 2025.07 | [Speckle2Self: Self-Supervised Ultrasound Speckle Reduction Without Clean Data](https://arxiv.org/pdf/2507.06828) | 🕒Soon |

#### Other Medical Applications  
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03| [Flip Learning: Weakly supervised erase to segment nodules in breast ultrasound](https://www.sciencedirect.com/science/article/abs/pii/S1361841525000994) | NA | 
| 2025.03 | [From Monocular Vision to Autonomous Action:Guiding Tumor Resection via 3D Reconstruction](https://arxiv.org/pdf/2503.16263)| NA |
| 2025.03 | [Operating Room Workflow Analysis via Reasoning Segmentation over Digital Twins](https://arxiv.org/pdf/2503.21054) | NA |
|2025.03 | [Early Detection and Classification of Lung Cancer using Segment Anything Model 2 and Dense Net](https://www.researchgate.net/publication/390639307_Early_Detection_and_Classification_of_Lung_Cancer_using_Segment_Anything_Model_2_and_Dense_Net) | NA |
| 2025.04 | [Zero-Shot 4D Lidar Panoptic Segmentation](https://arxiv.org/pdf/2504.00848) | NA |
| 2025.04 | [SYNTHFM: Training Modality-Agnostic Foundation Models for Medical Image Segmentation Without Real Medical Data](https://arxiv.org/pdf/2504.08177) | NA |
| 2025.04 | [VoxelFeat: Voxel-wise foundation model features](https://openreview.net/pdf/9707b7d2fbd6be892e47b8acebf0f5e8c70c497c.pdf) | NA |
| 2025.06 | [Leadership Assessment in Pediatric Intensive Care Unit Team Training](https://arxiv.org/pdf/2505.24389) | NA |


### Graph Learning 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03 | [Universal Scene Graph Generation](https://arxiv.org/pdf/2503.15005) | [🌐Project page](https://sqwu.top/USG/)|


### Camouflaged Object Detection (COD)
#### Video COD
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.07| [Evaluating SAM2's Role in Camouflaged Object Detection: From SAM to SAM2](https://arxiv.org/abs/2407.21596) | [🔗 Code](https://github.com/luckybird1994/SAMCOD) |
| 2024.09 | [When SAM2 Meets Video Camouflaged Object Segmentation: A Comprehensive Evaluation and Adaptation](https://arxiv.org/abs/2409.18653) | [🔗 Code](https://github.com/zhoustan/SAM2-VCOS) |
| 2025.03 | [CamSAM2: Segment Anything Accurately in Camouflaged Videos](https://arxiv.org/pdf/2503.19730) | [🔗 Code](https://github.com/zhoustan/CamSAM2)|
| 2025.04 | [CamoSAM2: Motion-Appearance Induced Auto-Refining Prompts for Video Camouflaged Object Detection](https://arxiv.org/pdf/2504.00375) | NA |
| 2025.04 | [CamoSAM2: Motion-Appearance Induced Auto-Refining Prompts for Video Camouflaged Object Detection](https://arxiv.org/pdf/2504.00375) | NA |

#### Image COD
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation](https://arxiv.org/abs/2408.08870) | [🔗 Code](https://github.com/WZH0120/SAM2-UNet) |
| 2024.08| [SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More](https://arxiv.org/abs/2408.04579) | [🔗 Code](http://tianrun-chen.github.io/SAM-Adaptor/) |

### Remote Sensing
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.11| [DED-SAM: Adapting Segment Anything Model 2 for Dual Encoder-Decoder Change Detection](https://ieeexplore.ieee.org/abstract/document/10741350) | NA |
| 2025.01| [Prompt-Based Segmentation at Multiple Resolutions and Lighting Conditions using Segment Anything Model 2](https://arxiv.org/abs/2408.06970) | NA |
| 2025.03| [Customized SAM 2 for Referring Remote Sensing Image Segmentation](https://arxiv.org/pdf/2503.07266) | NA |
| 2025.05 | [InstructSAM: A Training-Free Framework for Instruction-Oriented Remote Sensing Object Recognition](https://arxiv.org/pdf/2505.15818) | [🔗 Code](https://github.com/VoyagerXvoyagerx/InstructSAM) |
| 2025.06 | [Baltimore Atlas: FreqWeaver Adapter for Semi-supervised Ultra-high Spatial Resolution Land Cover Classification](https://arxiv.org/pdf/2506.15565) | NA |
| 2025.06 | [Bundle adjustment for multi-source Mars orbiter imagery with generalized control constraints](https://www.sciencedirect.com/science/article/abs/pii/S0924271625002175) | NA |
| 2025.07 | [Leveraging SAM 2 and LiDAR for Automated Individual Tree Crown Delineation: A Comparative Evaluation of Prompting Methods](https://www.sciencedirect.com/science/article/pii/S3050520825000259) | [🔗 Code](https://github.com/lu-liang-geo/Sam-Lidar/) |
| 2025.07 | [Aerial Visual Localization over Low Level-of-Detail City Models using Explicit Silhouette Alignment](https://arxiv.org/pdf/2507.00659) | [🔗 Code](https://github.com/VictorZoo/LoD-Loc-v2) |
| 2025.07 | [CSW-SAM: a cross-scale algorithm for very-high-resolution water body segmentation based on segment anything model 2](https://www.sciencedirect.com/science/article/pii/S0924271625002709) | NA |
| 2025.07 | [A Fine Agricultural Flood Segmentation Model For HJ-2E S-band SAR Data](https://ieeexplore.ieee.org/document/11079287) | NA |

### Mesh or Point Cloud / 3D Processing
#### Mesh or Point Cloud Segmentation
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Segment Any Mesh: Zero-shot Mesh Part Segmentation via Lifting Segment Anything 2 to 3D](https://arxiv.org/abs/2408.13679) | [🔗 Code](https://github.com/gtangg12/samesh) |
| 2024.11| [Object and Contact Point Tracking in Demonstrations Using 3D Gaussian Splatting](https://arxiv.org/abs/2411.03555) | NA |
| 2024.11| [Any3DIS: Class-Agnostic 3D Instance Segmentation by 2D Mask Tracking](https://arxiv.org/abs/2411.16183) |  [🌐Project page](https://any3dis.github.io/) |
| 2025.03 | [Segment-then-Splat: A Unified Approach for 3D Open-Vocabulary Segmentation based on Gaussian Splatting](https://arxiv.org/pdf/2503.22204) | [🌐Project page](https://vulab-ai.github.io/Segment-then-Splat/) |
| 2025.04 | [DSM: Building A Diverse Semantic Map for 3D Visual Grounding](https://arxiv.org/pdf/2504.08307) | [🌐Project page](https://binicey.github.io/DSM/) |
| 2025.07 | [GraphSeg: Constructing Segmented 3D Representations via Graph Edge Addition and Contraction](https://rss25-roboreps.github.io/papers/28_GraphSeg_Segmented_3D_Repre.pdf) | NA |

#### Mesh or Point Cloud Reconstruction
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.12 | [Deblur4DGS: 4D Gaussian Splatting from Blurry Monocular Videos](https://arxiv.org/abs/2410.17988) | [🌐Project page](https://deblur4dgs.github.io/) |
| 2024.11| [Updating Dynamic 3D Scene Graphs from Egocentric Observations](https://arxiv.org/pdf/2411.19162)| [🌐Project page](https://behretj.github.io/LostAndFound/)| 
| 2025.02| [Inter3D: A Benchmark and Strong Baseline for Human-Interactive 3D Object Reconstruction](https://arxiv.org/pdf/2502.14004)| [🔗 Code](https://github.com/Inter3D-ui/Inter3D?tab=readme-ov-file)|

#### Other Applications
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03| [LP-Gaussians: Learnable Parametric Gaussian Splatting for Efficient Dynamic Reconstruction of Single-View Scenes](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10888277) | [🌐Project page](https://github.com/LPGaussians)|
| 2025.03 | [DecoupledGaussian: Object-Scene Decoupling for Physics-Based Interaction](https://arxiv.org/pdf/2503.05484) | [🌐Project page](https://wangmiaowei.github.io/DecoupledGaussian.github.io/) |
| 2025.03 | [Free Your Hands: Lightweight Relightable Turntable Capture Pipeline](https://arxiv.org/pdf/2503.05511) | NA |
| 2025.03 | [WildSeg3D: Segment Any 3D Objects in the Wild from 2D Images](https://arxiv.org/pdf/2503.08407) | 🕒Soon | 
| 2025.03 | [Pseudo-LiDAR With Two-Dimensional Instance for Monocular Three-Dimensional Object Tracking](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10918939) | NA |
| 2025.03 | [SED-MVS: Segmentation-Driven and Edge-Aligned Deformation Multi-View Stereo with Depth Restoration and Occlusion Constraint](https://arxiv.org/pdf/2503.13721) | NA |
| 2025.03 | [SceneSplat: Gaussian Splatting-based Scene Understanding with Vision-Language Pretraining](https://arxiv.org/pdf/2503.18052) | [🔗 Code](https://github.com/unique1i/SceneSplat) |
| 2025.03 | [COB-GS: Clear Object Boundaries in 3DGS Segmentation Based on Boundary-Adaptive Gaussian Splitting](https://arxiv.org/pdf/2503.19443)| [🔗 Code](https://github.com/ZestfulJX/COB-GS) |
| 2025.03 | [Feature4X: Bridging Any Monocular Video to 4D Agentic AI with Versatile Gaussian Feature Fields](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhou_Feature4X_Bridging_Any_Monocular_Video_to_4D_Agentic_AI_with_CVPR_2025_paper.pdf) | [🌐Project page](https://feature4x.github.io/)|
| 2025.03 | [Semantic Consistent Language Gaussian Splatting for Point-Level Open-vocabulary Querying](https://arxiv.org/pdf/2503.21767) | [🌐Project page](https://evelinyin.github.io/seconGS/) |
| 2025.04 | [Augmented Unseen Region Alignment for Reference-based 360° Unbounded Scene Inpainting](https://arxiv.org/pdf/2502.05176) | [🌐Project page](https://kkennethwu.github.io/aurafusion360/) |
| 2025.04 | [ FMLGS: Fast Multilevel Language Embedded Gaussians for Part-level Interactive Agents](https://arxiv.org/pdf/2504.08581) | NA |
| 2025.06 | [ GENMANIP: LLM-driven Simulation for Generalizable Instruction-Following Manipulation](https://openaccess.thecvf.com/content/CVPR2025/papers/Gao_GENMANIP_LLM-driven_Simulation_for_Generalizable_Instruction-Following_Manipulation_CVPR_2025_paper.pdf) | [🌐Project page](https://genmanip.axi404.top/) |
| 2025.05 | [Constructing a 3D Town from a Single Image](https://arxiv.org/pdf/2505.15765) | [🌐Project page](https://eric-ai-lab.github.io/3dtown.github.io/) |
| 2025.06 | [GenMOJO: Robust Multi-Object 4D Generation for In-the-wild Videos](https://arxiv.org/pdf/2506.12716) | [🌐Project page](https://genmojo.github.io/) |
| 2025.06 | [CAP-Net: A Unified Network for 6D Pose and Size Estimation of Categorical Articulated Parts from a Single RGB-D Image](https://arxiv.org/pdf/2504.11230) | [🌐Project page](https://shanehuanghz.github.io/CAPNet/) |
| 2025.06 | [BlenderFusion: 3D-Grounded Visual Editing and Generative Compositing](https://arxiv.org/pdf/2506.17450)| [🌐Project page](https://blenderfusion.github.io/) |
| 2025.07 | [LangScene-X: Reconstruct Generalizable 3D Language-Embedded Scenes with TriMap Video Diffusion](https://arxiv.org/pdf/2507.02813) | [🌐Project page](https://liuff19.github.io/LangScene-X/) |
| 2025.07 | [ Consistent Bokeh for Multi-View Images With 3D Gaussian Splatting](https://ieeexplore.ieee.org/document/11045295) | [🔗 Code](https://github.com/jiutaojushi/CBMI) |
| 2025.07 | [Defect segmentation and 3D reconstruction in concrete structures using SAM 2 and 3D Gaussian splatting](https://link.springer.com/article/10.1007/s13349-025-00993-z) | Upon Request |
| 2025.07 | [Image-Guided Shape-from-Template Using Mesh Inextensibility Constraints](https://arxiv.org/pdf/2507.22699) | [🔗 Code](https://github.com/dvttran/nsft) |
| 2025.07 | [MG-Mono: A Lightweight Multi-Granularity Method for Self-Supervised Monocular Depth Estimation](https://www.sciencedirect.com/science/article/abs/pii/S0031320325008842) | [🔗 Code](https://github.com/PENGFly2022/MGMono) |

### Image or Video Generation & Editing
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.10| [AdaptiveDrag: Semantic-Driven Dragging on Diffusion-Based Image Editing](https://arxiv.org/abs/2410.12696) | [🔗 Code](https://github.com/Calvin11311/AdaptiveDrag) |
| 2024.11| [VideoDirector: Precise Video Editing via Text-to-Video Models](https://arxiv.org/abs/2411.17592) | [🌐Project page](https://anonymous.4open.science/w/c4KzqAbCaz89o0FeWkdya/) |
| 2024.11| [VIVID-10M: A Dataset and Baseline for Versatile and Interactive Video Local Editing](https://arxiv.org/abs/2411.15260) | [🌐Project page](https://inkosizhong.github.io/VIVID/) |
| 2024.11 | [Generative Omnimatte: Learning to Decompose Video into Layers](https://arxiv.org/abs/2411.16683) | [🌐Project page](https://gen-omnimatte.github.io/)|
| 2024.12 | [InterDyn: Controllable Interactive Dynamics with Video Diffusion Models](https://arxiv.org/abs/2412.11785) | [🌐Project page](https://interdyn.is.tue.mpg.de/) |
| 2025.01 | [MovieCharacter: A Tuning-Free Framework for Controllable Character Video Synthesis](https://arxiv.org/abs/2410.20974) | [🌐Project page](https://moviecharacter.github.io/) |
| 2025.01 |[BlobGEN-Vid: Compositional Text-to-Video Generation with Blob Video Representations](https://arxiv.org/abs/2501.07647) | [🌐Project page](https://blobgen-vid2.github.io/)|
| 2025.03| [TransVDM: Motion-Constrained Video Diffusion Model for Transparent Video Synthesis](https://arxiv.org/pdf/2502.19454)| NA|
| 2025.03 | [Towards More Accurate Personalized Image Generation: Addressing Overfitting and Evaluation Bias](https://arxiv.org/pdf/2503.06632) | [🔗 Code](https://github.com/Mingxiao-Li/Towards-More-Accurate-Personalized-Image-Generation) | 
| 2025.03 | [Unified Dense Prediction of Video Diffusion](https://arxiv.org/pdf/2503.09344) | NA |
| 2025.03 | [DreamInsert: Zero-Shot Image-to-Video Object Insertion from A Single Image](https://arxiv.org/pdf/2503.10342) | 🕒Soon |
| 2025.03| [ReBot: Scaling Robot Learning with Real-to-Sim-to-Real Robotic Video Synthesis](https://arxiv.org/pdf/2503.14526) | [🌐Project page](https://yuffish.github.io/rebot/)|
| 2025.03 | [FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing](https://arxiv.org/pdf/2503.16153) | [🌐Project page](https://wtybest.github.io/projects/FreeFlux/) |
| 2025.03| [MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance](https://arxiv.org/pdf/2503.16421)| [🌐Project page](https://quanhaol.github.io/magicmotion-site/) |
| 2025.03 | [Visual Jenga: Discovering Object Dependencies via Counterfactual Inpainting](https://arxiv.org/pdf/2503.21770) | [🌐Project page](https://visualjenga.github.io/) |
| 2025.03 | [Multi-Subject and Motion Customization of Text-to-Video Diffusion Models](https://arxiv.org/pdf/2503.21781) | [🌐Project page](https://jasper0314-huang.github.io/videomage-customization/) |
| 2025.04 | [DreamFuse: Adaptive Image Fusion with Diffusion Transformer](https://arxiv.org/pdf/2504.08291) | [🌐Project page](https://ll3rd.github.io/DreamFuse/) |
| 2025.04 | [Enhanced Semantic Extraction and Guidance for UGC Image Super Resolution](https://arxiv.org/pdf/2504.09887) | [🔗 Code](https://github.com/Moonsofang/NTIRE-2025-SRlab) |
| 2025.06 | [ Keyframe-Guided Creative Video Inpainting](https://openaccess.thecvf.com/content/CVPR2025/papers/Guo_Keyframe-Guided_Creative_Video_Inpainting_CVPR_2025_paper.pdf) | [🌐Project page](https://guoyww.github.io/projects/VideoRepainter/) |
| 2025.06 | [OmniGen2: Exploration to Advanced Multimodal Generation](https://arxiv.org/pdf/2506.18871) | [🌐Project page](https://vectorspacelab.github.io/OmniGen2/) |
| 2025.07 | [Reasoning to Edit: Hypothetical Instruction-Based Image Editing with Visual Reasoning](https://arxiv.org/pdf/2507.01908) | [🔗 Code](https://github.com/hithqd/ReasonBrain) |
| 2025.07 | [Enhanced Velocity Field Modeling for Gaussian Video Reconstruction](https://arxiv.org/pdf/2507.23704) | NA |

### Simultaneous Localization and Mapping (SLAM / VO)
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.11| [OVO-SLAM: Open-Vocabulary Online Simultaneous Localization and Mapping](https://arxiv.org/abs/2411.15043) | NA |
| 2025.06 | [MCOO-SLAM: A Multi-Camera Omnidirectional Object SLAM System](https://arxiv.org/pdf/2506.15402) | NA |
| 2025.07 | [VISTA: Monocular Segmentation-Based Mapping for Appearance and View-Invariant Global Localization](https://arxiv.org/pdf/2507.11653) | NA |

### Light Field Segmentation
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.11| [Segment Anything in Light Fields for Real-Time Applications via Constrained Prompting](https://arxiv.org/abs/2411.13840) | [🔗 Code](https://roboticimaging.org/Projects/LFSAM/) |

### Robotics
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.10| [A Pipeline for Segmenting and Structuring RGB-D Data for Robotics Applications](https://arxiv.org/abs/2410.17988) | NA |
| 2024.10|[VLM See, Robot Do: Human Demo Video to Robot Action Plan via Vision Language Model](https://arxiv.org/abs/2410.08792)|[🌐Project page](https://ai4ce.github.io/SeeDo/)|
| 2025.02| [Video2Policy: Scaling up Manipulation Tasks in Simulation through Internet Videos](https://arxiv.org/pdf/2502.09886)| [🌐Project page](https://yewr.github.io/video2policy/)|
| 2025.02| [Map Space Belief Prediction for Manipulation-Enhanced Mapping](https://arxiv.org/pdf/2502.20606)| (To be released)|
| 2025.02| [Sim-to-Real Reinforcement Learning for Vision-Based Dexterous Manipulation on Humanoids](https://arxiv.org/pdf/2502.20396)| [🌐Project page](https://toruowo.github.io/recipe)|
| 2025.03| [DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping](https://arxiv.org/pdf/2502.20900)| [🌐Project page](https://dexgraspvla.github.io/)|
| 2025.03 | [Autonomous Dissection in Robotic Cholecystectomy](https://arxiv.org/pdf/2503.00666) | NA |
| 2025.03 | [MetaFold: Language-Guided Multi-Category Garment Folding Framework via Trajectory Generation and Foundation Model](https://arxiv.org/pdf/2503.08372) | [🌐Project page](https://meta-fold.github.io/) |
| 2025.03 | [LuciBot: Automated Robot Policy Learning from Generated Videos](https://arxiv.org/pdf/2503.09871) | [🌐Project page](https://lucibot.github.io/) |
| 2025.03 | [IMPACT : Intelligent Motion Planning with Acceptable Contact Trajectories via Vision-Language Models](https://arxiv.org/pdf/2503.10110) | [🌐Project page](https://impact-planning.github.io/) |
| 2025.03 | [VISO-Grasp: Vision-Language Informed Spatial Object-centric 6-DoF Active View Planning and Grasping in Clutter and Invisibility](https://arxiv.org/pdf/2503.12609) | NA |
| 2025.04 | [Slot-Level Robotic Placement via Visual Imitation from Single Human Video](https://arxiv.org/pdf/2504.01128) | [🌐Project page](https://ddshan.github.io/slerp/) |
| 2025.04 | [Entangled chip removal utilizing mass-spring model with mobile manipulator](https://www.sciencedirect.com/science/article/pii/S0007850625000885) | NA |
| 2025.05 | [Symbolically-Guided Visual Plan Inference from Uncurated Video Data](https://arxiv.org/pdf/2505.08444) | NA |
| 2025.05 | [Geometry-Consistent Video Diffusion for Robotic Visual Policy Transfer](https://arxiv.org/pdf/2505.23171) | [🌐Project page](https://horizonrobotics.github.io/robot_lab/robotransfer/) |
| 2025.05 | [Grasp the Invisibility by Vision-Language guided Active View Planning](https://dyalab.mines.edu/2025/icra-workshop/2.pdf) | NA |
|2025.07 | [Geometry-aware 4D Video Generation for Robot Manipulation](https://arxiv.org/pdf/2507.01099) | [🌐Project page](https://robot4dgen.github.io/) |
| 2025.07 | [Object-Centric Mobile Manipulation through SAM2-Guided Perception and Imitation Learning](https://arxiv.org/pdf/2507.10899) | NA |
| 2025.07 | [GraspGen: A Diffusion-based Framework for 6-DOF Grasping](https://arxiv.org/pdf/2507.13097) | [🌐Project page](https://graspgen.github.io/) |
| 2025.07 | [RAGNet: Large-scale Reasoning-based Affordance Segmentation Benchmark towards General Grasping](https://arxiv.org/pdf/2507.23734) | [🔗 Code](https://github.com/wudongming97/AffordanceNet) |

### Adaptation, Compression & Edge Applications
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03| [LVMScissor: Split and Schedule Large Vision Model Inference on Mobile Edges via Salp Swarm Algorithm](https://ieeexplore.ieee.org/abstract/document/10923690/) | NA |
| 2025.03| [SALT: Parameter-Efficient Fine-Tuning via Singular Value Adaptation with Low-Rank Transformation](https://arxiv.org/pdf/2503.16055) | [🔗 Code](https://github.com/BioMedIA-MBZUAI/SALT)|
| 2025.04 | [Parameter-Free Fine-tuning via Redundancy Elimination for Vision Foundation Models](https://arxiv.org/pdf/2504.08915) | NA |
| 2025.05 | [Deploying Vision Foundation AI Models on the Edge. The SAM2 Experience](https://people.ac.upc.edu/rtous/publications/conf_2025iwann.pdf) | NA |

## Training
### Datasets 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [SurgPose: a Dataset for Articulated Robotic Surgical Tool Pose Estimation and Tracking](https://arxiv.org/abs/2502.11534)| [🌐Project page](https://surgpose.github.io/)|
| 2025.02| [The PanAf-FGBG Dataset: Understanding the Impact of Backgrounds in Wildlife Behaviour Recognition](https://arxiv.org/pdf/2502.21201)| NA|
| 2025.02| [Picking the Cream of the Crop:Visual-Centric Data Selection with Collaborative Agents](https://arxiv.org/pdf/2502.19917)| [🔗 Code](https://github.com/HITsz-TMG/ViSA)|
| 2025.03| [Phantom: Training Robots Without Robots Using Only Human Videos](https://arxiv.org/pdf/2503.00779) | [🌐Project page](https://phantom-human-videos.github.io/)|
| 2025.03| [Scalable Real2Sim: Physics-Aware Asset Generation Via Robotic Pick-and-Place Setups](https://arxiv.org/pdf/2503.00370) | [🌐Project page](https://scalable-real2sim.github.io/)|
| 2025.03 | [What Are You Doing? A Closer Look at Controllable Human Video Generation](https://arxiv.org/pdf/2503.04666) | [🔗 Code](https://github.com/google-deepmind/wyd-benchmark) |
| 2025.03| [Instrument-Splatting: Controllable Photorealistic Reconstruction of Surgical Instruments Using Gaussian Splatting](https://arxiv.org/pdf/2503.04082) | 🕒Soon |
| 2025.03 | [Referring to Any Person](https://arxiv.org/pdf/2503.08507) | [🌐Project page](https://wangyian-me.github.io/LuciBot/) | 
| 2025.03 | [AUTV: Creating Underwater Video Datasets with Pixel-wise Annotations](https://arxiv.org/pdf/2503.12828) | NA |
| 2025.03 | [DynOPETs: A Versatile Benchmark for Dynamic Object Pose Estimation and Tracking in Moving Camera Scenarios](https://arxiv.org/pdf/2503.19625) | [🌐Project page](https://stay332.github.io/DynOPETs/) | 
| 2025.05 | [A fusion network for multi-modality medical image registration with progressive feature alignment](https://www.sciencedirect.com/science/article/abs/pii/S0950705125004745) | [🔗 Code](https://github.com/Jy1-Xu/PFRFusion) |
| 2025.04 | [InteractAvatar: Modeling Hand-Face Interaction in Photorealistic Avatars with Deformable Gaussians](https://arxiv.org/pdf/2504.07949) | NA |
| 2025.04 | [VideoSPatS: Video SPatiotemporal Splines for Disentangled Occlusion, Appearance and Motion Modeling and Editing](https://arxiv.org/pdf/2504.07146) | [🌐Project page](https://juanluisg-flwls.github.io/videospats-website/) |
| 2025.04 | [UrbanWaste: In-the-Bin Dataset for Waste Disposal Inspection with Multi-Granularity Hierarchical Labels](https://ojs.aaai.org/index.php/AAAI/article/view/35043) | [🌐Project page](https://github.com/zma029/UrbanWaste) |
| 2025.06 | [HD-EPIC: A Highly-Detailed Egocentric Video Dataset](https://openaccess.thecvf.com/content/CVPR2025/papers/Perrett_HD-EPIC_A_Highly-Detailed_Egocentric_Video_Dataset_CVPR_2025_paper.pdf) | [🌐Project page](https://hd-epic.github.io/) |
| 2025.06 | [ GigaHands: A Massive Annotated Dataset of Bimanual Hand Activities](https://openaccess.thecvf.com/content/CVPR2025/papers/Fu_GigaHands_A_Massive_Annotated_Dataset_of_Bimanual_Hand_Activities_CVPR_2025_paper.pdf) | [🌐Project page](https://ivl.cs.brown.edu/research/gigahands.html) |
| 2025.06 | [INTERNSPATIAL: A Comprehensive Dataset for Spatial Reasoning in Vision-Language Models](https://arxiv.org/pdf/2506.18385) | NA |
| 2025.06 | [BrokenVideos: A Benchmark Dataset for Fine-Grained Artifact Localization in AI-Generated Videos](https://arxiv.org/pdf/2506.20103) | [🌐Project page](https://broken-video-detection-datetsets.github.io/Broken-Video-Detection-Datasets.github.io/) |
| 2025.06 | [SAM4D:Segment Anything in Camera and LiDAR Streams](https://arxiv.org/pdf/2506.21547) | [🌐Project page](https://sam4d-project.github.io/) |
| 2025.06 | [XVerse: Consistent Multi-Subject Control of Identity and Semantic Attributes via DiT Modulation](https://arxiv.org/pdf/2506.21416) | [🌐Project page](https://bytedance.github.io/XVerse/) |
| 2025.07 | [A New Dataset and Performance Benchmark for Real-time Spacecraft Segmentation in Onboard Flight Computers](https://arxiv.org/pdf/2507.10775)| [🔗 Code](https://github.com/RiceD2KLab/SWiM) |
| 2025.07 | [Towards Omnimodal Expressions and Reasoning in Referring Audio-Visual Segmentation](https://arxiv.org/pdf/2507.22886)| [🌐Project page](https://henghuiding.com/OmniAVS/) |


#### Used for Data Augmentation (/Tool)
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02 | [Towards Physical Understanding in Video Generation: A 3D Point Regularization Approach](https://arxiv.org/pdf/2502.03639?) | [🌐Project page](https://snap-research.github.io/PointVidGen/) |
|2025.03| [A Taxonomy for Evaluating Generalist Robot Policies](https://arxiv.org/pdf/2503.01238)| [🌐Project page](https://stargen-taxonomy.github.io/)|
|2025.03|[CRESTE: Scalable Mapless Navigation with Internet Scale Priors and Counterfactual Guidance](https://arxiv.org/pdf/2503.03921)|[🌐Project page](https://amrl.cs.utexas.edu/creste/)|
|2025.03| [Shaken, Not Stirred: A Novel Dataset for Visual Understanding of Glasses in Human-Robot Bartending Tasks](https://arxiv.org/pdf/2503.04308) | [🌐Project page](https://gajdosech2.github.io/GlassNICOLDataset/)|
| 2025.03 | [YOLOE: Real-Time Seeing Anything](https://arxiv.org/pdf/2503.07465) | [🔗 Code](https://github.com/THU-MIG/yoloe) |
| 2025.03 | [VACE: All-in-One Video Creation and Editing](https://arxiv.org/pdf/2503.07598) | [🌐Project page](https://ali-vilab.github.io/VACE-Page/) |
| 2025.03 | [V2M4: 4D Mesh Animation Reconstruction from a Single Monocular Video](https://arxiv.org/pdf/2503.09631)| [🌐Project page](https://windvchen.github.io/V2M4/) |
| 2025.03 | [Better Together: Unified Motion Capture and 3D Avatar Reconstruction](https://arxiv.org/pdf/2503.09293) | NA |
| 2025.03 | [CINEMA: Coherent Multi-Subject Video Generation via MLLM-Based Guidance](https://arxiv.org/pdf/2503.10391) | NA |
| 2025.03 | [RePerformer: Immersive Human-centric Volumetric Videos from Playback to Photoreal Reperformance ](https://arxiv.org/pdf/2503.12242) | [🌐Project page](https://moqiyinlun.github.io/Reperformer/) |
| 2025.03 | [Evaluating the FLUX.1 Synthetic Data on YOLOv9 for AI-Powered Poultry Farming](https://www.mdpi.com/2076-3417/15/7/3663) | NA |
| 2025.03 | [Any2Caption : Interpreting Any Condition to Caption for Controllable Video Generation](https://arxiv.org/pdf/2503.24379) | [🌐Project page](https://sqwu.top/Any2Cap/) |
| 2025.05 | [LayerCraft: Enhancing Text-to-Image Generation with CoT Reasoning and Layered Object Integration](https://arxiv.org/pdf/2504.00010) | [🔗 Code](https://github.com/PeterYYZhang/LayerCraft) |
| 2025.04 | [VisualCloze: A Universal Image Generation Framework via Visual In-Context Learning](https://arxiv.org/pdf/2504.07960) | [🌐Project page](https://visualcloze.github.io/) |
| 2025.04 | [M2Flow: A Motion Information Fusion Framework for Enhanced Unsupervised Optical Flow Estimation in Autonomous Driving](https://ojs.aaai.org/index.php/AAAI/article/view/32767) | NA |
| 2025.05 | [Interspatial Attention for Efficient 4D Human Video Generation](https://arxiv.org/pdf/2505.15800) | [🌐Project page](https://dsaurus.github.io/isa4d/) |
| 2025.06 | [Real-Time Per-Garment Virtual Try-On with Temporal Consistency for Loose-Fitting Garments](https://arxiv.org/pdf/2506.12348) | NA |
| 2025.06 | [Impact of Synthetic Data from Diffusion Models on Weed Detection Performance](https://rodrigoguerra.com/wp-content/uploads/2025/05/RamosSyntheticWeed.pdf) | NA |
| 2025.06 | [VLA-OS: Structuring and Dissecting Planning Representations and Paradigms in Vision-Language-Action Models](https://arxiv.org/pdf/2506.17561) | [🌐Project page](https://nus-lins-lab.github.io/vlaos/) |
| 2025.06 | [Building Software for Analyzing Muck Piles After Blasting in Laboratory Conditions with Integrated Artificial Intelligence](https://jst.lqdtu.edu.vn/index.php/sce/article/view/970/630) | NA |
| 2025.06 | [WeedSwin hierarchical vision transformer with SAM-2 for multi-stage weed detection and classification](https://www.nature.com/articles/s41598-025-05092-z) | On Request | 
| 2025.07 | [Go to Zero: Towards Zero-shot Motion Generation with Million-scale Data](https://arxiv.org/pdf/2507.07095) | [🔗 Code](https://github.com/VankouF/MotionMillion-Codes) |
| 2025.07 | [ RCG: Safety-Critical Scenario Generation for Robust Autonomous Driving via Real-World Crash Grounding](https://arxiv.org/pdf/2507.10749) | 🕒Soon |

### Training Helper
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03 | [DINeMo: Learning Neural Mesh Models with no 3D Annotations](https://arxiv.org/pdf/2503.20220) | [🌐Project page](https://analysis-by-synthesis.github.io/DINeMo/) |
| 2025.04 | [CoProSketch: Controllable and Progressive Sketch Generation with Diffusion Model](https://arxiv.org/pdf/2504.08259) | NA |
| 2025.04 | [Aligning Anime Video Generation with Human Feedback](https://arxiv.org/pdf/2504.10044) | 🕒Soon |
| 2025.04 | [OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding](https://arxiv.org/pdf/2504.10825) | [🌐Project page](https://tele-ai.github.io/OmniVDiff/) |
| 2025.06 | [HunyuanVideo-HOMA Generic Human-Object Interaction in Multimodal Driven Human Animation](https://arxiv.org/pdf/2506.08797) | [🌐Project page](https://anonymous.4open.science/w/homa-page-0FBE/) |
| 2025.06 | [Enhancing Visual Localization with Cross-Domain Image Generation](https://openreview.net/pdf?id=ruj5ILBUuK) | [🌐Project page](https://yzwang-sjtu.github.io/CDG-Loc/) |
| 2025.07 | [RoboBrain 2.0: See Better. Think Harder. Do Smarter.](https://arxiv.org/pdf/2507.02029) | [🌐Project page](https://superrobobrain.github.io/) |
| 2025.07 | [Scalable Multi-Task Reinforcement Learning for Generalizable Spatial Intelligence in Visuomotor Agents](https://arxiv.org/pdf/2507.23698) | [🔗 Code](https://github.com/CraftJarvis/ROCKET-3/) |


### Performance Evaluations 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [Vector-Quantized Vision Foundation Models for Object-Centric Learning](https://arxiv.org/pdf/2502.20263)| NA|
| 2025.04 | [WorldScore: A Unified Evaluation Benchmark for World Generation](https://arxiv.org/pdf/2504.00983) | [🌐Project page](https://haoyi-duan.github.io/WorldScore/)|
| 2025.04 | [BIGS: Bimanual Category-agnostic Interaction Reconstruction from Monocular Videos via 3D Gaussian Splatting](https://arxiv.org/pdf/2504.09097) | NA |
| 2025.05 | [ UWSAM: Segment Anything Model Guided Underwater Instance Segmentation and A Large-scale Benchmark Dataset](https://arxiv.org/pdf/2505.15581) | [🔗 Code](https://github.com/LiamLian0727/UIIS10K) |
 | 2025.05 | [Leveraging Segment Anything Model 2 (SAM 2) to optimize segmentation for synthetic data quality in high-clutter baggage](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13464/134640Q/Leveraging-Segment-Anything-Model-2-SAM-2-to-optimize-segmentation/10.1117/12.3057025.short) | NA |
 | 2025.05  | [Synergistic Enhancement: A Study on the Design of Large Models Assisted by End-toEnd Road Damage Prompt Network and Methods for Quantification of Damage Morphological Features](https://ieeexplore.ieee.org/abstract/document/11011305) | NA |
 | 2025.06 | [Towards Scalable and Generalizable Earth Observation Data Mining via Foundation Model Composition](https://arxiv.org/pdf/2506.20174) | NA |
 | 2025.06 | [AI-Driven MRI-based Brain Tumour Segmentation Benchmarking](https://arxiv.org/pdf/2506.20786) | NA |
 | 2025.07 | [Amulti-modal dataset for insect biodiversity with imagery and DNA at the trap and individual level](https://arxiv.org/pdf/2507.06972) | [🔗 Code](https://github.com/uoguelph-mlrg/MassID45) |
 | 2025.07 | [enLLASD: An ensemble deep learning framework to automate derivation of lower-limb alignments for skeletal dysplasia](https://ieeexplore.ieee.org/document/11080497) | NA |
 | 2025.07 | [Semantic Segmentation of iPS Cells: Case Study on Model Complexity in Biomedical Imaging](https://arxiv.org/pdf/2507.21608) | NA |
 
#### Post Processing
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.03 | [Easi3R: Estimating Disentangled Motion from DUSt3R Without Training](https://arxiv.org/pdf/2503.24391) | [🌐Project page](https://easi3r.github.io/)|
| 2025.04 | [Multi-identity Human Image Animation with Structural Video Diffusion](https://arxiv.org/pdf/2504.04126)| NA |
| 2025.06 | [Vid-CamEdit: Video Camera Trajectory Editing with Generative Rendering from Estimated Geometry](https://arxiv.org/pdf/2506.13697) | [🌐Project page](https://cvlab-kaist.github.io/Vid-CamEdit/) |
| 2025.06 | [Leader360V: A Large-scale, Real-world 360 Video Dataset for Multi-task Learning in Diverse Environments]() | NA |
| 2025.07 | [Robust and Efficient 3D Gaussian Splatting for Urban Scene Reconstruction](https://arxiv.org/pdf/2507.23006) | [🌐Project page](https://yzslab.github.io/REUrbanGS/) |

### Robustness
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.04 | [Robust SAM: On the Adversarial Robustness of Vision Foundation Models](https://ojs.aaai.org/index.php/AAAI/article/view/32616) | NA |

### Unique Applications/Usage
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.09| [Towards Robust Automation of Surgical Systems via Digital Twin-based Scene Representations from Foundation Models](https://arxiv.org/abs/2409.13107) | NA |
| 2024.09| [Helpful DoggyBot: Open-World Object Fetching using Legged Robots and Vision-Language Models](https://arxiv.org/abs/2410.00231) | [🔗 Code](https://helpful-doggybot.github.io/) |
| 2024.09| [Point of Interest Recognition and Tracking in Aerial Video during Live Cycling Broadcasts](https://www.mdpi.com/2076-3417/14/20/9246) | NA |
| 2024.10| [ROCKET-1: Mastering Open-World Interaction with Visual-Temporal Context Prompting](https://arxiv.org/abs/2410.17856) | [🔗 Code](https://github.com/CraftJarvis/ROCKET-1) |
| 2024.10| [GRS: Generating Robotic Simulation Tasks from Real-World Images](https://arxiv.org/abs/2410.15536) | NA |
| 2024.10| [Iterative Optimization Annotation Pipeline and ALSS-YOLO-Seg for Efficient Banana Plantation Segmentation in UAV Imagery](https://arxiv.org/abs/2410.07955) | NA |
| 2024.10| [Next Best Sense: Guiding Vision and Touch with FisherRF for 3D Gaussian Splatting](https://arxiv.org/abs/2410.04680) | [🔗 Code](https://github.com/armlabstanford/NextBestSense) |
| 2025.01| [Zero-Shot Pupil Segmentation with SAM 2: A Case Study of Over 14 Million Images](https://arxiv.org/abs/2410.08926) | [📊Data](https://zenodo.org/records/13911636) |
| 2025.02| [Best Foot Forward: Robust Foot Reconstruction in-the-wild](https://arxiv.org/pdf/2502.20511)| |
| 2025.03| [ROCKET-2: Steering Visuomotor Policy via Cross-View Goal Alignment](https://arxiv.org/pdf/2503.02505)| [🌐Project page](https://craftjarvis.github.io/ROCKET-2/) |
| 2025.03| [JARVIS-VLA: Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse](https://arxiv.org/pdf/2503.16365)| [🌐Project page](https://craftjarvis.github.io/JarvisVLA/)|
|2025.04| [MORPHEUS: Benchmarking Physical Reasoning of Video Generative Models with Real Physical Experiments](https://arxiv.org/pdf/2504.02918) | [🌐Project page](https://physics-from-video.github.io/morpheus-bench/)|
| 2025.05 | [Air-Ground Collaboration for Language-Specified Missions in Unknown Environments](https://arxiv.org/pdf/2505.09108) | NA |
| 2025.06 | [In Situ Detection and Measurement of Broccoli Heads Under Different Lighting Conditions Using Proximal Remote Sensing](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.70008) | NA |
| 2025.07 | [ Zero-Shot Recognition of Test Tube Types by Automatically Collecting and Labeling RGB Data](https://ieeexplore.ieee.org/abstract/document/11067950/) | NA |
| 2025.07 | [Box Pose and Shape Estimation and Domain Adaptation for Large-Scale Warehouse Automation](https://arxiv.org/pdf/2507.00984) | NA |
| 2025.07 | [Phys2Real: Physically-Informed Gaussian Splatting for Adaptive Sim-to-Real Transfer in Robotic Manipulation](https://openreview.net/pdf?id=7HQTnl8qao) | NA |