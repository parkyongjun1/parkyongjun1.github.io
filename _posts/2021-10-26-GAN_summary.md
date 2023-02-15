---
title: Project. GAN Summary
author: YongJun Park
date: 2021-10-26 18:00:00 +0900
categories: [Project, School]
tags: [GAN, Recycle, Tonify, Age Transformation]
math: true
pin: True
---


## **Tonify**
- pSp(pixel2Style2pixel) Encoder를 통해 StyleGAN Generator의 Style wieght에 대한 vector를 넣어줌. 
- 기존 Random Sampled Latent는 Layer 상단(고해상도)로 사용하고, pSp Encoder를 통해 나온 weight vector는 Layer 하단(저해상도)에 사용.
- Img translation GAN 연구의 흐름은 결국 vector space에서 이미 학습되어진 vector들과 새로 주어진 vector(ex: cartoon)들을 서로 매칭시켜주고, Unified Vector Space를 어떻게 형성할 것인지에 대한 Domain Adaptation 연구가 중요함.

### **Tonify dataset**
- Anim. img 1024x1024 317장
<img src="/assets/projects/GAN_sum/1.png" width='800'>


### **Tonify results**
- paper results
<img src="/assets/projects/GAN_sum/2.png" width='800'>


- implemental results
<img src="/assets/projects/GAN_sum/3.png" width='800'>
<img src="/assets/projects/GAN_sum/4.png" width='800'>
<img src="/assets/projects/GAN_sum/5.png" width='800'>


### **RecyclePS results**
- 재반복 학습을 통해 output의 quality를 높임.
<img src="/assets/projects/GAN_sum/6.png" width='800'>


- Animation이 아닌 중세시대 dataset인 metdata를 다운받아 모델을 학습시킨 결과
<img src="/assets/projects/GAN_sum/7.png" width='800'>

### **SAM results**
- Age Transformation 모델인 SAM을 구현해본 결과.
<img src="/assets/projects/GAN_sum/8.png" width='800'>
<img src="/assets/projects/GAN_sum/9.png" width='800'>
<img src="/assets/projects/GAN_sum/10.png" width='800'>
<img src="/assets/projects/GAN_sum/11.png" width='800'>


## **Limitations**
- 기존 style GAN은 FFHQ 등 고해상도(1024X1024) Img로 pretrain되었기 때문에 translation하고자 하는 target dataset이 어느정도 실제 사람과 유사해야지만 quality가 높다는 문제가 존재.

- 예를 들어 이말년 webtoon과 같이 웹툰 상 사람의 형태가 실제 사람과 차이가 있는 경우 학습의 어려움이 존재.

- 이것은 결국 pretrain된 vector space와 학습하고자 하는 dataset의 vector space가 다르기 때문에 생기는 문제.

- 현재까지는 이말년 style의 target으로 translation하고자 한다면 이말년 학습 dataset내에 존재하는 어떤 vector로의 매핑까지는 가능하지만 실질적으로 Unified vector Space에 완벽하게 존재한다고 보기에는 어려움.

- 이말년 데이터셋으로 학습한다면 결과 img는 이말년 데이터셋 내에 존재하는 어떤 img가 그대로 나올 가능성이 높음.(단순 매핑, 새롭게 생성된 img X)

- Sketch pair dataset과 같이 명시적으로 source와 target이 주어진 데이터의 경우 model이 어떻게 unified vector space를 형성할지 방향성을 알지만, pair data가 아닌 경우 model이 어떻게 unified vector space를 구성할지 어려움을 느낄 것이라 생각됨.

- Img Translation Source와 Target의 domain Adaptation 연구는 결국 Language, Vision, Signal 간의 Domatin Adaptation 연구와도 결이 비슷하기 때문에(결국 한 vector space에 정보가 통합될 수 있는 관점으로 본다면) Domain Adaptation 연구 발전이 Img Translation은 물론 모든 분야의 Unified Multi Model로 이어질 수 있다고 판단함. 