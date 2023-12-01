# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step1:
1. Define a function.
## step2:
2. Assign number_iters = 100 in the function to perform 100 iteratios.
## step3:
3. Set i = 0.
## step4:
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## step5:
5. Return number

## Program:
```
#Square root of the number
#Developed by:S.kathiranand
#Reg No:23013711
def newton_method(number,number_iters = 100):
    a=float(number)
    for i in range(number_iters):
        number=0.5 * (number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:

![output](<Screenshot 2023-12-01 133158-1.png>)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
