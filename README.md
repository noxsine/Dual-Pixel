<p align="center">
  <h3 align="center">A Collection of Dual-Pixel Sensors</h3>
</p>

This repository is a collection of dual-pixel (DP) related methods. It includes a curated list of papers, code, datasets, and other related resources on DP-based vision tasks, including depth estimation, defocus deblurring, autofocusing, and computational photography.

## Table of contents

- [Table of contents](#table-of-contents)
- [Sensor / Circuits / Hardware](#sensor--circuits--hardware)
- [Autofocus](#autofocus)
- [Depth / Disparity / 3D](#depth--disparity--3d)
- [Deblur / Restoration](#deblur--restoration)
- [Simulation / Modeling / Synthesis](#simulation--modeling--synthesis)
- [Other Dual-Pixel Applications](#other-dual-pixel-applications)
- [Datasets](#datasets)
- [Other Related DP Papers](#other-related-dp-papers)

## Sensor / Circuits / Hardware

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2014 | JPSTJ | [EOS 70D's Dual Pixel CMOS AF](https://doi.org/10.11454/photogrst.77.222) | Dual-Pixel CMOS AF | [Paper](https://doi.org/10.11454/photogrst.77.222) |
| 2016 | MTA | [A Low Noise and High Sensitivity Image Sensor with Imaging and Phase-Difference Detection AF in All Pixels](https://doi.org/10.3169/mta.4.123) | All-pixel PDAF / sensor | [Paper](https://doi.org/10.3169/mta.4.123) |
| 2019 | IISW | [A Small-size Dual Pixel CMOS Image Sensor with Vertically Broad Photodiode of 0.61 um pitch](https://imagesensors.org/Past%20Workshops/2019%20Workshop/2019%20Papers/R30.pdf) | Sensor design | [Paper](https://imagesensors.org/Past%20Workshops/2019%20Workshop/2019%20Papers/R30.pdf) |
| 2021 | IISW | [A Smart Dual Pixel Technology for Accurate and All-Directional Auto Focus in CMOS Image Sensors](https://doi.org/10.60928/klx5-qji6) | Sensor / autofocus | [Paper](https://doi.org/10.60928/klx5-qji6) |
| 2021 | VLSI | [All-Directional Dual Pixel Auto Focus Technology in CMOS Image Sensors](https://doi.org/10.23919/VLSITechnologyandCircuits52059.2021.9492472) | Sensor / autofocus | [Paper](https://doi.org/10.23919/VLSITechnologyandCircuits52059.2021.9492472) |
| 2021 | Hot Chips | [World Largest Mobile Image Sensor with All Directional Phase Detection Auto Focus Function](https://ieeexplore.ieee.org/document/9567122) | Mobile image sensor | [Paper](https://ieeexplore.ieee.org/document/9567122) |
| 2022 | ISSCC | [A 1/1.57-Inch 50Mpixel CMOS Image Sensor With 1.0 um All-Directional Dual Pixel by 0.5 um-Pitch Full-Depth Deep-Trench Isolation Technology](https://doi.org/10.1109/ISSCC42614.2022.9731567) | Sensor / all-directional DP | [Paper](https://doi.org/10.1109/ISSCC42614.2022.9731567) |
| 2024 | SSE | [Pinning Voltage Model of Vertical Pinned Photodiode for Dual-Pixel Image Sensor](https://doi.org/10.1016/j.sse.2024.108919) | Device modeling | [Paper](https://doi.org/10.1016/j.sse.2024.108919) |
| 2025 | IISW | [A 0.45um-pitch Photodiode Based 1-layer Dual Pixel for CMOS Image Sensor with High Full-Well Capacity and Low Noise](https://doi.org/10.60928/8w7q-kq5j) | Sensor design | [Paper](https://doi.org/10.60928/8w7q-kq5j) |

## Autofocus

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2018 | ECCV | [Revisiting Autofocus for Smartphone Cameras](https://doi.org/10.1007/978-3-030-01267-0_32) | Autofocus | [Paper](https://doi.org/10.1007/978-3-030-01267-0_32) |
| 2020 | CVPR | [Learning to Autofocus](https://openaccess.thecvf.com/content_CVPR_2020/html/Herrmann_Learning_to_Autofocus_CVPR_2020_paper.html) | Autofocus | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Herrmann_Learning_to_Autofocus_CVPR_2020_paper.html) / [Project](https://learntoautofocus-google.github.io/) |
| 2023 | ICCV | [Exploring Positional Characteristics of Dual-Pixel Data for Camera Autofocus](https://openaccess.thecvf.com/content/ICCV2023/html/Choi_Exploring_Positional_Characteristics_of_Dual-Pixel_Data_for_Camera_Autofocus_ICCV_2023_paper.html) | Autofocus | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Choi_Exploring_Positional_Characteristics_of_Dual-Pixel_Data_for_Camera_Autofocus_ICCV_2023_paper.html) |

## Depth / Disparity / 3D

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2018 | SIGGRAPH | [Synthetic Depth-of-Field with a Single-Camera Mobile Phone](https://doi.org/10.1145/3197517.3201329) | Mobile portrait / DP-assisted DoF | [Paper](https://doi.org/10.1145/3197517.3201329) / [arXiv](https://arxiv.org/abs/1806.04171) |
| 2019 | ICCV | [Learning Single Camera Depth Estimation Using Dual-Pixels](https://openaccess.thecvf.com/content_ICCV_2019/html/Garg_Learning_Single_Camera_Depth_Estimation_Using_Dual-Pixels_ICCV_2019_paper.html) | Depth | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Garg_Learning_Single_Camera_Depth_Estimation_Using_Dual-Pixels_ICCV_2019_paper.html) / [Code+Data](https://github.com/google-research/google-research/tree/master/dual_pixels) |
| 2020 | ICCP | [Modeling Defocus-Disparity in Dual-Pixel Sensors](https://abhijithpunnappurath.github.io/ICCP2020.pdf) | Depth / defocus-disparity | [Paper](https://abhijithpunnappurath.github.io/ICCP2020.pdf) / [Code+Data](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity) |
| 2020 | ECCV | [Du2Net: Learning Depth Estimation from Dual-Cameras and Dual-Pixels](https://augmentedperception.github.io/du2net/) | Depth / disparity | [Project](https://augmentedperception.github.io/du2net/) |
| 2021 | CVPR | [Dual Pixel Exploration: Simultaneous Depth Estimation and Image Restoration](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_Dual_Pixel_Exploration_Simultaneous_Depth_Estimation_and_Image_Restoration_CVPR_2021_paper.html) | Depth + restoration | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_Dual_Pixel_Exploration_Simultaneous_Depth_Estimation_and_Image_Restoration_CVPR_2021_paper.html) / [Code+Data](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration) |
| 2021 | TIFS | [Single-Shot Face Anti-Spoofing for Dual Pixel Camera](https://ieeexplore.ieee.org/document/9248008) | Depth / anti-spoofing | [Paper](https://ieeexplore.ieee.org/document/9248008) |
| 2022 | ECCV | [Facial Depth and Normal Estimation using Single Dual-Pixel Camera](https://arxiv.org/abs/2111.12928) | Facial depth / normals | [Paper](https://arxiv.org/abs/2111.12928) / [Code+Data](https://github.com/MinJunKang/DualPixelFace) |
| 2023 | CVPR | [Spatio-Focal Bidirectional Disparity Estimation From a Dual-Pixel Image](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_Spatio-Focal_Bidirectional_Disparity_Estimation_From_a_Dual-Pixel_Image_CVPR_2023_paper.html) | Disparity | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_Spatio-Focal_Bidirectional_Disparity_Estimation_From_a_Dual-Pixel_Image_CVPR_2023_paper.html) / [Code](https://github.com/KAIST-VCLAB/dual-pixel-disparity) |
| 2024 | ECCV | [Resolving Scale Ambiguity in Multi-view 3D Reconstruction Using Dual-Pixel Sensors](https://link.springer.com/chapter/10.1007/978-3-031-72973-7_10) | 3D reconstruction | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-72973-7_10) / [Code](https://github.com/kohei-ashida/dp-sfm) |
| 2024 | 3DV | [Continuous Cost Aggregation for Dual-Pixel Disparity Extraction](https://arxiv.org/abs/2306.07921) | Disparity extraction | [Paper](https://arxiv.org/abs/2306.07921) |
| 2024 | CVPR | [Passive Snapshot Coded Aperture Dual-Pixel RGB-D Imaging](https://arxiv.org/abs/2402.18102) | RGB-D imaging | [Paper](https://arxiv.org/abs/2402.18102) / [Code](https://github.com/shadowfax11/coded-dual-pixels) |
| 2024 | TPAMI | [Weakly-Supervised Depth Estimation and Image Deblurring via Dual-Pixel Sensors](https://doi.org/10.1109/TPAMI.2024.3458974) | Depth + deblurring | [Paper](https://doi.org/10.1109/TPAMI.2024.3458974) / [Code](https://github.com/zwxu064/DiffImageWarpingCUDA) |
| 2025 | WACV | [Revisiting Disparity from Dual-Pixel Images: Physics-Informed Lightweight Depth Estimation](https://arxiv.org/abs/2411.04714) | Depth | [Paper](https://arxiv.org/abs/2411.04714) |
| 2025 | ICCV | [Simulating Dual-Pixel Images From Ray Tracing For Depth Estimation](https://openaccess.thecvf.com/content/ICCV2025/html/He_Simulating_Dual-Pixel_Images_From_Ray_Tracing_For_Depth_Estimation_ICCV_2025_paper.html) | Simulation + depth | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/He_Simulating_Dual-Pixel_Images_From_Ray_Tracing_For_Depth_Estimation_ICCV_2025_paper.html) |
| 2025 | MVA | [FMDP: Leveraging a Foundation Model for Dual-Pixel Disparity Estimation](https://doi.org/10.23919/MVA65244.2025.11175082) | Disparity | [Paper](https://doi.org/10.23919/MVA65244.2025.11175082) |
| 2025 | arXiv / IROS | [DiFuse-Net: RGB and Dual-Pixel Depth Estimation using Window Bi-directional Parallax Attention and Cross-modal Transfer Learning](https://arxiv.org/abs/2506.14709) | RGB + DP depth | [Paper](https://arxiv.org/abs/2506.14709) |

## Deblur / Restoration

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2019 | CVPR | [Reflection Removal Using a Dual-Pixel Sensor](https://openaccess.thecvf.com/content_CVPR_2019/html/Punnappurath_Reflection_Removal_Using_a_Dual-Pixel_Sensor_CVPR_2019_paper.html) | Reflection removal | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Punnappurath_Reflection_Removal_Using_a_Dual-Pixel_Sensor_CVPR_2019_paper.html) / [Code](https://github.com/abhijithpunnappurath/dprr) |
| 2020 | ECCV | [Defocus Deblurring Using Dual-Pixel Data](https://www.eecs.yorku.ca/~abuolaim/eccv_2020_dp_defocus_deblurring/) | Defocus deblurring | [Project](https://www.eecs.yorku.ca/~abuolaim/eccv_2020_dp_defocus_deblurring/) / [Code+Data](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel) |
| 2021 | CVPRW | [NTIRE 2021 Challenge for Defocus Deblurring Using Dual-Pixel Images: Methods and Results](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Abuolaim_NTIRE_2021_Challenge_for_Defocus_Deblurring_Using_Dual-Pixel_Images_Methods_CVPRW_2021_paper.html) | Benchmark / challenge | [Paper](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Abuolaim_NTIRE_2021_Challenge_for_Defocus_Deblurring_Using_Dual-Pixel_Images_Methods_CVPRW_2021_paper.html) |
| 2021 | ICCV | [Defocus Map Estimation and Deblurring From a Single Dual-Pixel Image](https://openaccess.thecvf.com/content/ICCV2021/html/Xin_Defocus_Map_Estimation_and_Deblurring_From_a_Single_Dual-Pixel_Image_ICCV_2021_paper.html) | Deblurring + defocus map | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Xin_Defocus_Map_Estimation_and_Deblurring_From_a_Single_Dual-Pixel_Image_ICCV_2021_paper.html) / [Code+Data](https://github.com/cmu-ci-lab/dual_pixel_defocus_estimation_deblurring) |
| 2021 | ICCV | [Learning To Reduce Defocus Blur by Realistically Modeling Dual-Pixel Data](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) | Deblurring | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) / [Code+Data](https://github.com/Abdullah-Abuolaim/recurrent-defocus-deblurring-synth-dual-pixel) |
| 2021 | ICTC | [Disparity Probability Volume Guided Defocus Deblurring Using Dual Pixel Data](https://ieeexplore.ieee.org/document/9621024) | Deblurring | [Paper](https://ieeexplore.ieee.org/document/9621024) |
| 2022 | WACV | [Improving Single-Image Defocus Deblurring: How Dual-Pixel Images Help Through Multi-Task Learning](https://arxiv.org/abs/2108.05251) | Deblurring | [Paper](https://arxiv.org/abs/2108.05251) / [Code+Data](https://github.com/Abdullah-Abuolaim/multi-task-defocus-deblurring-dual-pixel-nimat) |
| 2022 | ICME | [Dynamic Multi-Scale Network for Dual-Pixel Images Defocus Deblurring with Transformer](https://ieeexplore.ieee.org/document/9859631) | Deblurring | [Paper](https://ieeexplore.ieee.org/document/9859631) |
| 2022 | IEEE/CAA JAS | [BaMBNet: A Blur-Aware Multi-Branch Network for Dual-Pixel Defocus Deblurring](https://doi.org/10.1109/JAS.2022.105563) | Deblurring | [Paper](https://doi.org/10.1109/JAS.2022.105563) / [Code](https://github.com/junjun-jiang/BaMBNet) |
| 2023 | ICASSP | [MRNet: Multi-Refinement Network for Dual-pixel Images Defocus Deblurring](https://ieeexplore.ieee.org/document/10096428) | Deblurring | [Paper](https://ieeexplore.ieee.org/document/10096428) |
| 2023 | CVPR | [K3DN: Disparity-Aware Kernel Estimation for Dual-Pixel Defocus Deblurring](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_K3DN_Disparity-Aware_Kernel_Estimation_for_Dual-Pixel_Defocus_Deblurring_CVPR_2023_paper.html) | Deblurring | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_K3DN_Disparity-Aware_Kernel_Estimation_for_Dual-Pixel_Defocus_Deblurring_CVPR_2023_paper.html) |
| 2024 | CVPR | [LDP: Language-driven Dual-Pixel Image Defocus Deblurring Network](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_LDP_Language-driven_Dual-Pixel_Image_Defocus_Deblurring_Network_CVPR_2024_paper.html) | Deblurring | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_LDP_Language-driven_Dual-Pixel_Image_Defocus_Deblurring_Network_CVPR_2024_paper.html) / [Code](https://github.com/noxsine/LDP) |
| 2025 | Neurocomputing | [Learning dual-pixel alignment for defocus deblurring](https://doi.org/10.1016/j.neucom.2024.128880) | Deblurring | [Paper](https://doi.org/10.1016/j.neucom.2024.128880) / [Code](https://github.com/liyucs/DPANet) |
| 2025 | EAAI | [Parallax-aware dual-view feature enhancement and adaptive detail compensation for dual-pixel defocus deblurring](https://doi.org/10.1016/j.engappai.2024.109612) | Deblurring | [Paper](https://doi.org/10.1016/j.engappai.2024.109612) |
| 2025 | arXiv | [Adjust Your Focus: Defocus Deblurring From Dual-Pixel Images Using Explicit Multi-Scale Cross-Correlation](https://arxiv.org/abs/2502.11002) | Deblurring | [Paper](https://arxiv.org/abs/2502.11002) |

## Simulation / Modeling / Synthesis

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2019 | Optics Express | [Joint electromagnetic and ray-tracing simulations for quad-pixel sensor and computational imaging](https://doi.org/10.1364/OE.27.030486) | Quad-pixel simulation | [Paper](https://doi.org/10.1364/OE.27.030486) |
| 2020 | ICCP | [Modeling Defocus-Disparity in Dual-Pixel Sensors](https://abhijithpunnappurath.github.io/ICCP2020.pdf) | DP image formation | [Paper](https://abhijithpunnappurath.github.io/ICCP2020.pdf) / [Code+Data](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity) |
| 2021 | ICCV | [Learning To Reduce Defocus Blur by Realistically Modeling Dual-Pixel Data](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) | Synthetic DP generation | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) / [Code+Data](https://github.com/Abdullah-Abuolaim/recurrent-defocus-deblurring-synth-dual-pixel) |
| 2022 | SPIE | [Deep Learning Applied to Quad-Pixel Plenoptic Images](https://doi.org/10.1117/12.2597001) | Quad-pixel plenoptic imaging | [Paper](https://doi.org/10.1117/12.2597001) |
| 2023 | ICCP | [Learning to Synthesize Photorealistic Dual-pixel Images from RGBD Frames](https://doi.org/10.1109/ICCP56744.2023.10233839) | DP synthesis / simulator | [Paper](https://doi.org/10.1109/ICCP56744.2023.10233839) / [Code+Data](https://github.com/feiran-l/Neural-Dual-Pixel-Simulator) |
| 2024 | ICCP | [Stereo-Knowledge Distillation from dpMV to Dual Pixels for Light Field Video Reconstruction](https://doi.org/10.1109/ICCP61108.2024.10644854) | Light field / DP reconstruction | [Paper](https://doi.org/10.1109/ICCP61108.2024.10644854) |
| 2024 | TOG | [Split-Aperture 2-in-1 Computational Cameras](https://doi.org/10.1145/3658170) | Split-aperture cameras | [Paper](https://doi.org/10.1145/3658170) / [Project](https://light.princeton.edu/publication/2in1-camera) |
| 2025 | ICCV | [Simulating Dual-Pixel Images From Ray Tracing For Depth Estimation](https://openaccess.thecvf.com/content/ICCV2025/html/He_Simulating_Dual-Pixel_Images_From_Ray_Tracing_For_Depth_Estimation_ICCV_2025_paper.html) | Ray-traced DP simulation | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/He_Simulating_Dual-Pixel_Images_From_Ray_Tracing_For_Depth_Estimation_ICCV_2025_paper.html) |

## Other Dual-Pixel Applications

| Year | Pub | Paper | App | Links |
|:---:|:---:|:---|:---|:---|
| 2019 | CVPR | [Reflection Removal Using a Dual-Pixel Sensor](https://openaccess.thecvf.com/content_CVPR_2019/html/Punnappurath_Reflection_Removal_Using_a_Dual-Pixel_Sensor_CVPR_2019_paper.html) | Reflection removal | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Punnappurath_Reflection_Removal_Using_a_Dual-Pixel_Sensor_CVPR_2019_paper.html) / [Code](https://github.com/abhijithpunnappurath/dprr) |
| 2021 | TIFS | [Single-Shot Face Anti-Spoofing for Dual Pixel Camera](https://ieeexplore.ieee.org/document/9248008) | Biometrics / anti-spoofing | [Paper](https://ieeexplore.ieee.org/document/9248008) |
| 2022 | BMVC | [Dual-Pixel Raindrop Removal](https://arxiv.org/abs/2210.13321) | Deraining / raindrop removal | [Paper](https://arxiv.org/abs/2210.13321) |
| 2024 | TPAMI | [Dual-Pixel Raindrop Removal](https://doi.org/10.1109/TPAMI.2024.3442955) | Deraining / raindrop removal | [Paper](https://doi.org/10.1109/TPAMI.2024.3442955) |
| 2019 | Optics Express | [Joint electromagnetic and ray-tracing simulations for quad-pixel sensor and computational imaging](https://doi.org/10.1364/OE.27.030486) | Quad-pixel modeling | [Paper](https://doi.org/10.1364/OE.27.030486) |
| 2022 | SPIE | [Deep Learning Applied to Quad-Pixel Plenoptic Images](https://doi.org/10.1117/12.2597001) | Quad-pixel plenoptic imaging | [Paper](https://doi.org/10.1117/12.2597001) |
| 2024 | BMVC | [Disparity Estimation Using a Quad-Pixel Sensor](https://arxiv.org/abs/2409.00665) | Quad-pixel disparity | [Paper](https://arxiv.org/abs/2409.00665) |
| 2024 | TOG | [Split-Aperture 2-in-1 Computational Cameras](https://doi.org/10.1145/3658170) | Split-aperture sensing | [Paper](https://doi.org/10.1145/3658170) / [Project](https://light.princeton.edu/publication/2in1-camera) |
| 2025 | CVPR | [All-directional Disparity Estimation for Real-world QPD Images](https://openaccess.thecvf.com/content/CVPR2025/html/Yu_All-directional_Disparity_Estimation_for_Real-world_QPD_Images_CVPR_2025_paper.html) | QPD disparity | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Yu_All-directional_Disparity_Estimation_for_Real-world_QPD_Images_CVPR_2025_paper.html) |
| 2025 | CVPR | [Quad-Pixel Image Defocus Deblurring: A New Benchmark and Model](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_Quad-Pixel_Image_Defocus_Deblurring_A_New_Benchmark_and_Model_CVPR_2025_paper.html) | QPD deblurring | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_Quad-Pixel_Image_Defocus_Deblurring_A_New_Benchmark_and_Model_CVPR_2025_paper.html) |

## Datasets

| Year | Pub | Paper / Dataset | Detail | Links |
|:---:|:---:|:---|:---|:---|
| 2019 | ICCV | [Learning Single Camera Depth Estimation Using Dual-Pixels](https://openaccess.thecvf.com/content_ICCV_2019/html/Garg_Learning_Single_Camera_Depth_Estimation_Using_Dual-Pixels_ICCV_2019_paper.html) | Google DP depth dataset | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Garg_Learning_Single_Camera_Depth_Estimation_Using_Dual-Pixels_ICCV_2019_paper.html) / [Code+Data](https://github.com/google-research/google-research/tree/master/dual_pixels) |
| 2020 | ICCP | [Modeling Defocus-Disparity in Dual-Pixel Sensors](https://abhijithpunnappurath.github.io/ICCP2020.pdf) | DP defocus-disparity dataset | [Paper](https://abhijithpunnappurath.github.io/ICCP2020.pdf) / [Code+Data](https://github.com/abhijithpunnappurath/dual-pixel-defocus-disparity) |
| 2020 | ECCV | [Defocus Deblurring Using Dual-Pixel Data](https://www.eecs.yorku.ca/~abuolaim/eccv_2020_dp_defocus_deblurring/) | DPDD benchmark | [Project](https://www.eecs.yorku.ca/~abuolaim/eccv_2020_dp_defocus_deblurring/) / [Code+Data](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel) |
| 2020 | CVPR | [Learning to Autofocus](https://openaccess.thecvf.com/content_CVPR_2020/html/Herrmann_Learning_to_Autofocus_CVPR_2020_paper.html) | L2A autofocus dataset | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Herrmann_Learning_to_Autofocus_CVPR_2020_paper.html) / [Project](https://learntoautofocus-google.github.io/) |
| 2021 | CVPRW | [NTIRE 2021 Challenge for Defocus Deblurring Using Dual-Pixel Images](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Abuolaim_NTIRE_2021_Challenge_for_Defocus_Deblurring_Using_Dual-Pixel_Images_Methods_CVPRW_2021_paper.html) | DPDD challenge benchmark | [Paper](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Abuolaim_NTIRE_2021_Challenge_for_Defocus_Deblurring_Using_Dual-Pixel_Images_Methods_CVPRW_2021_paper.html) |
| 2021 | CVPR | [Dual Pixel Exploration: Simultaneous Depth Estimation and Image Restoration](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_Dual_Pixel_Exploration_Simultaneous_Depth_Estimation_and_Image_Restoration_CVPR_2021_paper.html) | Synthetic DP simulator from NYUD-style depth | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Pan_Dual_Pixel_Exploration_Simultaneous_Depth_Estimation_and_Image_Restoration_CVPR_2021_paper.html) / [Code+Data](https://github.com/panpanfei/Dual-Pixel-Exploration-Simultaneous-Depth-Estimation-and-Image-Restoration) |
| 2021 | ICCV | [Learning To Reduce Defocus Blur by Realistically Modeling Dual-Pixel Data](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) | Synthetic DP data from SYNTHIA-like scenes | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Abuolaim_Learning_To_Reduce_Defocus_Blur_by_Realistically_Modeling_Dual-Pixel_Data_ICCV_2021_paper.html) / [Code+Data](https://github.com/Abdullah-Abuolaim/recurrent-defocus-deblurring-synth-dual-pixel) |
| 2023 | ICCP | [Learning to Synthesize Photorealistic Dual-pixel Images from RGBD Frames](https://doi.org/10.1109/ICCP56744.2023.10233839) | Neural DP simulator / synthetic-real data | [Paper](https://doi.org/10.1109/ICCP56744.2023.10233839) / [Code+Data](https://github.com/feiran-l/Neural-Dual-Pixel-Simulator) |
| 2025 | CVPR | [Quad-Pixel Image Defocus Deblurring: A New Benchmark and Model](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_Quad-Pixel_Image_Defocus_Deblurring_A_New_Benchmark_and_Model_CVPR_2025_paper.html) | QPDD / quad-pixel benchmark | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_Quad-Pixel_Image_Defocus_Deblurring_A_New_Benchmark_and_Model_CVPR_2025_paper.html) |

## Other Related DP Papers

| Year | Pub | Paper | Why it is included | Links |
|:---:|:---:|:---|:---|:---|
| 2021 | CVPRW | [ATTSF: Attention! Stay Focus!](https://arxiv.org/abs/2104.07925) | DPDD challenge method | [Paper](https://arxiv.org/abs/2104.07925) / [Code](https://github.com/tuvovan/ATTSF) |
| 2021 | CVPR | [Iterative Filter Adaptive Network for Single Image Defocus Deblurring](https://openaccess.thecvf.com/content/CVPR2021/html/Lee_Iterative_Filter_Adaptive_Network_for_Single_Image_Defocus_Deblurring_CVPR_2021_paper.html) | Common DPDD baseline | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Lee_Iterative_Filter_Adaptive_Network_for_Single_Image_Defocus_Deblurring_CVPR_2021_paper.html) |
| 2021 | CVPR | [Multi-Stage Progressive Image Restoration](https://openaccess.thecvf.com/content/CVPR2021/html/Zamir_Multi-Stage_Progressive_Image_Restoration_CVPR_2021_paper.html) | Common restoration baseline in DP papers | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Zamir_Multi-Stage_Progressive_Image_Restoration_CVPR_2021_paper.html) |
| 2022 | CVPR | [Restormer: Efficient Transformer for High-Resolution Image Restoration](https://openaccess.thecvf.com/content/CVPR2022/html/Zamir_Restormer_Efficient_Transformer_for_High-Resolution_Image_Restoration_CVPR_2022_paper.html) | Frequently reported on DPDD / used as DP deblurring baseline | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zamir_Restormer_Efficient_Transformer_for_High-Resolution_Image_Restoration_CVPR_2022_paper.html) |
| 2022 | CVPR | [Uformer: A General U-Shaped Transformer for Image Restoration](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Uformer_A_General_U-Shaped_Transformer_for_Image_Restoration_CVPR_2022_paper.html) | Frequently reused as a DPDD baseline | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Uformer_A_General_U-Shaped_Transformer_for_Image_Restoration_CVPR_2022_paper.html) |
| 2022 | CVPR | [Deep Generalized Unfolding Networks for Image Restoration](https://openaccess.thecvf.com/content/CVPR2022/html/Mou_Deep_Generalized_Unfolding_Networks_for_Image_Restoration_CVPR_2022_paper.html) | General restoration baseline in later DP works | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Mou_Deep_Generalized_Unfolding_Networks_for_Image_Restoration_CVPR_2022_paper.html) |
| 2022 | CVPR | [Learning to Deblur Using Light Field Generated and Real Defocus Images](https://openaccess.thecvf.com/content/CVPR2022/html/Ruan_Learning_to_Deblur_Using_Light_Field_Generated_and_Real_Defocus_Images_CVPR_2022_paper.html) | Strong defocus deblurring comparison paper | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Ruan_Learning_to_Deblur_Using_Light_Field_Generated_and_Real_Defocus_Images_CVPR_2022_paper.html) |
| 2023 | TPAMI | [Learning Enriched Features for Fast Image Restoration and Enhancement](https://doi.org/10.1109/TPAMI.2022.3167175) | MIRNet-v2; includes dual-pixel defocus deblurring among restoration tasks | [Paper](https://doi.org/10.1109/TPAMI.2022.3167175) |



