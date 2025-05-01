# Exp.no: 46
## STACK

### AIM

To write a python program to get the integer values from the user and push only the odd number into the stack and later pop the last 2 elements.

### ALORITHM 

1. Start the program.

2. Read the number of elements.

3. Initialize empty list l.

4. Read n integers:
   If the number is odd, append it to list l.

5. Print the list l (odd numbers only).

6. Remove last two elements from list l using pop().

7. Print the updated list l.

8. Terminate the program.

### PROGRAM

```
l=[]
n=int(input())
for i in range(n):
    value=int(input())
    if value%2!=0:
        l.append(value)
print(l)
for i in range(2):
    l.pop()
print(l)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/982eafe4-57a7-4dd7-8d4b-9150a41d62e8)

### RESULT
Thus the python program was successfully created.
