# 문자열 내 p와 y의 개수

```python
def solution(s):
    p = 0
    y = 0
    answer = True
    for i in s:
        if i == 'p' or i == 'P':
            p +=1
        elif i == 'y' or i == 'Y':
            y +=1
    if p == y:
        answer = True
    else:
        answer = False
    return answer
```

신기해요