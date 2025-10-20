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
student_data1 = pd.DataFrame(eval(input()))
student_data2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
#Add your code here
print(student_data1)
print("-------------------------------------")
print(student_data2)
print()
print("Join the said two dataframes along rows:")
result_data=pd.concat([student_data1,student_data2],ignore_index=False)
print(result_data)
```


## Output

<img width="1154" height="418" alt="Screenshot 2025-10-20 190615" src="https://github.com/user-attachments/assets/0d8a3d66-2307-4584-9bfb-59192bd2cd2f" />



## Result
Thus,the python program has been executed successfully
