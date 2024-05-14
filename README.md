# EX- 11 -Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program. 


# Program for Copy contents of a file 
# Developed by:K.Ligneshwar
# Register Number:212223230113
```
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![image](https://github.com/ligneshwar/Copy-File/assets/149365037/79a8edfc-cf8a-46a0-99a7-6500a8741727)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
