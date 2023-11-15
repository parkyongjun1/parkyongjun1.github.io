---
title: Programmers. Making_hambur
author: YongJun Park
date: 2023.08.09 16:10:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/making_hambur.py)


## **햄버거 만들기**
- practice problem
- 정답률: 48% 
- 2023.08.09
- 16:10 ~ 17:00 (50 min)
- 후기: 초반에 while과 for문을 이용해 1231이 나오면 for문을 종료하고 while문을 만족할때까지 설계하여 시간초과가 나옴. 이후 for문 대신 단순 count라는 변수를 이용해 idx를 설정해서 해결함.

## **Code**
```python
def solution(ingredient):
    answer = 0
    count = 0
    while count < len(ingredient)-3:
        if ingredient[count:count+4] == [1,2,3,1]:
            answer +=1
            del ingredient[count:count+4]
            if count < 4:
                count = 0
            else:
                count -= 2
        else:
            count += 1      
    return answer
```