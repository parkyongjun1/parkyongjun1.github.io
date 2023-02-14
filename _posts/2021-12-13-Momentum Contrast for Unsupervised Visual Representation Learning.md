---
title: Paper Review. Momentum Contrast for Unsupervised Visual Representation Learning@CVPR’ 2020
author: YongJun Park
date: 2021-12-13 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Unsupervised, Self-supervised, Contrastive Learning, Pretrain]
math: true
pin: True
---

- [Paper link](https://openaccess.thecvf.com/content_CVPR_2020/papers/He_Momentum_Contrast_for_Unsupervised_Visual_Representation_Learning_CVPR_2020_paper.pdf)


## **Abstract**
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/10.png" width='800'>

## **Introduction**
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/3.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/4.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/5.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/6.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/7.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/8.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/9.png" width='800'>

## **MOCO**
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/11.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/12.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/13.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/14.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/15.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/16.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/17.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/18.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/19.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/20.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/21.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/22.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/23.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/24.png" width='800'>

## **Experiments**
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/25.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/26.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/27.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/28.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/29.png" width='800'>
<img src="/assets/papers/Momentum Contrast for Unsupervised Visual Representation Learning/30.png" width='800'>


## **Conclusions & Reviews**
- 큰 사이즈의 dictionary를 사용하여 충분한 양의 negative를 고려함으로써 성능을 끌어올림.

- dictionary를 queue 개념으로 접근하고 momentum 방법을 이용해 consistency를 유지함.

- transformer 구조에서도 self-supervised를 적용하면 좋을거 같다는 생각이 들었음. 

- augmentation이 중요하다고 생각이 되는데 augmentation에 따른 성능 차이가 없었던 점이 다소 아쉬웠음.


## **Reference**
