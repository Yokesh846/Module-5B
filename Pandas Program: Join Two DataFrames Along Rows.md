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
```
import pandas as pd
x=eval(input())
y=eval(input())
a1=pd.DataFrame(x)
a2=pd.DataFrame(y)
print("Original DataFrames:")
print(a1)
print("-------------------------------------")
print(a2,'\n')
result=pd.concat([a1,a2],axis=1)
print("Join the said two dataframes along columns:")
print(result)
```
## Output
<img width="750" height="432" alt="image" src="https://github.com/user-attachments/assets/a90a7088-10e8-465f-997c-089f1f0ebfdc" />

## Result
Thus the program was successfully executed.
