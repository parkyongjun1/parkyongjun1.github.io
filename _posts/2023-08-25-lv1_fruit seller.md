---
title: Programmers. Fruit seller
author: YongJun Park
date: 2023.08.25 15:40:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/fruit_seller.py)


## **과일 장수**
- practice problem
- 정답률: 62% 
- 2023.08.25
- 15:40 ~ 15:50 (10 min)
- 후기: sort를 이용해 정렬 후 m에 맞게 나눠서 쉽게 문제를 해결.

## **Code**
```python
def solution(k, m, score):
    score.sort(reverse=True)
    box_price = 0
    total_price = 0
    
    for idx,i in enumerate(score, start = 1):
        if idx%m == 0:
            box_price = i*m
            total_price += box_price
    
    return total_price
```