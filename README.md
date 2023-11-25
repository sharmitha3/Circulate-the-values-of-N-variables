# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate.
### Step 2: 
Get a list input from user.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the circulated value 
### Step 6: 
Call the function using function call and end the program.
## Program:
~~~
#Program to circulate N values.
#Developed by: SHARMITHA V
#RegisterNumber:23002259
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~

## Output:
![image](https://github.com/sharmitha3/Circulate-the-values-of-N-variables/assets/145974496/8061b53e-1d7b-4a0b-9507-83cf0afacd37)

## Result:
Thus the circulating the values in the list is successfully executed.
