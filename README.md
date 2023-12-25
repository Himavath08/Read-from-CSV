# Read-from-CSV

## AIM:To write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1:Import pandas as pd.
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and columns
### Step 5:Print the output

## PROGRAM:
```
#Programmed By: M HIMAVATH
#RegisterNumber: 23010121
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no.of.rows",len(df.axes[0]))
print("no.of.columns",len(df.axes[1]))  
```
## OUTPUT:
![WhatsApp Image 2023-12-25 at 08 40 31_32f6aa8b](https://github.com/Himavath08/Read-from-CSV/assets/139110631/b89420d4-2afb-4384-8c8b-94176279c433)

## RESULT:
 Thus a python program is written to read the contents of a CSV file.
