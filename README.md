# Singly_linked_list
Singly Linked List can be defined as collection of objects called nodes that are randomly stored in the memory.
A node contains two fields i.e. data stored at that particular address and the pointer which contains the address of the next node in the memory.
The last node of the list contains pointer to the null.


The syntax for creating a node:

struct Node
{
  int Data;
  Struct Node *next;
};
The code will create a data type Node, which  will be able to store two values-:
int value – data
pointer value – address of the next node

Insertion of a node

struct node   
{  
    int data;   
    struct node *next;  
};  
struct node *head, *ptr;   
ptr = (struct node *)malloc(sizeof(struct node *));  



Circular Linked List is a linked list where all nodes are connected to form a circle.
In a circular linked list, the first node and the last node are connected to each other which forms a circle. There is no NULL at the end.
In a circular Singly linked list, the last node of the list contains a pointer to the first node of the list. We traverse the circular singly linked list until we reach the same node where we started. The circular singly linked list has no beginning or end. 


