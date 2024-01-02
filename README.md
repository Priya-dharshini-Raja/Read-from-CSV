# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using read_csv method
### Step 3:
use head and tail method to get the required contents from the file.
### Step 4:
use len() method to get the number of rows and columns.
### Step 5:
Print the output

## PROGRAM:

'''
#Developed by : Priyadharshini Raja
#Register number : 23013908

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```


### OUTPUT:
![output](<Screenshot 2024-01-02 224946.png>)

### RESULT:
Completed successfully.