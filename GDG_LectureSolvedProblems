# HackerRank Python Tasks

This repository contains solutions to selected HackerRank Python challenges. Each problem's solution is provided along with its corresponding link.

## Task 1: String Split and Join

**Problem Link:** [Python String Split and Join](https://www.hackerrank.com/challenges/python-string-split-and-join/problem?isFullScreen=true)

### Solution:

```python
def split_and_join(line):
    return "-".join(line.split())

if __name__ == "__main__":
    line = input()
    result = split_and_join(line)
    print(result)
```

---

## Task 2: Find the Second Maximum Number

**Problem Link:** [Find the Second Maximum Number in a List](https://www.hackerrank.com/challenges/find-second-maximum-number-in-a-list/problem?isFullScreen=true)

### Solution:

```python
def second_maximum(arr):
    unique_numbers = sorted(set(arr), reverse=True)
    return unique_numbers[1]

if __name__ == "__main__":
    n = int(input())
    arr = list(map(int, input().split()))
    print(second_maximum(arr))
```

---

## Task 3: Nested Lists

**Problem Link:** [Nested Lists](https://www.hackerrank.com/challenges/nested-list/problem?isFullScreen=true)

### Solution:

```python
def second_lowest(students):
    scores = []
    for student in students:
        scores.append(student[1])
    
    unique_scores = sorted(set(scores))
    second_lowest_score = unique_scores[1]
    
    second_lowest_students = []
    for student in students:
        if student[1] == second_lowest_score:
            second_lowest_students.append(student[0])
    
    for name in sorted(second_lowest_students):
        print(name)

if __name__ == "__main__":
    students = []
    for _ in range(int(input())):
        name = input()
        score = float(input())
        students.append([name, score])
    
    second_lowest(students)
```
