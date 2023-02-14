---
title: Paper Review. End-to-End Object Detection with Transformers@ECCV’2020
author: YongJun Park
date: 2021-10-12 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Object Detection, Transformer, 1 stage]
math: true
pin: True
---

- [Paper link](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460205.pdf)


## **Introduction**
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/4.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/5.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/6.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/7.png" width='800'>

## **DETR**
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/9.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/10.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/11.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/12.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/13.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/14.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/15.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/16.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/17.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/18.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/19.png" width='800'>

## **Experiments**
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/22.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/23.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/24.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/25.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/26.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/27.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/28.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/29.png" width='800'>
<img src="/assets/papers/EndtoEnd Object Detection with Transformers/30.png" width='800'>


## **Conclusions & Reviews**
- 기존 object detection의 Anchor generation과 NMS를 제거한 end-to-end 파이프라인을 제안함

- transforme를 set prediction과 이분매칭을 통해 효과적으로 성능을 끌어올림

- Anchor를 생성하지 않는 점과 NMS를 사용하지 않고 object detection을 수행한다는 점이 놀라웠음

 - training time이 길다는 점과 small object에 대해서 성능이 낮다는 점이 다소 아쉬웠음


## **Reference**
