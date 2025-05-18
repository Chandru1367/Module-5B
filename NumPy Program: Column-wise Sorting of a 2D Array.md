# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```python
import numpy as np
a=eval(input())
b=np.array(a)
print(f"Given array\n {b}\n")
print(np.sort(b))
```

## Output


![image](https://github.com/user-attachments/assets/05202dcc-b3d8-402c-bd71-f311fedc48e8)


## Result

Thus, the program has been successfully executed.
