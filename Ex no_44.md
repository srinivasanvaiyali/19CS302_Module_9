# EX 44 C functions to perform enqueue, dequeue, display, peek in Queue using Array.
## DATE:
## AIM:
To write a C Write a functions to perform enqueue, dequeue, display, peek in Queue using Array.

## Algorithm
1. Start.
2. Define a variables.
3. Write a functions to perform enqueue,dequeue ,display,peek in Queue using array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
/*
C functions to perform enqueue, dequeue, display, peek in Queue using Array.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008  
*/
```
```
char queue[50]; 
int size=10,front,rear,i; 
void enqueue(char data) 
{ 
if(rear<size) 
{ 
if(front==-1) 
{ 
front=0; 
} 
rear=rear+1; 
queue[rear]=data; 
} 
{ 
printf("%c\n",queue[i]); 
} 
} 
void dequeue() 
{  
if(front==-1||front>rear) 
{ 
printf("Queue Underflow\n"); 
} 
else 
{ 
front=front+1; 
} 
 
} 
void peek() 
{ 
printf("%c\n",queue[front]); 
 
} 
 
}
```


## Output:

<img width="999" height="642" alt="441357411-ee8b9992-d1b1-4c5b-9274-6a9696e45f14" src="https://github.com/user-attachments/assets/eaa715ae-f44a-4e1d-a802-3224bb5251d6" />



## Result:
Thus the program was executed and the output was verified successfully.
