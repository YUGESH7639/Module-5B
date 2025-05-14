# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```

import pandas as pd
student_data1 = {
    'name': ['Alice', 'Bob'],
    'age': [20, 21],
    'score': [85, 90]
}
df1 = pd.DataFrame(student_data1)
student_data2 = {
    'name': ['Charlie', 'David'],
    'age': [22, 23],
    'score': [78, 88]
}
df2 = pd.DataFrame(student_data2)
new_df = pd.concat([df1, df2], axis=0)
print("Combined DataFrame:")
print(new_df)


```

## Output
![Screenshot 2025-05-14 110934](https://github.com/user-attachments/assets/17122242-b9d6-4f26-89fc-8dabeead318b)

## Result
Therefore,the given program is verified
