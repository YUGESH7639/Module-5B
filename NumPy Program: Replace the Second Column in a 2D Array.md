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
array = np.array([[10, 20, 30], 
                  [40, 50, 60], 
                  [70, 80, 90]])
new_column = np.array([100, 200, 300])
modified_array = np.delete(array, 1, axis=1)
updated_array = np.insert(modified_array, 1, new_column, axis=1)
print("Original Array:")
print(array)
print("\nArray after replacing the second column:")
print(updated_array)


```

## Output
![Screenshot 2025-05-14 104232](https://github.com/user-attachments/assets/b21d01bc-ca7d-4590-a7d2-8f8a8a34ccf1)

## Result
Therefore,the given python programm is sucessfully verified
