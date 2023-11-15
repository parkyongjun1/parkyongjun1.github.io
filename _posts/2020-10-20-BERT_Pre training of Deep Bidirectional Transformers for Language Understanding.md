---
title: Paper Review. BERT_Pretraining of Deep Bidirectional Transformers for Language Understanding@NAACL' 2019
author: YongJun Park
date: 2020-10-20 18:00:00 +0900
categories: [Paper Reviews, NLP]
tags: [Pretrain, Transformer]
math: true
pin: False
---

- [Paper link](https://aclanthology.org/N19-1423.pdf)


## **Abstract**
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/4.png" alt='' width='800'>

## **Background**
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/6.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/7.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/8.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/9.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/10.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/11.png" alt='' width='800'>

## **BERT**
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/13.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/14.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/15.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/16.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/17.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/18.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/19.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/20.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/21.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/22.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/23.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/24.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/25.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/26.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/27.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/28.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/29.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/30.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/31.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/32.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/33.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/34.png" alt='' width='800'>

## **Experiments**
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/36.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/37.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/38.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/39.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/40.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/41.png" alt='' width='800'>
<img src="/assets/papers/BERT_Pretraining_of_Deep_Bidirectional_Transformers_for_Language_Understanding/42.png" alt='' width='800'>


## **Conclusions & Reviews**
- bidirectional 구조를 일반화시켜 Pre training 된 모델이 광범위한 NLP 작업을 성공적으로 처리할 수 있도록 기여함.

- Fine tuning 을 위해 단순하게 bert 의 마지막 단에 한 개의 레이어를 추가해서 downstream task 를 수행한다는 점이 놀라웠다.

- 모델을 복잡하게 만들어서 성능을 올릴 수도 있지만 반대로 단순하게 접근해서 강력한 성능을 낼 수 있었다는 점이 매우 흥미로웠다.


## **Reference**

