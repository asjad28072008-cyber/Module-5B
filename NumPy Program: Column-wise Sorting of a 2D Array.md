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
```
#Complete the following code
import numpy as np
array = np.array(eval(input()))
print('Given array','\n',array)
print()
print(np.sort(array,axis=0))
```


## Output

<img width="871" height="577" alt="Screenshot 2025-10-20 145435" src="https://github.com/user-attachments/assets/3b8dd58e-5485-451e-bfb3-64af4ae67f8c" />


## Result
Thus,the python program has been executed successfully
