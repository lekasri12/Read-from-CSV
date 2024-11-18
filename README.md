# EX-12-Read-from-CSV
## Date:

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
Developed by: G Lekasri

Register number: 212223100025
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))

```

## OUTPUT:
![Screenshot 2024-05-14 062246 py 12](https://github.com/user-attachments/assets/d6cec35f-367a-4f42-8e0d-d9702081c532)
![Screenshot 2024-05-14 062255 py 12(1)](https://github.com/user-attachments/assets/734dc0ca-6358-41a3-b31a-6c47186037af)





## RESULT:
