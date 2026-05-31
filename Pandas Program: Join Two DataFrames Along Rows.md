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
d1=eval(input())
d2=eval(input())
df1=pd.DataFrame(d1)
df2=pd.DataFrame(d2)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
jd=pd.concat([df1,df2])
print("\nJoin the said two dataframes along rows:")
print(jd)










```

## Output

















<img width="909" height="373" alt="530710323-cb84a501-a65d-4052-9663-b274468fccf0" src="https://github.com/user-attachments/assets/07fb2031-d302-42e1-a524-55ff4bc71ea3" />


## Result
