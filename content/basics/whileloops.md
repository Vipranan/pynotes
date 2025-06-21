---
title: Whileloops
date: 2025-06-21
author: Your Name
cell_count: 4
score: 0
---

```python
count = 1
while count <= 5:
    print("Count is:", count)
    count += 1
```

    Count is: 1
    Count is: 2
    Count is: 3
    Count is: 4
    Count is: 5
    


```python
number = 1
total = 0

while number <= 50:
    if number % 2 != 0:
        number += 1
        continue  # skip odd numbers
    total += number
    number += 1

print("Sum of even numbers from 1 to 50 is:", total)

```

    Sum of even numbers from 1 to 50 is: 650
    


```python
number = 1
total = 0
while number <= 20:
    if number % 2 != 0:
        number +=1
        continue
    total += number
    number += 1
print("sum of the even number from 1 to 50 i,", total)
```

    sum of the even number from 1 to 50 i, 110
    


```python

```


---
**Score: 0**