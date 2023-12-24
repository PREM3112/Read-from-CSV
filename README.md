# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output
## PROGRAM:
```
# Developed by: PREM.R
# Register Number: 23002486
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 131558](https://github.com/PREM3112/Read-from-CSV/assets/145449383/9685a7fa-8d6a-48c0-ba96-ef0b1db038a1)

## RESULT:
thus the output got successfully.
