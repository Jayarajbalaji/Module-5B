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
x=np.array(eval(input()))
sorted=np.sort(x,axis=1)
print("Given array ")
print("",x,"\n")
print(sorted)
~~~
## Output
![439322848-fe2b0019-a533-4b1d-8e6b-1465ca52b498](https://github.com/user-attachments/assets/5192c83d-39dd-4ebd-a013-5c82baa81802)


## Result
The program successfully converts a 1-D array into a 2-D array with 3 rows and displays it.
