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

# NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```python
import numpy as np

x = np.array(eval(input()))
y = np.array(eval(input())) 

great = np.where(x > y)     
equal = np.where(x == y)    

print(great)                 
print(equal)               
```

## Output


![image](https://github.com/user-attachments/assets/99bdf25c-2d37-4427-8313-79c48c9a88dc)


## Result

Thus, the program has been successfully executed.

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

# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```python
import pandas as pd
data1 = pd.DataFrame(eval(input()))
data2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(data1)
print("-------------------------------------")
print(data2)
result=pd.concat([data1,data2])
print("\nJoin the said two dataframes along rows:")
print(result)
```

## Output


![image](https://github.com/user-attachments/assets/c5ef6478-8a8d-48de-a816-77a10404be8d)


## Result

Thus, the program has been successfully executed.
