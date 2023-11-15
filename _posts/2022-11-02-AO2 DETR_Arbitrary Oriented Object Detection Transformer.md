---
title: Paper Review. AO2 DETR_Arbitrary Oriented Object Detection Transformer@TCSVT’ 2022
author: YongJun Park
date: 2022-11-02 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Oriented-Object Detection, Aerial, Deformable DETR, 2 stage, FRM]
math: true
pin: True
---

- [Paper link](https://arxiv.org/abs/2205.12785)


## **Introduction**
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/3.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/4.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/5.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/6.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/7.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/8.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/9.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/10.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/11.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/12.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/13.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/14.png" width='800'>

## **2-stage Deformable DETR**
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/15.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/16.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/17.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/18.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/19.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/20.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/21.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/22.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/23.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/24.png" width='800'>

## **AO2 DETR**
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/25.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/26.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/27.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/28.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/29.png" width='800'>

## **Experiments**
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/30.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/31.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/32.png" width='800'>
<img src="/assets/papers/AO2 DETR_Arbitrary Oriented Object Detection Transformer/33.png" width='800'>


## **Conclusions & Reviews**
- 항공 도메인에 transformer 구조의 deformable detr 구조를 적용함.

- 트랜스포머 구조에 spatial한 정보를 넣어주어 성능 향상을 이끌어냄.

- Oriented proposal을 정의하고, re-encoding을 통해 refine된 feature를 사용함으로써 cnn SOTA인 Oriented-RCNN과 비교해 준수한 성능을 달성.

- FRM을 개인 연구에 적용 후 성능 분석을 진행하고 dynamic anchor box generation과 query selection 부분의 상관 관계를 파악해볼 예정.

- 제안한 방법의 완벽한 open code를 배포하지 않아 FRM 구현은 가능했지만, reference point(decoder)에 각도를 고려하는 방법을 이식할 수 없음.

- Deformable DETR에서 xywh를 이용해 xy는 reference point로 wh는 deformable attention을 고려하는 구역을 정하는 scale로 사용하지만, angle의 경우 실질적으로 구역을 어떻게 scale 하는지가 불분명함.


## **Reference**
