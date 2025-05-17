# EX 49 C function to search an element in the doubly linked list.
## AIM:
To write a C function to search an element in the doubly linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to perform all basic operations.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.  

## Program:
```c
struct Node
{
    struct Node *prev;
    struct Node *next;
    int data;
}*head;
void search(int data)
{
    struct Node *temp;
    temp=head;
    int i=1;
    while(temp!=NULL)
    {
        if(data==temp->data)
        {
            printf("item %d found at location %d",data,i);
            return;
        }
        i++;
        temp=temp->next;
    }
    printf("Item not found");
}
```

## Output:
![Screenshot 2025-05-13 191957](https://github.com/user-attachments/assets/f9119353-c0b5-4e59-9ed1-0a5604da29d7)



## Result:
Thus the program was executed and the output was verified successfully.
