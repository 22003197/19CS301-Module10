# Exp.no: 48
## QUEUE

### AIM

### ALORITHM 

1. Start the program.

2. Define a Queue class with:
   A constructor to initialize an empty list queue.
   add_element(val) method:
   If val is not already in the queue, insert it at the front.
   size() method to return the queue length.

3. Create TheQueue object.

4. Input n – Number of elements to add.

5. Repeat n times:
   Read input and call add_element() to add to the queue.

6. Print the final queue list

7. Terminate the program.
   
### PROGRAM

```
class Queue:  
  def __init__(self):  
      self.queue = list()  
  def add_element(self,val):
      if val not in self.queue:  
          self.queue.insert(0,val)  
          return True  
      return False  
  def size(self):  
      return len(self.queue)  
  
TheQueue = Queue()  
n=int(input())
for i in range(n):
    TheQueue.add_element(input())  
print(TheQueue.queue)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/9e4b73a9-ac1c-4269-b383-204e76500de2)

### RESULT

Thus the python program was successfully created.
