# Circulate-the-values-of-N-variables
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
End the program 

## Program:
```
Name: Kanagavel A K
Reg no: 212223230096
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:] + l[:n]
    print("After circulating the values are:",l)
```

## Output:
![Screenshot 2024-03-17 194152](https://github.com/KanagavelAK/Circulate-the-values-of-N-variables/assets/151514454/bca6045e-2ff4-4a19-ad0f-514bc5b71057)


## Result:
The output for circulate the values of n variables is successfull.
