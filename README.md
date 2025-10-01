# Experiment 17 – Linked List Operations in C++


---

## Aim  
To implement **Linked List operations using Classes in C++**.  
- **Experiment 17 A**: Create and connect two nodes.  
- **Experiment 17 B**: Insert nodes at the front of a linked list.  

---

## Theory  

- A **Linked List** is a dynamic data structure consisting of nodes connected using pointers.  
- Each node has two parts:  
  - **Data** – value stored in the node.  
  - **Pointer (next)** – address of the next node.  
- The **head pointer** always points to the first node in the list.  
- Types of linked list operations:  
  - Creating nodes  
  - Connecting nodes  
  - Traversing and displaying nodes  
  - Insertion and deletion of nodes  

---

## Algorithm  

### Experiment 17 A – Creating and Connecting Nodes  

1. Start the program.  
2. Define a class `Link` with data and pointer to next node.  
3. Create a constructor to initialize data and set `next = NULL`.  
4. Write a `display()` function to show node data and next pointer.  
5. In `main()`, create two nodes dynamically using `new`.  
6. Connect the first node to the second (`l1->next = l2`).  
7. Display both nodes.  
8. End the program.  

---

### Experiment 17 B – Insertion at Front of Linked List  

1. Start the program.  
2. Define a class `Node` with data and a pointer to the next node.  
3. Write a function `addToFront()` to:  
   - Create a new node.  
   - Link it to the current head.  
   - Update head to new node.  
4. Write a function `printList()` to traverse and display all nodes.  
5. In `main()`:  
   - Initialize head as `NULL`.  
   - Insert multiple nodes using `addToFront()`.  
   - Print list after each insertion.  
6. End the program.  

---

## Conclusion  

- In **17 A**, learned how to create and connect two nodes using pointers.  
- In **17 B**, implemented **insertion at the front** of a linked list.  
- Understood that:  
  - Each node stores data and a pointer to the next node.  
  - The **head pointer** determines the starting point of the list.  
- These are the basic building blocks for more complex linked list operations like insertion at end, deletion, and traversal.  
