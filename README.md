# 🐼 Pandas Dummy Dataset and Commands  

This project demonstrates how to work with **Pandas**, a powerful Python library for data analysis and manipulation.  
It includes a **dummy dataset** and examples of **essential Pandas commands** used for cleaning, transforming, and analyzing data.  

---

## 📂 Project Overview  

In this repository, you will learn how to:  
- Create and load a **dummy dataset** using `pandas.DataFrame()`  
- Perform **data cleaning** (handling missing values, duplicates)  
- Use **filtering and selection** techniques  
- Apply **groupby()**, **mean()**, **sum()**, **sort_values()**, and **describe()**  
- Add new columns with **apply()** and **lambda functions**  
- Combine datasets using **merge()**, **concat()**, and **join()**  
- Save and load data with **CSV**, **Excel**, and **JSON** formats  

---

## 🧩 Example Dummy Dataset  

```python
import pandas as pd

# Create dummy employee dataset
data = {
    'EmployeeID': [101, 102, 103, 104, 105],
    'Name': ['Ali', 'Sara', 'Usman', 'Fatima', 'Hassan'],
    'Department': ['HR', 'IT', 'Finance', 'IT', 'HR'],
    'Salary': [60000, 80000, 75000, 90000, 65000],
    'Year': [2021, 2022, 2021, 2023, 2022]
}

df = pd.DataFrame(data)
print(df)
