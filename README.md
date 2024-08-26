## DATE:
# EXP NO:2 Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
print the result
## Program:
```
#Write a python program to Circulate the n variables using function concept
# Developed by: MONISH N
# Register no: 212223240097
def circulate():
    values=eval(input())
    n=int(input())
    for i in range(n):
        temp=values.pop(0)
        values.append(temp)
    print("After circulating the values are:",values)
```
## Output:
![Screenshot 2024-08-26 192720](https://github.com/user-attachments/assets/295fcac6-343e-4046-a60d-4a9ff33394a0)

## Result:
The output for circulate the values of n variables is successfull.
