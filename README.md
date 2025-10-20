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
x = np.array(eval(input()))
y = np.array(eval(input()))
great=np.where(x>y)
equal=np.where(x==y)
print(great)
print(equal)
```
## Output

<img width="1326" height="254" alt="Screenshot 2025-10-20 150429" src="https://github.com/user-attachments/assets/d0b96a43-e260-4475-8146-185259133993" />



## Result
Thus,the python program has been executed successfully



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
original=np.array(eval(input()))
newone=np.array(eval(input()))
print("Printing Original array")
print(original)
modified=np.delete(original,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(modified)
result=np.insert(modified,1,newone,axis=1)
print("Array after inserting column 2 on axis 1")
print(result)
```

## Output

<img width="1306" height="411" alt="Screenshot 2025-10-20 151305" src="https://github.com/user-attachments/assets/8c16f9bd-81f7-48fb-aa11-8596f81abfb3" />



## Result
Thus,the python program has been executed successfully
