# # Stack-Stack Reversal Program 🔁

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```
stack = []
n = int(input())
for i in range(n):
    val = int(input())
    stack.append(val)
reverse = []
while stack:
    reverse.append(stack.pop())
print(reverse)
```
## 🧪 Sample Input and Output
<img width="335" height="232" alt="Screenshot 2026-03-28 085801" src="https://github.com/user-attachments/assets/624e96c4-5c64-409b-a60c-b28279f36f85" />


## Result
Thus, the python program that reverse the values in a stack has been executed successfully.
