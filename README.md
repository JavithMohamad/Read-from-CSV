# Read-from-CSV
## AIM:

To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1:
import panda module as pd

### Step 2:
Read the csv file

### Step 3:
print the first 10rows

### Step 4:
print the next 5rows

### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```python
#Program to read contents from a CSV file.
#Developed by: JAVITH M
#Reg No: 212222110014

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```

## OUTPUT:
`![new ](https://github.com/JavithMohamad/Read-from-CSV/assets/121215951/1a371385-61a2-43c3-8825-9d4492cddd2c)

## RESULT:
The program is executed successfully
