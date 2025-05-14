# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```

import pandas as pd
exam_data = {
    'name': ['Alice', 'Bob', 'Charlie', 'David', 'Emma'],
    'score': [85, 90, 78, 88, 76],
    'attempts': [1, 2, 3, 1, 2],
    'qualify': ['Yes', 'Yes', 'No', 'Yes', 'No']
}
labels = ['A', 'B', 'C', 'D', 'E']
df = pd.DataFrame(exam_data, index=labels)

print("Exam Data:")
print(df)

```

## Output
![Screenshot 2025-05-14 105942](https://github.com/user-attachments/assets/5de956c8-7af3-42d9-b558-dee32172a96f)

## Result
Therefore,the given program is verified
