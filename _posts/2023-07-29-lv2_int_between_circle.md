---
title: Programmers. Int between circle and circle
author: YongJun Park
date: 2023.07.29 16:00:00 +0900
categories: [Programmers, lv2]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_2/int_between_circle.py)


## **두 원 사이의 정수 쌍**
- practice problem
- 정답률: 36% 
- 2023.07.29
- 16:00 ~ 15:20 (80 min)
- 후기: 처음에 접근을 원을 포함하는 사각형의 둘레로 접근을 했지만 문제점을 파악하고, 각 반지름을 빗변으로 가지는 정수로 접근해서 문제를 해결함.



## **Code**
```python
from math import sqrt, pow, ceil, floor
def solution(r1, r2):
    answer = 0
    total_point = 0
    max_y = 0
    min_y = 0
    
    for x in range(1,r2+1):
        max_y = floor(sqrt(pow(r2,2)-pow(x,2)))
        min_y = ceil(sqrt(pow(r1,2)-pow(x,2))) if x < r1 else 0
        
        total_point += max_y-min_y+1
       
    return total_point*4
```