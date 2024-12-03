# Awesome SAM2 ( Segment Anything in Images and Videos)
This repo aims to include materials (papers, codes, slides) about [SAM2](https://arxiv.org/abs/2408.00714) (segment anything in images and videos), <ins>a vision foundation model released by Meta AI </ins>. We are continuously improving the project. Welcome to PR the works (papers, repos) that are missed.

## SAM2
- [SAM2](https://arxiv.org/abs/2408.00714) [[code](https://github.com/facebookresearch/segment-anything-2), [demo](https://sam2.metademolab.com/), [Explaination](https://www.sievedata.com/blog/meta-segment-anything-2-sam2-introduction)]
- [SAM](https://arxiv.org/abs/2304.02643) [[code](https://github.com/facebookresearch/segment-anything), [demo](https://segment-anything.com/), [Explaination](https://www.v7labs.com/blog/segment-anything-model-sam))

## Contents
- [Survey](#survey)
- [Medical Video or 3D Segmentation](#medical-video-and-3d-segmentation)
- [Medical Image Segmentation](#medical-image-segmentation)
- [Image Segmentation](#image-segmentation)
- [Tracking or Video Object Segmentation](#tracking-or-video-object-segmentation)
- [Video Camouflage Object Detection](#video-camouflage-object-detection)
- [Image Camouflage Object Detection](#image-camouflage-object-detection)
- [Remote Sensing](#remote-sensing)
- [3D Mesh or Point Cloud Segmentation](#3d-mesh-or-point-cloud-segmentation)
- [Image or Video Editing](#image-or-video-editing)
- [Simultaneous Localization and Mapping](#simultaneous-localization-and-mapping)
- [Light Field Segmentation](#light-field-segmentation)
- [Applications](#applications)

## Papers/Projects
### Survey
- [Segment Anything for Videos: A Systematic Survey](https://arxiv.org/abs/2408.08315) [code]
- [Unleashing the Potential of SAM2 for Biomedical Images and Videos: A Survey](https://arxiv.org/abs/2408.12889) [code]
- [On Efficient Variants of Segment Anything Model: A Survey](https://arxiv.org/pdf/2410.04960)

### Medical Video and 3D Segmentation
- [Segment anything in medical images and videos: Benchmark and deployment](https://arxiv.org/abs/2408.03322) [[code](https://github.com/bowang-lab/MedSAM)]
- [SAM 2 in Robotic Surgery: An Empirical Evaluation for Robustness and Generalization in Surgical Video Segmentation](https://arxiv.org/abs/2408.04593) [code]
- [A Short Review and Evaluation of SAM2's Performance in 3D CT Image Segmentation](https://arxiv.org/abs/2408.11210) [[code](https://github.com/Project-MONAI/VISTA)]
- [Is SAM 2 Better than SAM in Medical Image Segmentation?](https://arxiv.org/abs/2408.04212) [code]
- [Performance and Non-adversarial Robustness of the Segment Anything Model 2 in Surgical Video Segmentation](https://arxiv.org/abs/2408.04098) [code]
- [Novel adaptation of video segmentation to 3D MRI: efficient zero-shot knee segmentation with SAM2](https://arxiv.org/abs/2408.04762) [code]
- [SAM2-PATH: A better segment anything model for semantic segmentation in digital pathology](https://arxiv.org/abs/2408.03651) [[code](https://github.com/simzhangbest/SAM2PATH)]
- [SAM & SAM 2 in 3D Slicer: SegmentWithSAM Extension for Annotating Medical Images](https://arxiv.org/abs/2408.15224) [[code](https://github.com/mazurowski-lab/SlicerSegmentWithSAM)]
- [Medical SAM 2: Segment Medical Images As Video Via Segment Anything Model 2](https://arxiv.org/abs/2408.00874) [[code](https://github.com/MedicineToken/Medical-SAM2?tab=readme-ov-file)]
- [Interactive 3D Medical Image Segmentation](https://arxiv.org/abs/2408.02635) [[code](https://github.com/Chuyun-Shen/SAM_2_Medical_3D)]
- [Biomedical sam 2: Segment anything in biomedical images and videos](https://arxiv.org/abs/2408.03286) [code]
- [Polyp SAM 2: Advancing Zero shot Polyp Segmentation in Colorectal Cancer Detection](https://arxiv.org/abs/2408.05892) [[code](https://github.com/sajjad-sh33/Polyp-SAM-2)]
- [Surgical SAM 2: Real-time Segment Anything in Surgical Video by Efficient Frame Pruning](https://arxiv.org/pdf/2408.07931) [[code](https://github.com/jinlab-imvr/Surgical-SAM-2)]
- [SAM-OCTA2: Layer Sequence OCTA Segmentation with Fine-tuned Segment Anything Model 2](https://arxiv.org/pdf/2409.09286) [[code](https://github.com/ShellRedia/SAM-OCTA2)]
- [Phase-Informed Tool Segmentation for Manual Small-Incision Cataract Surgery](https://arxiv.org/pdf/2411.16794) [code]
- [A-MFST: Adaptive Multi-Flow Sparse Tracker for Real-Time Tissue Tracking Under Occlusion](https://arxiv.org/pdf/2410.19996) [code]

### Medical Image Segmentation
- [SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation](https://arxiv.org/abs/2408.08870) [[code](https://github.com/WZH0120/SAM2-UNet)]
- [SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More](https://arxiv.org/abs/2408.04579) [[code](http://tianrun-chen.github.io/SAM-Adaptor/)]
- [Retrieval-augmented Few-shot Medical Image Segmentation with Foundation Models](https://arxiv.org/abs/2408.08813) [code]
- [Self-Prompting Polyp Segmentation in Colonoscopy using Hybrid Yolo-SAM 2 Model](https://arxiv.org/abs/2409.09484) [[code](https://github.com/sajjad-sh33/YOLO_SAM2)]
- [A multi-task learning model for clinically interpretable sesamoiditis grading](https://www.sciencedirect.com/science/article/pii/S0010482524012642) [code]
- [Combination of detector and SAM2 for image instance segmentation of industrial pelletized ore](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5034445) [code]
- [Zero-shot capability of SAM-family models for bone segmentation in CT scans](https://arxiv.org/pdf/2411.08629) [code]
- [SAM-I2I: Unleash the Power of Segment Anything Model for Medical Image Translation](https://arxiv.org/pdf/2411.12755) [code]
- [SAM-Swin: SAM-Driven Dual-Swin Transformers with Adaptive Lesion Enhancement for Laryngo-Pharyngeal Tumor Detection](https://arxiv.org/pdf/2410.21813) [[code](https://github.com/VVJia/SAM-Swin)]

### Image Segmentation
- [CorrCLIP: Reconstructing Correlations in CLIP with Off-the-Shelf Foundation Models for Open-Vocabulary Semantic Segmentation](https://arxiv.org/pdf/2411.10086) [code]
- [Towards Natural Image Matting in the Wild via Real-Scenario Prior](https://arxiv.org/pdf/2410.06593) [[code](https://github.com/XiaRho/SEMat)]

### Tracking or Video Object Segmentation
- [Video Object Segmentation via SAM 2: The 4th Solution for LSVOS Challenge VOS Track](https://arxiv.org/abs/2408.10125) [code]
- [The 2nd Solution for LSVOS Challenge RVOS Track: Spatial-temporal Refinement for Consistent Semantic Segmentation](https://arxiv.org/abs/2408.12447) [code]
- [LSVOS Challenge 3rd Place Report: SAM2 and Cutie based VOS](https://arxiv.org/abs/2408.10469) [code]
- [Masks and Boxes: Combining the Best of Both Worlds for Multi-Object Tracking](https://arxiv.org/pdf/2409.14220) [code]
- [Unleashing the Temporal-Spatial Reasoning Capacity of GPT for Training-Free Audio and Language Referenced Video Object Segmentation](https://arxiv.org/pdf/2408.15876) [[code](https://github.com/appletea233/AL-Ref-SAM2)]
- [A Distractor-Aware Memory for Visual Object Tracking with SAM2](https://arxiv.org/pdf/2411.17576) [[code](https://github.com/jovanavidenovic/DAM4SAM)]
- [SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation](https://arxiv.org/pdf/2411.17646) [[code](https://github.com/ClaudiaCuttano/SAMWISE)]
- [There is no SAMantics! Exploring SAM as a Backbone for Visual Understanding Tasks](https://arxiv.org/pdf/2411.15288) [[code](https://github.com/miquel-espinosa/samantics)]
- [Any3DIS: Class-Agnostic 3D Instance Segmentation by 2D Mask Tracking](https://arxiv.org/pdf/2411.16183) [code]
- [SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory](https://arxiv.org/pdf/2411.11922) [[code](https://github.com/yangchris11/samurai)]
- [SAM2Long: Enhancing SAM 2 for Long Video Segmentation with a Training-Free Memory Tree](https://arxiv.org/pdf/2410.16268) [[code](https://github.com/Mark12Ding/SAM2Long)]
- [Zero-Shot Pupil Segmentation with SAM 2: A Case Study of Over 14 Million Images](https://arxiv.org/pdf/2410.08926) [code]
  
### Video Camouflage Object Detection
- [Evaluating SAM2's Role in Camouflaged Object Detection: From SAM to SAM2](https://arxiv.org/abs/2407.21596) [[code](https://github.com/luckybird1994/SAMCOD)]
- [When SAM2 Meets Video Camouflaged Object Segmentation: A Comprehensive Evaluation and Adaptation](https://arxiv.org/pdf/2409.18653)[[code](https://github.com/zhoustan/SAM2-VCOS)]

### Image Camouflage Object Detection
- [SAM2-UNet: Segment Anything 2 Makes Strong Encoder for Natural and Medical Image Segmentation](https://arxiv.org/abs/2408.08870) [[code](https://github.com/WZH0120/SAM2-UNet)]
- [SAM2-Adapter: Evaluating & Adapting Segment Anything 2 in Downstream Tasks: Camouflage, Shadow, Medical Image Segmentation, and More](https://arxiv.org/abs/2408.04579) [[code](http://tianrun-chen.github.io/SAM-Adaptor/)]

### Remote Sensing
- [Prompt-Based Segmentation at Multiple Resolutions and Lighting Conditions using Segment Anything Model 2](https://arxiv.org/abs/2408.06970) [code]
- [DED-SAM: Adapting Segment Anything Model 2 for Dual Encoder-Decoder Change Detection](https://ieeexplore.ieee.org/abstract/document/10741350)

### 3D Mesh or Point Cloud Segmentation
- [Segment Any Mesh: Zero-shot Mesh Part Segmentation via Lifting Segment Anything 2 to 3D](https://arxiv.org/abs/2408.13679) [[code](https://github.com/gtangg12/samesh)]
- [Object and Contact Point Tracking in Demonstrations Using 3D Gaussian Splatting](https://arxiv.org/pdf/2411.03555) [code]
- [A Pipeline for Segmenting and Structuring RGB-D Data for Robotics Applications](https://arxiv.org/pdf/2410.17988) [code]

### Image or Video Editing
- [VideoDirector: Precise Video Editing via Text-to-Video Models](https://arxiv.org/pdf/2411.17592) [code]
- [VIVID-10M: A Dataset and Baseline for Versatile and Interactive Video Local Editing](https://arxiv.org/pdf/2411.15260) [code]
- [MovieCharacter: A Tuning-Free Framework for Controllable Character Video Synthesis](https://arxiv.org/pdf/2410.20974) [[code](https://moviecharacter.github.io/)]
- [AdaptiveDrag: Semantic-Driven Dragging on Diffusion-Based Image Editing](https://arxiv.org/pdf/2410.12696) [[code](https://github.com/Calvin11311/AdaptiveDrag)]

### Simultaneous Localization and Mapping
- [OVO-SLAM: Open-Vocabulary Online Simultaneous Localization and Mapping](https://arxiv.org/pdf/2411.15043) [code]

### Light Field Segmentation
- [Segment Anything in Light Fields for Real-Time Applications via Constrained Prompting](https://arxiv.org/pdf/2411.13840) [[code](https://roboticimaging.org/Projects/LFSAM/)]

### Applications
- [Towards Robust Automation of Surgical Systems via Digital Twin-based Scene Representations from Foundation Models](https://arxiv.org/pdf/2409.13107) [code]
- [Helpful DoggyBot: Open-World Object Fetching using Legged Robots and Vision-Language Models](https://arxiv.org/pdf/2410.00231) [[code](https://helpful-doggybot.github.io/)]
- [ROCKET-1: Mastering Open-World Interaction with Visual-Temporal Context Prompting](https://arxiv.org/pdf/2410.17856) [[code](https://github.com/CraftJarvis/ROCKET-1)]
- [GRS: Generating Robotic Simulation Tasks from Real-World Images](https://arxiv.org/pdf/2410.15536) [code]
- [Point of Interest Recognition and Tracking in Aerial Video during Live Cycling Broadcasts](https://www.mdpi.com/2076-3417/14/20/9246) [code]
- [Iterative Optimization Annotation Pipeline and ALSS-YOLO-Seg for Efficient Banana Plantation Segmentation in UAV Imagery](https://arxiv.org/pdf/2410.07955) [code]
- [Next Best Sense: Guiding Vision and Touch with FisherRF for 3D Gaussian Splatting](https://arxiv.org/pdf/2410.04680) [[code](https://github.com/armlabstanford/NextBestSense)]
