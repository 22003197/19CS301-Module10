# Exp.no: 49
## TYPES OF QUEUE

### AIM

To write a python program to get the 4 integer values from user and display the values  using multiprocessing library.

### ALORITHM 

1. Start the program.

2. Create a multiprocessing queue using Queue().

4. Input 4 integers – For each input, add it to the queue using put().

5. Retrieve and print 4 values – Use get() to remove and print each item from the queue in the same order.

6. Terminate the program.
   
### PROGRAM

```
from multiprocessing import Queue
# instantiating a queue object
queue = Queue()
list1=[]
for i in range(4):
    queue.put(int(input()))
for i in range(4):
    print(queue.get())
```

### OUTPUT

![image](https://github.com/user-attachments/assets/35ca1fb5-a0b4-4b0a-9498-5e26a9eb51a1)

### RESULT
Thus the python program was successfully created.
