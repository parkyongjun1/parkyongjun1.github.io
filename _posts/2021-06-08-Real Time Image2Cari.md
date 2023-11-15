---
title: Project. Real Time Image2Cari
author: YongJun Park
date: 2021-06-08 18:00:00 +0900
categories: [Project, School]
tags: [GAN, Real-time, Caricature]
math: true
pin: True
---

- [Code link](https://github.com/parkyongjun1/img2cari)


## **Real-time Image2Cari**
- CariGAN과 Style Transfer 모델을 활용하여 Real-time Style and Caricature Transfer가 가능한 모델 설계.

## **Caricature**
- CariGAN에서 기본 제공하는 Caricatures 외 다양한 Caricatures을 수집.

<img src="/assets/projects/CV_term_project/3.png" width='800'>


## **Model**
- Model은 크게 face detection, Caricature Retrieval, Shape Transformation, Style Transfer로 구분되어짐.
- (1) MTCNN을 통해 User의 Face를 detection.
- (2) Caricature Dataset을 가지고 Caricature Retrieval을 수행.
- (3) (1)에서 detection한 영역을 통해 Face Parsing을 수행.
- (4) (2)의 Retrieval 결과 Mask와 (3)의 결과 Mask를 통해 Shape을 맞춰주는 Shape Transformation Network를 통과.
- (5) 사용자 얼굴에 Caricature된 shape을 가지는 (4)의 결과에 Style transfer를 수행.
- (6) 최종적으로 Input img에 대해 Caricature shape을 가지고, Style img의 textual를 담고 있는 Output img 생성.

<img src="/assets/projects/CV_term_project/4.png" width='800'>

## **Shape Transformation**
<img src="/assets/projects/CV_term_project/5.png" width='800'>

## **Style Transfer**
<img src="/assets/projects/CV_term_project/6.png" width='800'>


## **Result**
- Entire input
<iframe width="800" height="500" src="/assets/video/img2cari.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Only Face input
<iframe width="800" height="500" src="/assets/video/img2cari_face.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## **Limitations**
- 웹캠을 통한 실시간 Shape Transformation을 수행할 때 카메라의 각도와 거리, 그리고 User(input)의 움직임으로 인해 완벽하게는 Caricature의 Shape이 나오지 않는 문제점이 발생.
- 이로 인한 output Cari Shape Quality는 다소 떨어짐.
- 실시간 움직임에 강건한 Shape Transformation 기법을 적용할 필요가 있음.