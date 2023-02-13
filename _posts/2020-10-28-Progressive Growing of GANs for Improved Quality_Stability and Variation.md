---
title: Paper Review. Progressive Growing of GANs for Improved Quality, Stability, and Variation@arXiv’ 2018
author: YongJun Park
date: 2020-10-28 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [GAN, Image Generation]
math: true
pin: True
---

- [Paper link](https://arxiv.org/abs/1710.10196)


## **Introduction**
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/4.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/5.png" width='800'>

## **Pregressive Growing of GANs**
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/7.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/8.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/9.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/10.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/11.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/12.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/13.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/14.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/15.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/16.png" width='800'>

## **Normalization in generator and discriminator**
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/18.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/19.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/20.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/21.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/22.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/23.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/24.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/25.png" width='800'>

## **Experiments**
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/27.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/28.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/29.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/30.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/31.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/32.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/33.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/34.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/35.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/36.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/37.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/38.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/39.png" width='800'>
<img src="/assets/papers/Progressive Growing of GANs for Improved Quality_Stability and Variation/40.png" width='800'>


## **Conclusions & Reviews**
- 낮은 해상도에서부터 점차 고해상도를 학습시킴으로써 훈련 속도를 높이고, 안정화하였음.

- CELEBA 에서 이전과 비교해 매우 좋은 이미지를 생성해 냄.

- CIFAR10 에서 8.80 이라는 점수를 달성함.

- GAN 결과를 평가하기위한 새로운 평가 지표를 제시함.

- 학교과제에 적용하는 Style Gan 을 공부하기 전 base 가 되는 PGGan 을 학습하였는데, 모델 구조는 단순하지만 그 안에 적용한 내용들이 다소 어려웠다.

- 각각의 내용들을 이해하는데 시간이 조금 많이 걸리긴 했지만 나중에 Style Gan을 공부할 때 도움이 많이 될거 같다.


## **Reference**
- [1] Improved Techniques for Training GANs@arXiv 2016
- [2] 참고 블로그 : https://qiita.com/Phoeboooo/items/ea0e44733e2d2240879b
- [3] Sliced Wasserstein distance: https://arxiv.org/pdf/1902.00434.pdf