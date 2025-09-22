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
num1=int(input())
num2=int(input())
num3=int(input())

max_number = num1 if (num1 > num2 and num1 > num3) else (num2 if num2 > num3 else num3)

print(f"The maximum of {num1}, {num2}, {num3} is {max_number}")
```

## OUTPUT

The maximum of 15, 20, 11 is 20

## RESULT

<img width="901" height="367" alt="image" src="https://github.com/user-attachments/assets/8fa9ca46-c996-43ae-8dce-8b8e927ee0f7" />
