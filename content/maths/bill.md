---
title: Bill
date: 2026-01-08
author: Your Name
cell_count: 2
score: 0
---

```python
print("Welcome to the Tip Calculator!")
bill = float(input("What was the total bill? $"))   
tip = int(input("What percentage tip would you like to give? 10, 12, or 15? "))
people = int(input("How many people to split the bill? "))  

tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)
print(f"Each person should pay: ${final_amount}")
```

    Welcome to the Tip Calculator!


    What was the total bill? $ 100
    What percentage tip would you like to give? 10, 12, or 15?  10
    How many people to split the bill?  5


    Each person should pay: $22.0



```python

```


---
**Score: 0**