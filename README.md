# Awesome SAM2 ( Segment Anything in Images and Videos)
This repo aims to include materials (papers, codes, slides) about [SAM2](https://arxiv.org/abs/2408.00714) (segment anything in images and videos), <ins>a vision foundation model released by Meta AI </ins>. We are continuously improving the project. Welcome to PR the works (papers, repos) that are missed.

## SAM2

- **[SAM2](https://arxiv.org/abs/2408.00714)**  [🔗 [**Code**](https://github.com/facebookresearch/segment-anything-2) | 🖥️ [**Demo**](https://sam2.metademolab.com/) | 📖 [**Explanation**](https://www.sievedata.com/blog/meta-segment-anything-2-sam2-introduction)]
- **[SAM](https://arxiv.org/abs/2304.02643)**  [🔗 [**Code**](https://github.com/facebookresearch/segment-anything) | 🖥️ [**Demo**](https://segment-anything.com/) | 📖 [**Explanation**](https://www.v7labs.com/blog/segment-anything-model-sam)]


## Contents
- [Surveys & Reviews](#surveys--reviews)
- [Traditional Segmentation Tasks](#traditional-segmentation)
    - [Image Segmentation](#image-segmentation)
    - [Tracking or Video Object Segmentation](#tracking-or-video-object-segmentation)
- [Medical Segmentation](#medical-domain)
    - [Medical Video & 3D Segmentation](#medical-video--3d-segmentation)
    - [Medical Image Segmentation](#medical-image-segmentation)
- [Camouflaged Object Detection (COD)](#camouflaged-object-detection-cod)
  - [Video COD](#video-cod)
  - [Image COD](#image-cod)
- [3D Mesh or Point Cloud Segmentation](#3d-mesh-or-point-cloud-segmentation)
- [Image or Video Editing](#image-or-video-editing)
- [Remote Sensing](#remote-sensing)
- [Simultaneous Localization and Mapping](#simultaneous-localization-and-mapping)
- [Light Field Segmentation](#light-field-segmentation)
- [Unique Applications](#unique-applications)

## Papers/Projects

### **Surveys & Reviews**
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.07 | [Segment Anything for Videos: A Systematic Survey](https://arxiv.org/abs/2408.08315) | [📖 Repo](https://github.com/983632847/SAM-for-Videos) |
| 2024.08 | [Unleashing the Potential of SAM2 for Biomedical Images and Videos: A Survey](https://arxiv.org/abs/2408.12889) | [📖 Repo](https://github.com/YichiZhang98/SAM4MIS) |
| 2024.10 | [On Efficient Variants of Segment Anything Model: A Survey](https://arxiv.org/abs/2410.04960) | NA |
<!-- | 2023.12 | [Large Scale Foundation Models for Intelligent Manufacturing Applications: A Survey](https://arxiv.org/abs/2312.06718) | [📖 Repo](https://github.com/NEUFS-MA/LSFMs-IM) | -->

### Traditional Segmentation
#### Image Segmentation
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.10 | [Towards Natural Image Matting in the Wild via Real-Scenario Prior](https://arxiv.org/abs/2410.06593) | [🔗 Code](https://github.com/XiaRho/SEMat) |
| 2024.11 | [CorrCLIP: Reconstructing Correlations in CLIP with Off-the-Shelf Foundation Models for Open-Vocabulary Semantic Segmentation](https://arxiv.org/abs/2411.10086) | NA |

#### Referring Video Object Segmentation (RVOS) 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Unleashing the Temporal-Spatial Reasoning Capacity of GPT for Training-Free Audio and Language Referenced Video Object Segmentation](https://arxiv.org/abs/2408.15876) | [🔗 Code](https://github.com/appletea233/AL-Ref-SAM2) |
| 2024.11| [SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation](https://arxiv.org/abs/2411.17646) | [🔗 Code](https://github.com/ClaudiaCuttano/SAMWISE) |
| 2024.11| [SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory](https://arxiv.org/abs/2411.11922) | [🔗 Code](https://github.com/yangchris11/samurai) |
| 2025.02| [Text-Promtable propagation for referring medical image sequence segmentation](https://arxiv.org/abs/2502.11093)| NA|


#### Video Object Segmentation (+ Tracking)
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

### Camouflaged Object Detection (COD)
#### Video COD
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.07| [Evaluating SAM2's Role in Camouflaged Object Detection: From SAM to SAM2](https://arxiv.org/abs/2407.21596) | [🔗 Code](https://github.com/luckybird1994/SAMCOD) |
| 2024.09 | [When SAM2 Meets Video Camouflaged Object Segmentation: A Comprehensive Evaluation and Adaptation](https://arxiv.org/abs/2409.18653) | [🔗 Code](https://github.com/zhoustan/SAM2-VCOS) |

#### Image COD
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation](https://arxiv.org/abs/2408.08870) | [🔗 Code](https://github.com/WZH0120/SAM2-UNet) |
| 2024.08| [SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More](https://arxiv.org/abs/2408.04579) | [🔗 Code](http://tianrun-chen.github.io/SAM-Adaptor/) |

### Audio-visual segmentation (AVS)
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [Audio visual segmentation through text embeddings](https://arxiv.org/pdf/2502.16359) | NA|

### Remote Sensing
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.11| [DED-SAM: Adapting Segment Anything Model 2 for Dual Encoder-Decoder Change Detection](https://ieeexplore.ieee.org/abstract/document/10741350) | NA |
| 2025.01| [Prompt-Based Segmentation at Multiple Resolutions and Lighting Conditions using Segment Anything Model 2](https://arxiv.org/abs/2408.06970) | NA |

### Mesh or Point Cloud Segmentation

#### Mesh or Point Cloud Segmentation
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.08| [Segment Any Mesh: Zero-shot Mesh Part Segmentation via Lifting Segment Anything 2 to 3D](https://arxiv.org/abs/2408.13679) | [🔗 Code](https://github.com/gtangg12/samesh) |
| 2024.11| [Object and Contact Point Tracking in Demonstrations Using 3D Gaussian Splatting](https://arxiv.org/abs/2411.03555) | NA |
| 2024.11| [Any3DIS: Class-Agnostic 3D Instance Segmentation by 2D Mask Tracking](https://arxiv.org/abs/2411.16183) |  [🌐Project page](https://any3dis.github.io/) |

#### Mesh or Point Cloud Reconstruction
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.12 | [Deblur4DGS: 4D Gaussian Splatting from Blurry Monocular Videos](https://arxiv.org/abs/2410.17988) | [🌐Project page](https://deblur4dgs.github.io/) |
| 2024.11| [Updating Dynamic 3D Scene Graphs from Egocentric Observations](https://arxiv.org/pdf/2411.19162)| [🌐Project page](https://behretj.github.io/LostAndFound/)| 
| 2025.02| [Inter3D: A Benchmark and Strong Baseline for Human-Interactive 3D Object Reconstruction](https://arxiv.org/pdf/2502.14004)| [🔗 Code](https://github.com/Inter3D-ui/Inter3D?tab=readme-ov-file)|


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


### Simultaneous Localization and Mapping (SLAM)
| Release | Title | Code |
| :--- | :--- | :---: |
| 2024.11| [OVO-SLAM: Open-Vocabulary Online Simultaneous Localization and Mapping](https://arxiv.org/abs/2411.15043) | NA |

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

### Datasets 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [SurgPose: a Dataset for Articulated Robotic Surgical Tool Pose Estimation and Tracking](https://arxiv.org/abs/2502.11534)| [🌐Project page](https://surgpose.github.io/)|
| 2025.02| [The PanAf-FGBG Dataset: Understanding the Impact of Backgrounds in Wildlife Behaviour Recognition](https://arxiv.org/pdf/2502.21201)| NA|
| 2025.02| [Picking the Cream of the Crop:Visual-Centric Data Selection with Collaborative Agents](https://arxiv.org/pdf/2502.19917)| [🔗 Code](https://github.com/HITsz-TMG/ViSA)|

### Performance Evaluations 
| Release | Title | Code |
| :--- | :--- | :---: |
| 2025.02| [Vector-Quantized Vision Foundation Models for Object-Centric Learning](https://arxiv.org/pdf/2502.20263)| NA|

### Unique Applications
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
