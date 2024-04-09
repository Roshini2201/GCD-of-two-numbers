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
# Developed by: ROSHINI S
 # Register Number: 212223240142
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:

![Screenshot 2024-04-09 115603](https://github.com/Roshini2201/GCD-of-two-numbers/assets/154105318/acd1441a-4f66-482d-9e4a-df1f0bbe1684)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
