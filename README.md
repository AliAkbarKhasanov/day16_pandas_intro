# 📊 Pandas Intro (Day 16)

First steps with **Pandas**, the Python library for data analysis.  
Learned how to create tables and filter rows.

---

## 📌 Features
- Create a DataFrame from a dictionary
- Select specific column
- Filter rows with conditions

---

## ▶️ Example run
```python
import pandas as pd

data = {
    "Name": ["Ali", "Sara", "Omar"],
    "Age": [24, 22, 27],
    "City": ["Munich", "Berlin", "Hamburg"]
}

df = pd.DataFrame(data)
print(df)
print(df[df["Age"] > 23])
📊 Example output
pgsql
Copy code
   Name  Age     City
0   Ali   24   Munich
1  Sara   22   Berlin
2  Omar   27  Hamburg

   Name  Age     City
0   Ali   24   Munich
2  Omar   27  Hamburg
✨ This project is part of my Python learning journey (Day 16).
