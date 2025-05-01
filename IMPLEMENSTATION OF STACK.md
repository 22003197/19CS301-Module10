# Exp.no: 47
## IMPLEMENTAION OF STACK

### AIM

To write a python program to implement the stack using deque method for rotating the stack.

### ALORITHM 

1. Start the program.

2. Define function fun(r) – Takes rotation value r.

3. Initialize empty deque de.

4. Input n – Read the number of elements.

5. Read n float values – Append each to the deque de.

6. Print original deque – "Stack before rotation".

7. Rotate the deque by r positions using de.rotate(r).

8. Print rotated deque – "Stack after rotation".

9. Terminate the program.
    
### PROGRAM

```
import collections
def fun(r):
    de=collections.deque([])
    n=int(input())
    for i in range(n):
        de.append(float(input()))
    print("Stack before rotation",de)
    de.rotate(r)
    print("Stack after rotation",de)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/a36ff3e2-6284-459e-83fc-c6d8f01faf94)

### RESULT
Thus the python program was successfully created.
