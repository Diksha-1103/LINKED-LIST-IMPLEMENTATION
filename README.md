# LINKED LIST IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DIKSHA KUMARI

*INTERN ID*: CTO4DF77

*DOMAIN*: C LANGUAGE

*DURATION*: 4 WEEKS

*MENTOR NAME*: NEELA SANTOSH

**DESCRIPTION OF THE TASK**

A singly linked list is the most simple type of linked list, with each node containing some data as well as a pointer to the next node. That is a singly linked list allows traversal of data only in one way.
A singly linked list is a linear data structure where each element (called a node) contains:
   (a) Data (the actual value)
   (b) A pointer to the next node in the list
   (c) The list ends with a node that has its next pointer set to NULL.

There are several linked list operations that allow us to perform different tasks & the basic linked list operations are:

  (1) Traversal – Access the nodes of the list
  (2) Insertion – Adds a new node to an existing linked list
  (3) Deletion – Removes a node from an existing linked list
  (4) Search – Finds a particular element in the linked list


(A). Traverse a Linked List:
Accessing the nodes of a linked list in order to process it is called traversing a linked list. Normally we use the traverse operation to display the contents or to search for an element in the linked list.
The process of traversing a singly linked list involves printing the value of each node and then going on to the next node and print that node's value also and so on, till we reach the last node in the singly linked list, whose next node points towards the null. We can also traverse the singly linked list using recursion. We start at the head node of the singly linked list, check if it is null or not and print its value. We then call the traversal function again with the next node passed as pointer

(B). Insertion in a linked list:
Insertion in a linked list involves adding a new node at a specified position in the list. There are several types of insertion based on the position where the new node is to be added:
    At the front of the linked list  
    Before a given node.
    After a given node.
    At a specific position.
    At the end of the linked list

(C). Deletion in a linked list:
There is a singly-linked list head and we want to delete a node node in it. You are given the node to be deleted node. You will not be given access to the first node of head. All the values of the linked list are unique, and it is guaranteed that the given node node is not the last node in the linked list. Deleting a node in a Linked List is an important operation and can be done in three main ways:
    Removing the first node
    Removing a node in the middle
    Removing the last node.

(D). Searching node in a linked list:
The idea is to traverse all the nodes of the linked list, starting from the head. While traversing, if we find a node whose value is equal to key then print "Yes", otherwise print "No".The idea is to recursively traverse all the nodes starting from the head of linked list. For any node, if the value is equal to key, then return true. Otherwise, recursively search the next node. If at any point the head reaches NULL, it means that we have reached the end of linked list so return false.









