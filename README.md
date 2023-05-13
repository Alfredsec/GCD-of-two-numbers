# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
"""
To find the gcd of a number
Name:Alfred A B
Register:212222110002
"""
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        s=n2
    else:
        s=n1
    for i in range(1,s+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![gcd alfred](https://github.com/Alfredsec/GCD-of-two-numbers/assets/120621608/e3230156-f1d4-45fd-80a8-b3261b6324e1)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
