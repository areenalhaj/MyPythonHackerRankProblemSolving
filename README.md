# MyPythonHackerRankProblemSolving

# Problem 1:
URL: https://www.hackerrank.com/challenges/finding-the-percentage/problem?isFullScreen=true

## Solution:
```python
def aver(marks):
    summ = 0
    num = len(marks)
    for mark in marks:
        summ += mark
    return (summ/num)

def check_mark(mark):
    if mark>=0 and mark<=100:
        return True
    else:
        return False
    
if __name__ == '__main__':
    retry=True
    while (retry):
        n = int(input())
        if n>=2 and n<=10:
            retry=False
    student_marks = {}
    for _ in range(n):
        name, *line = input().split()
        if len(line)==3:
            scores = list(map(float, line))
            retry=True
            while(retry):
                marks_status = list(map(check_mark, scores))
                for res in marks_status:
                    if res == False:
                        pass
                    else:
                        retry = False
            student_marks[name] = scores
        else:
            print("false input, try again")
            n+=1
    query_name = input()
    marks = student_marks[query_name]
    print(f"{aver(marks):.2f}")
```
---
# Problem 2
URL: 
## Solution:
```python
```
