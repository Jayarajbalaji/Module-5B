# EX-5 NumPy Program: Column-wise Sorting of a 2D Array

##  Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

##  Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

##  Program
~~~
import numpy as np
l=eval(input())
print("The original array:")
arr=np.array(l)

print(f" {arr}")
print("\n3 x 3 Array:")
new=arr.reshape(3,3)
print(f" {new}")
~~~
## Output
![438749336-768e3cd3-b615-4bc5-b7d3-b0dedb26af6c](https://github.com/user-attachments/assets/4e27f069-9336-4e2f-b921-825f17d195d0)

## Result
The program successfully converts a 1-D array into a 2-D array with 3 rows and displays it.
