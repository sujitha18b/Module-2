# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN


### AIM  
To write a Python program  to print reversed pyramid pattern in Python.


### ALGORITHM

1.Start

2.Input the number of rows n (height of the pyramid)

3.Loop from i = 0 to n - 1:

4.Print i spaces → " " * i

5.Print 2*(n - i) - 1 stars → "*" * (2 * (n - i) - 1)

6.Go to the next line after each row

7.End


### PROGRAM

n=int(input())  <br />
s=(2*n)-2         <br />
for i in range(n,-1,-1):  <br />
    for j in range (s,0,-1):  <br />
        print(end=" ")      <br />
    s=s+1           <br />
    for j in range(i+1):    <br />
        print("*",end=" ") <br />
    print()
    
### OUTPUT

![Screenshot 2025-04-30 093254](https://github.com/user-attachments/assets/7c849ed8-5868-4df6-911b-ef3ffb02806b)

### RESULT
Thus,the given python program is implemented and executed sucessfully.
