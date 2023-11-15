---
title: Programmers. Hall of honor1
author: YongJun Park
date: 2023.08.14 16:00:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/hall_of_honor1.py)


## **명예의전당1**
- practice problem
- 정답률: 64% 
- 2023.08.14
- 16:00 ~ 16:20 (20 min)
- 후기: deque를 이용해 popleft를 사용하여 쉽게 문제를 해결.

## **Code**
```python
from collections import deque

def solution(k, score):
    answer = []
    rank_len = []
    rank_list = deque()
    min_check = 0
    
    for i in range(k):
        rank_len.append(0)
        
    for idx, i in enumerate(score):
        if idx < len(rank_len):
            rank_list.append(i)
            answer.append(min(rank_list))
        else:
            min_check = min(rank_list)
            if i > min_check:
                rank_list.remove(min_check)
                rank_list.append(i)
                
                answer.append(min(rank_list))
            else:
                answer.append(min(rank_list))
    
    return answer
```