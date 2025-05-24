# EX 60 C function to find the peek element of the queue using linked list.
## DATE:
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start. 
2. Define a variables. 
3. Write a functions to find peek in Queue using linked list. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End 

## Program:
```
/*
C function to find the peek element of the queue using linked list.

Developed by: 
RegisterNumber:  
*/
struct Node 
{ 
char data; 
struct Node *next; 
}*front=NULL,*rear=NULL;  
 
void peek() 
{ 
printf("peek:");  
printf("%c\n",front->data); 
}
```

## Output:

![image](https://github.com/user-attachments/assets/0668a275-7705-4ec3-8537-b5faa8d7a331)



## Result:
Thus the program was executed and the output was verified successfully.
