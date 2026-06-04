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
```
import numpy as np
x=eval(input())
y=eval(input())
arr1=np.array(x)
arr2=np.array(y)
print("Printing Original array")
print(arr1)
deleting=np.delete(arr1,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(deleting)
inserting=np.insert(deleting,1,arr2,axis=1)
print("Array after inserting column 2 on axis 1")
print(inserting)
```

## Output
<img width="753" height="488" alt="image" src="https://github.com/user-attachments/assets/ed536b69-51bc-472f-9981-c8b421e17a7a" />

## Result
Thus the program was successfully executed
