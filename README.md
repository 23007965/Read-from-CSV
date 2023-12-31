# Read-from-CSV

## AIM:
Python program to read contents from csv file
## ALGORITHM:
### Step 1:
import and load
### Step 2:
Peek data
### Step 3:
Check dimensions
### Step 4:
Print the number of rows and columns in the DataFrame

## PROGRAM:
```
#Program to read contents from CSV file
#Developed by: P PARTHIBAN
#Register Number: 23007965


import pandas as pd
df=pd.read_csv("data.csv")
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/23007965/Read-from-CSV/assets/138971238/c38dee80-2471-4228-957b-4c9ea1bbff2e)


## RESULT:
Thus the program to read contents from CSV file is executed.
