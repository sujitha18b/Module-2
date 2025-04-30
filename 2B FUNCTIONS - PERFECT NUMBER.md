# Exp.No:2b  
## FUNCTIONS - FACTORIAL

### AIM  
To write a Python program to define a function that returns factorial of a number

### ALGORITHM

1.Start

2.Define a function called factorial(n)

3.Inside the function:

4.If n is 0 or 1:

5.Return 1 (since 0! = 1! = 1)

6.Otherwise:

7.Initialize a variable result = 1

8.For i from 2 to n:

9.Multiply result by i → result = result * i

10.Return result

11.Call the function with a number and print the result

12.End



### PROGRAM

def factorial(num):     <br />
    if num == 1 or num == 0:   <br />
        return 1   <br /> 
    else:    <br />
        return num * factorial(num-1)     <br />

num=int(input())   <br />
print(f"Factorial is {factorial(num)}")   <br />
        


### OUTPUT


![Screenshot 2025-04-30 091201](https://github.com/user-attachments/assets/5fb510f7-4135-4135-9f22-5fb8e04e5c51)



### RESULT
Thus,the given python program is implemented and executed sucessfully.
