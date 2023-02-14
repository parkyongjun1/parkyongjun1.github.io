---
title: Paper Review. Training data-efficient image transformers & distillation through attention@ICML’ 2021
author: YongJun Park
date: 2021-08-18 18:00:00 +0900
categories: [Paper Reviews, CV]
tags: [Pretrain, Image Classification, Transformer, Knowledge Distillation, Teacher, Student]
math: true
pin: True
---

- [Paper link](https://icml.cc/virtual/2021/poster/8671)


## **Introduction**
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/2.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/3.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/4.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/5.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/6.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/7.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/8.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/9.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/10.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/11.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/12.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/13.png" width='800'>

## **DeiT**
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/15.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/16.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/17.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/18.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/19.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/20.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/21.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/22.png" width='800'>

## **Experiments**
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/24.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/25.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/26.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/27.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/28.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/29.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/30.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/31.png" width='800'>
<img src="/assets/papers/Training data_efficient image transformers and distillation through attention/32.png" width='800'>


## **Conclusions & Reviews**
- Image Classification에서 비교적 적은 데이터 셋으로도 성능을 끌어 올릴 수 있는 distillation token을 제안함.

- DeiT에서 제안한 distillation 방법이 Teacher가 CNN일때 inductive bias를 어느정도 학습해 성능을 더 끌어 올릴 수 있다는 것을 보여줌.

- ImageNet에서 pretrain된 모델이 다른 데이터 셋 task에서도 좋은 성능을 도출함.

- transformer를 image classification에서 비교적 가볍게 pretrain 가능하다는 것이 놀라웠다.

- Knowledge Distillation 기법을 transformer안에 단순히 하나의 토큰으로 녹여낸 점이 인상적이었다.

- Transformer를 실용적 pretrain 하기 위해서는 Knowledge Distillation 기법이 핵심적인 역할을 하기때문에 앞으로 CV에서 Transformer에 KD를 효율적이게 사용할 수 있게 하는 연구가 활발해질 것 같다는 느낌을 받았다.


## **Reference**
