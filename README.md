# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
```
      queue = []
      queue.append('a')
      queue.append('b')
      queue.append('c')
      print('Queue after elements are inserted:')
      print(queue)
      print('Deleting the first element inserted:')
      print(queue.pop(0))
      print('Queue after the first elements is deleted:')
      print(queue)
```
## Output
![image](https://github.com/user-attachments/assets/564cf71b-6351-41aa-afb3-c9ff8025aa09)

## Result
Thus, the program has been execueted successfully.

# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
```
      queue = []
      queue.append('a')
      queue.append('b')
      queue.append('c')
      queue.append('d')
      print('Initial Queue: ' ,queue)
      front=queue[0]
      rear=queue[-1]
      print("\nElement at the front of the queue is.... ", front)
      print("\nElement at the rear of the queue is ....", rear)
```

## Output
![image](https://github.com/user-attachments/assets/e2eb10bd-b8b3-4250-8bb1-c5b7b05a1d6d)


## Result
Thus, the program has been execueted successfully.
