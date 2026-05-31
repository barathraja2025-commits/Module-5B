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




import numpy as np
a=eval(input())
array = np.array(a)
print('Given array','\n',array)
print()
print(np.sort(array,axis=0))


```

## Output












<img width="914" height="682" alt="530709764-30ca9505-89be-400e-986d-0bcd344a4886" src="https://github.com/user-attachments/assets/4eac2e19-3e6b-4b93-8c8e-ad1dec5e3ddc" />

## Result
