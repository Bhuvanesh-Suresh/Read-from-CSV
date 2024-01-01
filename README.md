# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
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
#Program to read contents from csv file.
#Developed by:Bhuvanesh.S.R
#Register Number:212223240017

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows: ",len(df.axes[0]))
print("Number of coloumns: ",len(df.axes[1]))
```
## OUTPUT:
![exp 6 read from csv python](https://github.com/Bhuvanesh-Suresh/Read-from-CSV/assets/145742661/9f6c34fc-c2b4-49e3-a8c5-4b1f42ab838e)

## RESULT:
Thus the program is written to copy the contents from one file to another file
