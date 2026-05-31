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
greater = np.where(x>y)
equal = np.where(x==y)
print(greater)
print(equal)













```
## Output













<img width="1094" height="368" alt="530709914-37dfe989-f7f2-4ff5-82b1-d989d49df90c" src="https://github.com/user-attachments/assets/4244cfde-1d5f-4f36-a492-e7b52e34b826" />


## Result
