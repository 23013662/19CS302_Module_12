# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a program to display stack elements using linked list. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 

## Program:
```
/*
C function to display stack elements using Linked List.(store integer data in stack) .

Developed by:santhiya c 
RegisterNumber:212223060247  
*/
Struct Node 
{ 
int data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *temp= head; 
while(temp!=NULL) 
{ 
printf("%d\n",temp->data); 
temp=temp->next; 
} 
 
} 

```

## Output:

![image](https://github.com/user-attachments/assets/232d3f8c-6fdb-4a6d-9ffc-5f2191c3aa2c)
 


## Result:
Thus the program was executed and the output was verified successfully.
