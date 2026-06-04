# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

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
```
import numpy as np
l1=eval(input())
l2=eval(input())
x=np.array(l1)
y=np.array(l2)
print(np.where(x>y))
print(np.where(x == y))
```
## Output
<img width="846" height="179" alt="image" src="https://github.com/user-attachments/assets/e53f089f-b990-4bed-a9bc-d31f39292953" />

## Result
Thus the program was successfully executed.
