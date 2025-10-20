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
```

import pandas as pd


data = eval(input())
Col=eval(input())


qrtsales = pd.DataFrame(data,columns=Col)


print (qrtsales)

qs=qrtsales.groupby('itemcat')
print('Result after Filtering Dataframe') 
print(qs['expenditure'].sum())
```

## Output

<img width="1136" height="206" alt="Screenshot 2025-10-20 185811" src="https://github.com/user-attachments/assets/8d292885-1c9f-4682-9008-7f484b29a274" />


## Result
Thus,the python program has been executed successfully
