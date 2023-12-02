---
title: Programmers. Min_dist Map
author: YongJun Park
date: 2023.12.02 13:30:00 +0900
categories: [Programmers, lv2]
tags: [Algorithm]
math: true
pin: False
---

- [Code link](https://github.com/parkyongjun1/programmers_algorithm/blob/main/level_2/mindist_map.py)


## **게임 맵 최단거리**
- DFS/BFS
- 정답률: 58% 
- 2023.12.02
- 13:30 ~ 14:30 (60 min)
- 후기: 최단거리 계산을 위해 BFS를 이용해 문제를 해결함.

## **Code**
```python
from collections import deque
DIR = ((1,0),(-1,0),(0,1),(0,-1))
INF = float('inf')

def solution(maps):
    answer = []

    row = len(maps)
    col = len(maps[0])
    
    start_pt, end_pt = [0,0], [row-1,col-1]
    
    start_r, start_c = start_pt
    end_r, end_c = end_pt
    
    
    chk_end = [[INF]*col for _ in range(row)]
    chk_end[start_r][start_c] = 1
    
    dq =deque([[start_r,start_c,chk_end[start_r][start_c]]])
    
    while dq:
        if chk_end[end_r][end_c] != INF:
            return chk_end[end_r][end_c]
        
        curr_r, curr_c, curr_chk = dq.popleft()
        
        for dir_r, dir_c in DIR:
            post_r, post_c, post_chk = curr_r, curr_c, curr_chk
        
            if 0<=post_r+dir_r<row and 0<=post_c+dir_c<col and maps[post_r+dir_r][post_c+dir_c] == 1:
                post_r, post_c,post_chk = post_r+dir_r, post_c+dir_c,curr_chk+1
                chk_end
                if post_chk < chk_end[post_r][post_c]:
                    chk_end[post_r][post_c] = post_chk
                    dq.append([post_r,post_c,post_chk])            
            
    return -1
```