# NumPy Program: Replace the Second Column in a 2D Array

##  Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## Program
~~~
import pandas as pd
a=eval(input())
b=eval(input())
print("Division of Series1 by Series2:")
a1=pd.Series(a)
a2=pd.Series(b)
print(a1/a2)
~~~
## Output

![438752233-50afc751-d0a5-43dd-bcd9-be3b384da38d](https://github.com/user-attachments/assets/36f2d47d-92d0-4dac-9eae-02165997259f)

## Result
The program correctly performs element-wise division of the two series and displays the floating-point results.
