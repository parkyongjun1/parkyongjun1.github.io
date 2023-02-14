---
title: Paper Review. RDrop_Regularized Dropout for Neural Networks@NeurIPS’ 2021
author: YongJun Park
date: 2021-11-30 18:00:00 +0900
categories: [Paper Reviews, NLP]
tags: [Regularization, Transformer, CV]
math: true
pin: True
---

- [Paper link](https://proceedings.neurips.cc/paper/2021/hash/5a66b9200f29ac3fa0ae244cc2a51b39-Abstract.html)


## **Introduction**
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/3.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/4.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/5.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/6.png" width='800'>

## **Model**
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/8.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/9.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/10.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/11.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/12.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/13.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/14.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/15.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/16.png" width='800'>

## **Experiments**
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/18.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/19.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/20.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/21.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/22.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/23.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/24.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/25.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/26.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/27.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/28.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/29.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/30.png" width='800'>
<img src="/assets/papers/RDrop_Regularized Dropout for Neural Networks/31.png" width='800'>


## **Conclusions & Reviews**
- 모델의 일반화 능력 향상을 위해 Dropout 기법을 확장한 R-Drop 방법을 제안함.

- 제안한 방법은 Over-fitting을 막아주면서, 일반화를 달성함.

- 생각보다 간단한 논문이지만, Training과 Inference 단계에서의 Dropout의 문제점을 잘 해결한 것 같음.

- Dropout 비율을 0.5나 했음에도 불구하고, baseline과 비교할만한 성능이 나오는 것을 통해, 일반화 능력을 달성하지 않았나라는 생각이 듦.


## **Reference**
