---
title: Programmers. Small_substring
author: YongJun Park
date: 2023.02.15 14:30:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/small_substring.py)


## **크기가 작은 부분문자열**
- practice problem
- 정답률: 64% 
- 2023.02.15
- 14:30 ~ 14:45 (15 min)
- 후기: 문제를 이해하고 어렵지 않게 해결 할 수 있었음. 


## **Code**
```python
def solution(t, p):
    answer = 0
    check_num = 0
    check_cnt = 0
    for  i in range(len(t)):
        check_len = len(p)
        if i+check_len > len(t):
            pass
        else:
            check_num = int(t[i:i+check_len])
            if check_num <= int(p):
                check_cnt += 1
                answer = check_cnt
                
        
    return answer
```