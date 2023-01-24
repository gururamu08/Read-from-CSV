# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:
```
'''
DEVELOPED BY : GURUMOORTHI R
REGISTER NUMBER : 22008475
'''

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```

## OUTPUT:
![output](/Screenshot%202023-01-24%20105630.jpg)

## RESULT:
A python program to read data from CSV files has been created successfully.