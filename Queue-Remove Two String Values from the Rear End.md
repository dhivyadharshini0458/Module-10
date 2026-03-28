# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
```
q = []
n = int(input())
for i in range(n):
    s = input()
    q.append(s)
q.pop()  
q.pop() 
print(q)
```

### Output:
<img width="444" height="379" alt="Screenshot 2026-03-28 085310" src="https://github.com/user-attachments/assets/9587b1da-8191-49c9-ad6b-2e8c638f0c3b" />



## Result:
Thus, the python program that remove two string values from the rear end of the list is executed successfully.
