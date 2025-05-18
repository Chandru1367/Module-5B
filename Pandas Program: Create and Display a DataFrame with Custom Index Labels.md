# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```python
import pandas as pd 
import numpy as np
exam_data  = eval(input())
labels = eval(input())
df = pd.DataFrame(exam_data,labels )
print(df)
```

## Output


![image](https://github.com/user-attachments/assets/0d72fbfe-2f90-4766-9165-8aa3a3fe7256)


## Result

Thus, the program has been successfully executed.
