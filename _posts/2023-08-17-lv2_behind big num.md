---
title: Programmers. Behind big num
author: YongJun Park
date: 2023.08.17 16:10:00 +0900
categories: [Programmers, lv2]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_2/behind_big_num.py)


## **뒤에 있는 큰 수 찾기**
- practice problem
- 정답률: 57% 
- 2023.08.17
- 16:10 ~ 17:15 (65 min)
- 후기: 처음에 dp로 방문했는지의 여부로 접근했지만, 이후 stack 개념으로 다시 접근함.



## **Code**
```python
def solution(numbers):
    answer = [-1] * len(numbers)
    stack = []

    for idx, number in enumerate(numbers):
        while stack and numbers[stack[-1]] < number:            
            answer[stack.pop()] = number

        stack.append(idx)
    return answer
```