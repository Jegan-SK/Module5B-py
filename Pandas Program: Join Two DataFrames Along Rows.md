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

    import pandas as pd
    student_data1 = {
        'name': ['Arun', 'Bala', 'Chitra'],
        'marks': [85, 78, 92]
    }
    df1 = pd.DataFrame(student_data1)
    student_data2 = {
        'name': ['Deepak', 'Esha'],
        'marks': [88, 76]
    }
    df2 = pd.DataFrame(student_data2)
    combined_df = pd.concat([df1, df2], axis=0)
    print("Combined DataFrame\n",combined_df)
    
## Output

<img width="1247" height="169" alt="image" src="https://github.com/user-attachments/assets/6a747e0a-570a-462c-b65a-1d6bb9204aed" />

## Result

Thus the python program using pandas to join two dataframes along rows , is written and executed successfully.
