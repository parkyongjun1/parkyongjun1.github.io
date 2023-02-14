---
title: Paper Review. DEFORMABLE DETR_DEFORMABLE TRANSFORMERS@ICLR’2021
author: YongJun Park
date: 2022-02-04 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Object Detection, Deformable, Transformer, 1 stage, 2 stage]
math: true
pin: True
---

- [Paper link](https://iclr.cc/virtual/2021/oral/3448)


## **Introduction**
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/3.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/4.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/5.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/6.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/7.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/8.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/9.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/10.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/11.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/12.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/13.png" width='800'>

## **Deformable DETR**
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/14.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/15.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/16.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/17.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/18.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/19.png" width='800'>

## **Experiments**
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/20.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/21.png" width='800'>
<img src="/assets/papers/DEFORMABLE DETR_DEFORMABLE TRANSFORMERS/22.png" width='800'>

## **Conclusions & Reviews**
- multi-scale feature map을 encoder input으로 사용하여  FPN의 효과를 도출함.  

- deformable attention을 통해 computation을 줄임으로써 학습시간을 대폭 단축시킴.

- object detection에서 multi-scale의 중요성을 다시 한번 느낌.

- DCN의 개념을 가져와 모든 key를 고려하지 않고 query에 인접한 key들만 attention을 계산하는 것이 신선함.

- 회전된 bbox를 예측하는 항공 이미지 task에도 적용해보면 좋을 거 같다는 생각을 함.


## **Reference**
