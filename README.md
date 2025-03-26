# LINKED-LIST-IMPLEMENTATION

 **COMPANY** : CODTECH SOLUTIONS

 **NAME** : VASAMSETTI GRACE SHYNI

 **INTERN ID**  : CT08WBU

 **DOMAIN** : C PROGRAMMING

 **DURATION** : 4 WEEKS 

 **MENTOR** : NEELA SANTHOSH KUMAR

**DESCRIPTION**

**What is a Singly Linked List?**

A singly linked list is a linear data structure where elements, called nodes, are connected using pointers. Each node consists of:
1. **Data**: The actual information stored in the node.
2. **Next Pointer**: A pointer that links the current node to the next node in the sequence.

Unlike arrays, singly linked lists do not require contiguous memory allocation. This flexibility allows dynamic memory allocation and makes it easy to insert or delete elements without worrying about shifting data.

**Key Operations in a Singly Linked List**

A singly linked list supports three primary operations:
**Insertion**: Add nodes to the list, either at the beginning, end, or a specific position.
**Deletion**: Remove nodes from the list, including from the beginning, end, or a specific position.
**Traversal**: Access and display the data in each node sequentially.
 
These operations ensure that you can manipulate the list dynamically based on the requirements of the program.

**1. Insertion**
Adding new nodes is essential for building and modifying the list. The following are the methods to insert nodes:

**Insertion at the Beginning**:
 Allocate memory for a new node.
 Set its `next` pointer to point to the current head node.
 Update the head pointer to the new node.

**Insertion at the End**:
 Allocate memory for a new node.
 Traverse the list to find the last node.
 Set the `next` pointer of the last node to the new node.

 **2. Deletion**

Deleting nodes helps manage memory and modify the list. Here are the methods:

**Deletion from the Beginning**:
 Update the head pointer to the second node in the list.
 Free the memory of the original head node.

**Deletion from the End**:
Traverse the list to find the second-to-last node.
Set its `next` pointer to `NULL`.
Free the memory of the last node.

**3. Traversal**
Traversing the list allows you to access and display the values stored in each node:

 **Advantages of Singly Linked Lists**

**Dynamic Size**: Unlike arrays, linked lists can grow or shrink dynamically, making them ideal for scenarios with uncertain data sizes.
**Efficient Insertions/Deletions**: These operations are easier compared to arrays, as you don't need to shift elements.

 **Applications**

Singly linked lists are widely used for:
1. **Data Management**: Implementing stacks and queues for dynamic datasets.
2. **Graph Algorithms**: Representing adjacency lists.
3. **Symbol Tables**: Storing identifiers and keywords dynamically in compilers.

**OUTPUT**

![Image](https://github.com/user-attachments/assets/5d9d334f-9e5c-4a27-ae14-60e4bc26ceed)
