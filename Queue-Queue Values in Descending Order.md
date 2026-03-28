# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
```
q = []
n = int(input())
for i in range(n):
    val = int(input())
    q.append(val)

q.pop(0)  
q.pop(0)  

q.sort(reverse=True)
print(*q)
```

### Output:
<img width="551" height="433" alt="Screenshot 2026-03-28 085127" src="https://github.com/user-attachments/assets/aaec67ab-6942-4bad-b6f7-1ef3e0df8e40" />



## Result:
Thus, the Python program simulates a queue using a list is executed successfully.
