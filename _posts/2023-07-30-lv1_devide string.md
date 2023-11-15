---
title: Programmers. Devide string
author: YongJun Park
date: 2023.07.30 13:00:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/devide_string.py)


## **문자열 나누기**
- practice problem
- 정답률: 53% 
- 2023.07.30
- 13:00 ~ 14:00 (60 min)
- 후기: 처음에 문제 자체를 이해하는데 다소 시간이 오래걸렸다. 문제를 이해하고 나서는 금방 해결했다.

## **Code**
```python
def solution(s):
    answer = 0
    cnt1=0; cnt2=0
    for i in s:
        if cnt1==cnt2:
            answer+=1
            k=i
        if k==i:
            cnt1+=1
            
        else:
            cnt2+=1
        
    return answer
```