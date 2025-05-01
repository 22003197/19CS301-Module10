# Exp.no: 50
## SEB

### AIM

To write a python program to add few programming language in a queue(LIFO).

### ALORITHM 

1. Start the program.

2. Input n – Read the maximum size of the stack.

3. Create a LIFO stack using LifoQueue with size n.

4. Repeat n times:
   Read an input value and push it onto the stack using put().

5. Repeat n times:
   Pop and print each element from the stack using get() (LIFO order).

6. Terminate the program.
   
### PROGRAM

```
from queue import LifoQueue
n=int(input())
stack=LifoQueue(maxsize=n)
for i in range(n):
    stack.put(input())
for i in range(n):
    print(stack.get())
```

### OUTPUT

![image](https://github.com/user-attachments/assets/5cc7e8e3-c465-4551-a649-344d7791af9c)

### RESULT
Thus the python program was successfully created.
