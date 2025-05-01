# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and subtraction operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `sub`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform subtraction 
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'



### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `sub(self)`: Performs the subtraction operation. 
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `sub()` method and print the result.
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.


### PROGRAM

```
# Reg.No-212223050048
# Name-SIBIRAJI M
# Write your code here
class saveetha:
    def setvalues(self,a,b):
        self.a=a
        self.b=b
    
    def add(self):
        return self.a + self.b
    def mul(self):
        return self.a * self.b
        
a=int(input())
b=int(input())
c=saveetha()
c.setvalues(a,b)

while True:
    choice=int(input())
    if choice == 1:
        print("Result: ",c.add())
    elif choice == 2:
        print("Result: ",c.mul())
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/a66b9186-2877-4088-b569-ee0e3018ac25)

### RESULT
Thus the Python program to perform addition and subtraction operations using a class is executed successfully.
