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
Take a list as input from the user and assign it to the variable l.
### Step 3: 
Take an integer as input from the user and assign it to the variable n.
### Step 4: 
Update the list l by taking the slice from index n to the end of the list and appending it with the slice from the start of the list to index n.
### Step 6: 
Print the updated list l with the message “After circulating the values are:”.

## Program:
```
#Program to circulate N values.
#Developed by: KEERTHANA SARAVANAN
#RegisterNumber:23013398
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
    
```
## Output:

![Alt text](<Circulate Output.png>)

## Result:

Thus the circulation of values are successfully executed