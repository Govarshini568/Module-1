# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223020009
# Name-Govarshini.P


a=int(input())
b=int(input())
c=int(input())
if (a<=b and a<=c):
    Smallest=a
elif(b<=c):
    Smallest=b
else:
    Smallest=c
print("The Smallest  of the three a=",a, "b=",b, "c=",c, "is",Smallest)

## OUTPUT
![smallest](https://github.com/user-attachments/assets/a4d4b983-d55a-4bf4-b517-1a369253e30c)


## RESULT
Thus the Python program to find the minimum between three integer numbers using a conditional expression is done successfully.
