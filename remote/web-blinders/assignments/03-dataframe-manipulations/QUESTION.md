# Assignment 03 · Project Qualification Task 01 (DataFrame Manipulations)

## Objective

Perform various **DataFrame manipulations** and **column-wise operations** without relying on high-level pandas shortcuts such as `.apply()` or `.dt`.

The assignment focuses on building logic manually using Python, list comprehensions, mathematical transformations, and index manipulations.

---

## Dataset

Create the following DataFrame:

```python
import pandas as pd
import numpy as np

df = pd.DataFrame(
    np.random.randn(10, 4),
    index=pd.date_range("2021-07-18", periods=10),
    columns=["a", "b", "c", "d"]
)
```

---

## Tasks

### Task 1
Create a new column containing the logarithmic values of column **d**.

**Constraint:** Do not use `np.log()` directly on the entire Series.

---

### Task 2
Create another column where:

- Negative values remain unchanged.
- Positive values are replaced by their logarithm.

---

### Task 3
Create a new column from **column a** that returns:

- `"yes"` if the integer value is even.
- `"no"` otherwise.

---

### Task 4
Create a new column containing the DataFrame index values.

---

### Task 5
Split the date index into three separate columns:

- Year
- Month
- Day

Do this manually without using pandas datetime shortcuts.

---

### Task 6
Create a new column containing the weekday name corresponding to each index value.

**Constraint:** Do not use `.day_name()`.

---

## Expected Learning Outcomes

- DataFrame manipulation
- List comprehensions
- Conditional transformations
- Manual date parsing
- Index manipulation
- Basic pandas programming