---
title: Paper Review. SSD_Single Shot Multibox Detector@ECCV’ 2016
author: YongJun Park
date: 2021-06-23 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Object Detection, 1-stage]
math: true
pin: True
---

- [Paper link](https://arxiv.org/abs/1512.02325)


## **Introduction**
<img src="/assets/papers/SSD_Single Shot Multibox Detector/3.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/4.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/5.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/6.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/7.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/8.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/9.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/10.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/11.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/12.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/13.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/14.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/15.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/16.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/17.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/18.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/19.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/20.png" width='800'>

## **SSD**
<img src="/assets/papers/SSD_Single Shot Multibox Detector/21.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/23.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/24.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/25.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/26.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/27.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/28.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/29.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/30.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/31.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/32.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/33.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/34.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/35.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/36.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/37.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/38.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/39.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/40.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/41.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/42.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/43.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/44.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/45.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/46.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/47.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/48.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/49.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/50.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/51.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/52.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/53.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/54.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/55.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/56.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/57.png" width='800'>

## **Experiments**
<img src="/assets/papers/SSD_Single Shot Multibox Detector/59.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/60.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/61.png" width='800'>
<img src="/assets/papers/SSD_Single Shot Multibox Detector/62.png" width='800'>


## **Conclusions & Reviews**
- 기존 1 stage, 2 stage에서 trade-off 관계였던 속도와 성능에서 좋은 성과를 거둠.

- multi-scale feature maps을 통해 다양한 크기의 object를 검출해 성능을 올림.

- 1 stage detector로 속도 측면에서도 우수한 성과를 달성.

- 2D object detection의 개념을 하나하나 잡고 갈 수 있는 아주 좋은 기회였다고 생각했다. 


## **Reference**
- [1] SSD: https://yeomko.tistory.com/20
- [2] SSD: https://m.blog.naver.com/PostView.nhn?blogId=dr_moms&logNo=221656802353&proxyReferer=https:%2F%2Fwww.google.com%2F
- [3] SSD: https://herbwood.tistory.com/15
- [4] SSD: https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Object-Detection
- [5] NMS: https://ctkim.tistory.com/98
- [6] YOUTUBE: https://www.youtube.com/watch?v=ej1ISEoAK5g
