# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
write the function definition
### Step 2: 
Get the input from the user which should be circulated
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the circulated values
### Step 6: 
end program
## Program:
```
#Program to circulate N values.
#Developed by: HarrishVenkat
#RegisterNumber:23013973
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)

```
## Output:
![circulate](https://github.com/HarrishVenkat/Circulate-the-values-of-N-variables/assets/144979588/5e787a03-e8c2-4d66-8c7a-58b0deec2adf)

## Result:
Thus circulate the values are sucessfully executed
