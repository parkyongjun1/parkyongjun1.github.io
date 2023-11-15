---
title: Programmers. Foodfight game
author: YongJun Park
date: 2023.08.28 14:00:00 +0900
categories: [Programmers, lv1]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_1/foodfight_game.py)


## **푸드파이터 대회**
- practice problem
- 정답률: 68% 
- 2023.08.28
- 14:00 ~ 14:15 (15 min)
- 후기: 몫을 이용하여 개를 구하고 reverse를 이용해 두 문자열을 합침.

## **Code**
```python
def solution(food):
    answer = ''
    food_num = 0
    food_list = []
    food_list_reverse = []
    for idx, i in enumerate(food):
        if food[idx] == 1:
            pass
        else:
            food_num = food[idx] // 2
            for j in range(food_num):
                food_list.append(idx)
    for i in reversed(food_list):
        food_list_reverse.append(i)
    food_list.append(0)
    food_list = food_list + food_list_reverse
    for i in food_list:
        answer += str(i)
    
    return answer
```