# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```python
#Reg N0-212222060262
#Name- SUJAN S B

l=eval(input())
sum=1
for i in range(0,len(l)):
    if l[i]%10==2:
        sum*=l[i]
print("Product= {}".format(sum))
```

### OUTPUT
<img width="932" height="214" alt="image" src="https://github.com/user-attachments/assets/7910a08b-aa08-4222-b094-87960d7631cf" />

### RESULT
Thus a python program to display the product of all the values which are ending with 2 from a list has been successfully implemented.
