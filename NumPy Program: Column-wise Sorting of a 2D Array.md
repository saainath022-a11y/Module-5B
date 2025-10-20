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
Add code here
import numpy as np
array=np.array(eval(input()))
print("og array\n",array)
print("sorted array\n",np.sort(array,axis=0))
## Output
<img width="470" height="318" alt="mod 5 1" src="https://github.com/user-attachments/assets/7e295d1e-7a93-4f91-9b48-40409b5b1ace" />

## Result
Successfully wrote a NumPy program that sorts the elements in each column of a given 2D array in ascending order.

