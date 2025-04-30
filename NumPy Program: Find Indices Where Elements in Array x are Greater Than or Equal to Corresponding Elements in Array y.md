# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

##  Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

##  Program
~~~
import numpy as np
a=list(map(int,input().split()))
arr=np.array(a)
new=arr.reshape((3,3))
print(new)
~~~
## Output
![438750455-c4931f77-d694-4eaf-a1ef-0a03813add20](https://github.com/user-attachments/assets/9051f0cd-4a03-42b0-8292-197765653422)

## Result
The program successfully takes a list of 9 integers and converts it into a 3×3 NumPy array.
