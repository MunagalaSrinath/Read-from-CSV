# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:Start the python.


### Step 2:Import pandas.
### Step 3:Mention the CSV file which is to be read.
### Step 4:Read the contents of the CSV file using df.read function.


### Step 5:End the program.

## PROGRAM:
```
'''
DEVELOPED BY : M Srinath
REGISTER NUMBER : 22000990
'''

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```

## OUTPUT:
![214657244-3a7c4ec7-8fab-440a-ac6e-3de658fdc673](https://user-images.githubusercontent.com/118678482/214667715-39581f47-7390-438a-83bf-eb47060f0273.jpg)


## RESULT:
