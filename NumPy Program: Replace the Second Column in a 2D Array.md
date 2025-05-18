# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```python
import numpy as np
array=np.array(eval(input()))
new_col=np.array(eval(input()))
print("Printing Original array")
print(array)
array=np.delete(array,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(array)
array=np.insert(array,1,new_col,axis=1)
print("Array after inserting column 2 on axis 1")
print(array)
```

## Output


![image](https://github.com/user-attachments/assets/ecdfc670-6278-4b23-b060-c9a01462c0af)



## Result

Thus, the program has been successfully executed.
