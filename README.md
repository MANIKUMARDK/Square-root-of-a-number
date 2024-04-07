# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: MANIKUMAR D.K
RegisterNumber: 212223230121
*/

def newton(n,nt=100):
    a=float(n)
    for i in range(nt):
        n=0.5*(n+a/n)
    return n
a=int(input())
print("Square root of the number:",newton(a))

```

## Output:
![Screenshot 2024-04-07 214619](https://github.com/MANIKUMARDK/Square-root-of-a-number/assets/147215581/c375fe9e-26dc-41f0-93fb-36fa356dca0b)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
