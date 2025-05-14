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
array = np.array([[34, 11, 56],
                  [78, 23, 45],
                  [12, 89, 67]])
print("Original Array:")
print(array)
sorted_array = np.sort(array, axis=0)
print("\nColumn-wise Sorted Array:")
print(sorted_array)

```

## Output

![Screenshot 2025-05-14 103128](https://github.com/user-attachments/assets/7ddc598b-6aa6-4a62-a663-c80c861c70ad)


## Result
Therefore,The given python programm is successfully verified
