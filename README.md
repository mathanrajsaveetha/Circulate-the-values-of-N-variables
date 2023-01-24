# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
define the function
### Step 2: 
enter the input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

## Program:
```python
#Program to circulate N values.
#Developed by: mathan raj.E
#RegisterNumber:22008971
def circulate():
    a=eval(input())
    n=int(input())
    c=a[n:]+a[:n]
    print("After circulating the values are:",c)
```

## Output:
![output](cir.n.png)

## Result:
the program was sucessufully executed.
