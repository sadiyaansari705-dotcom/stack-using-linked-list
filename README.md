Stack Implementation in C (Using Linked List)

This project demonstrates how to implement a Stack Data Structure in C using a Linked List.

The program performs:

✅ Push operation

✅ Peek (display top element) operation

The stack follows the LIFO (Last In, First Out) principle.

🧾 Program Description

The stack is implemented using:

A Node structure containing:

data

next pointer

A global pointer top that points to the top of the stack.

Elements are dynamically allocated using malloc().

🧠 Concepts Used

Structures in C

Pointers

Linked List

Dynamic Memory Allocation (malloc)

Stack (LIFO Principle)

Functions

📚 Stack Operations Explained
🔹 Push Operation

Create a new node using malloc().

Assign the value to the new node.

Set the new node’s next pointer to the current top.

Update top to the new node.

🔹 Peek Operation

If the stack is empty, display a message.

Otherwise, display the value stored at top.

📤 Sample Output
Top element = 30

Since elements are pushed in the order 10 → 20 → 30,
the last pushed element (30) becomes the top.

🚀 How to Run
🔹 Compile the Program
gcc main.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
📂 Project Structure
📁 stack-using-linked-list
 ├── main.c
 └── README.md
⚠️ Limitations

Pop operation is not implemented.

No memory deallocation using free().

No stack size limit handling (dynamic memory based).

🔧 Possible Improvements

Add pop operation.

Add display function to show entire stack.

Implement menu-driven version.

Free allocated memory before program exit.

👨‍💻 Author


B.Tech Student

If you want, I can also provide:

⭐ Full stack implementation (push, pop, peek, display)

⭐ Menu-driven version

⭐ Lab submission short version
