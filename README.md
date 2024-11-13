# Ex - 04 
# DATE : 28/08/24
# Find the GCD of two numbers :

## AIM :

To write a program to find the GCD of two numbers using function.

## Equipments Required :

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm :

1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program :

```
Program to find the gcd of two number using function.
Developed by: Aankarsh J
RegisterNumber: 22304386
def gcd():  
    number1,number2=int(input()),int(input())  
    if number1>number2:   
        smaller=number2    
    else:   
        smaller=number1  
    for i in range(1,smaller+1):   
        if number1%i==0 and number2%i==0:   
            gcd1=i   
    print("GCD of two numbers is:",gcd1) 

```
## Output :
![Ex - 4 (Image)](https://github.com/user-attachments/assets/0d8c1f1a-0ccb-4a42-9eb9-06bf7bc727d4)

## Result :

Thus the program to find the GCD of two numbers is written and verified using python programming.
