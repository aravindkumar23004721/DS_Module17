# Ex 5 C) Depth First Graph
## DATE:26/04/2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1.	Start
2.	Allocate memory for a new node.
3.	Set the vertex field of the new node to the given value v.
4.	Set the next pointer of the new node to NULL.
5.	Return the newly created node.
6.	End

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: Aravind Kumar SS
RegisterNumber:  212223110004
*/
/*#include<stdio.h> #include <stdlib.h>
structnode{ int vertex;
struct node* next;
};
struct node*createNode(int v); struct Graph {
intnumVertices; int* visited;
// We need int**to storeatwodimensionalarray.
// Similary, we needstruct node**to storeanarrayofLinked lists struct node** adjLists;
};*/
struct node*createNode(int v) {
structnode* newNode=malloc(sizeof(struct node));
 
newNode->vertex=v; newNode->next=NULL; returnnewNode;
}

```

## Output:

![image](https://github.com/user-attachments/assets/072d7d54-ee88-4db5-b2fb-a9265e202db0)


## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
