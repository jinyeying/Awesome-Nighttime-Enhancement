# Awesome-Nighttime-Enhancement
Collection of recent nighttime enhancement low-level works, including datasets, papers, codes and metrics.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/jinyeying/Awesome-Nighttime-Enhancement)

## 1. Nighttime Light-Effects Suppression
### 1.1 Dataset
* [[Light-effects data]](https://www.dropbox.com/sh/ro8fs629ldebzc2/AAD_W78jDffsJhH-smJr0cNSa?dl=0) <br>

### 1.2 Unsupervised-Deep-Learning
* `ECCV2022`
**Unsupervised Night Image Enhancement: When Layer Decomposition Meets Light-Effects Suppression** \
[Yeying Jin](https://jinyeying.github.io/), [Wenhan Yang](https://flyywh.github.io/) and [Robby T. Tan](https://tanrobby.github.io/pub.html)\
[[Paper]](https://arxiv.org/abs/2207.10564)
[[Code]](https://github.com/jinyeying/night-enhancement)

### 1.3 Semi-Supervised-Deep-Learning
* `CVPR2021`
**Nighttime Visibility Enhancement by Increasing the Dynamic Range and Suppression of Light Effects** \
[Aashish Sharma](https://aasharma90.github.io/) and [Robby T. Tan](https://tanrobby.github.io/pub.html) \
[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sharma_Nighttime_Visibility_Enhancement_by_Increasing_the_Dynamic_Range_and_Suppression_CVPR_2021_paper.pdf)[[Light-effects data]](https://www.dropbox.com/sh/ro8fs629ldebzc2/AAD_W78jDffsJhH-smJr0cNSa?dl=0)

### 1.4 Zero-Shot-Deep-Learning
* `IJCAI2022`
From Generation to Suppression: Towards Effective Irregular glow suppression for Nighttime Visibility Enhancement
[[Paper]](https://arxiv.org/abs/2307.16783)

## 2. Nighttime Dehazing/Defogging
### 2.1 Dataset
* [[GTA5 Nighttime Fog Data]](https://www.dropbox.com/sh/gfw44ttcu5czrbg/AACr2GZWvAdwYPV0wgs7s00xa?dl=0) <br>

### 2.2 Semi-Supervised-Deep-Learning
* `ACMMM2023`
**Enhancing Visibility in Nighttime Haze Images Using Guided APSF and Gradient Adaptive Convolution** \
[Yeying Jin*](https://jinyeying.github.io/), Beibei Lin*, Wending Yan, Wei Ye, Yuan Yuan and [Robby T. Tan](https://tanrobby.github.io/pub.html) \
[[Paper]](https://arxiv.org/abs/2308.01738) [[Code]](https://github.com/jinyeying/nighttime_dehaze)

* `ACMMM2023`
**NightHazeFormer: Single Nighttime Haze Removal Using Prior Query Transformer** [[Paper]](https://arxiv.org/abs/2305.09533)

  
* `ECCV2020`
**Nighttime Defogging Using High-Low Frequency Decomposition and Grayscale-Color Networks** \
Wending Yan, [Robby T. Tan](https://tanrobby.github.io/pub.html) and [Dengxin Dai](https://vas.mpi-inf.mpg.de/) \
[[Paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570460.pdf)


### 2.3 Supervised-Deep-Learning
* `VisualComputer,2022`
Multi-path Dilated Convolution Network for Haze and Glow Removal in Nighttime Images
* `ACMMM2020`
Nighttime Dehazing with a Synthetic Benchmark
[[Code]](https://github.com/chaimi2013/3R)
* `Arxiv2019`
Night Time Haze and Glow Removal using Deep Dilated Convolutional Network
* `PCM2018`
HDP-Net: Haze Density Prediction Network for Nighttime Dehazing
[[Code]](https://github.com/nicholasly/HDP-Net)

### 2.4 Traditional
* `TCSVT2022`
Multi-purpose Oriented Single Nighttime Image Haze Removal based on Unified Variational Retinex Model
* `Engineering Applications of AI,2022`
Single Nighttime Image Dehazing based on Unified Variational Decomposition Model and Multi-scale Contrast Enhancement
* `TIP2022`
Variational Single Nighttime Image Haze Removal With a Gray Haze-Line Prior
* `CVPRW2022`
Nighttime Image Dehazing Based on Variational Decomposition Model
* `Multimedia Tools and Applications,2022`
Joint Dehazing and Denoising for Single Nighttime Image via Multi-scale Decomposition
* `CVIU2021`
Nighttime Image Dehazing Based on Retinex and Dark Channel Prior using Taylor Series Expansion
* `Signal Processing,2021`
Single Nighttime Image Dehazing based on Image Decomposition
* `TIP2020`
Day and Night-time Dehazing by Local Airlight Estimation
* `IEEE Access,2020`
Integrating Haze Density Features for Fast Nighttime Image Dehazing
* `IEEE Access,2019`
Nighttime Single Image Dehazing via Pixel-Wise Alpha Blending
[[Code]](https://github.com/yuteng/nighttime-dehazing)
* `IEEE Access,2019`
A Unified Variational Model for Single Image Dehazing
* `CVPR2017`
Fast Haze Removal for Nighttime Image using Maximum Reflectance Prior
[[Code]](https://github.com/chaimi2013/MRP)
* `CVPR2017`
Night-time Dehazing by Fusion
* `ICCV2015`
Nighttime Haze Removal with Glow and Multiple Light Colors 
[[Paper]](https://www.dropbox.com/s/b7l89f31erqmjr0/2015_iccv_nightdehazing.pdf?dl=0)
[[Code]](https://tanrobby.github.io/code.html)\
[Yu Li](http://yu-li.github.io/), [Robby T. Tan](https://tanrobby.github.io/pub.html), and [Michael S. Brown](https://www.eecs.yorku.ca/~mbrown/)
* `ICIP2014`
Nighttime Haze Removal Based on a New Imaging Model
[[Code]](https://github.com/chaimi2013/NighttimeDehaze)
* `ICIP2012`
Nighttime Haze Removal using Color Transfer Pre-processing and Dark Channel Prior

### Survey
* `Archives of Computational Methods in Engineering,2021`
Nighttime Image‑Dehazing: A Review and Quantitative Benchmarking

## 3. Nighttime Ghost and Flare Removal
* `CVPR2023`
Nighttime Smartphone Reflective Flare Removal Using Optical Center Symmetry Prior\
[Yuekun Dai](https://ykdai.github.io/), Yihang Luo, Shangchen Zhou, [Chongyi Li](https://li-chongyi.github.io/), and [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/) \
[[Paper]](https://arxiv.org/abs/2303.15046)
[[Code]](https://github.com/ykdai/BracketFlare)

* `NeurIPS Dataset 2022`
Flare7K: A Phenomenological Nighttime Flare Removal Dataset\
[Yuekun Dai](https://ykdai.github.io/), [Chongyi Li](https://li-chongyi.github.io/), Shangchen Zhou, Ruicheng Feng, and [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/) \
[[Paper]](https://arxiv.org/abs/2210.06570) [[Code]](https://github.com/ykdai/Flare7K)

* `arXiv2023`
Flare7K++: Mixing Synthetic and Real Datasets for Nighttime Flare Removal and Beyond\
[Yuekun Dai](https://ykdai.github.io/), [Chongyi Li](https://li-chongyi.github.io/), Shangchen Zhou, Ruicheng Feng, Yihang Luo, and [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/)\
[[Paper]](https://arxiv.org/abs/2306.04236) [[Code]](https://github.com/ykdai/Flare7K)

* `ISCAS2023`
Removing Image Artifacts From Scratched Lens Protectors\
[[Paper]](https://arxiv.org/format/2305.09533) [[Code]](https://github.com/wyf0912/flare-removal)

## 4. Nighttime Deraining
* `AAAI2024`
NightRain: Nighttime Video Deraining via Adaptive-Rain-Removal and Adaptive-Correction\
[Beibei Lin*](https://bb12346.github.io/), [Yeying Jin*](https://jinyeying.github.io/), Wending Yan, Wei Ye, Yuan Yuan, Sunli Zhang, [Robby T. Tan](https://tanrobby.github.io/pub.html)


