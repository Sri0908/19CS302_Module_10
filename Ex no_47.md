# EX 47 C function to insert a node in a linked list.
## AIM:
To write a C function to insert a node in a linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to insert a node in a linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End
  

## Program:
```c
struct Node{ 
char data;
struct Node *next;
}*head;
void insert(char data)
{
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp;
if(head==NULL)
{
head=n;
n->data=data;
n->next=NULL; 
temp=head; 
return;
}
}
else
{
while(temp->next!=NULL)
{
temp=temp->next;
}
n->next=NULL; 
n->data=data; 
temp->next=n;
}
}

```

## Output:

![image](https://github.com/user-attachments/assets/5c22ee4f-f01e-4b72-8faf-78e8caee01e0)


## Result:
Thus the program was executed and the output was verified successfully.
