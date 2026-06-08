# EX 30 C program to multiply two integer  numbers using pointers in which memory allocated using calloc(). 
## DATE:
## AIM:
To write a C program to multiply two integer  numbers using pointers in which memory allocated using calloc(). 
## Algorithm
 1. Start.
2. Declare array size
3. Initialize array elements using malloc()
4. Update array size using realloc()
5. Print the result.
6. End 


## Program:
```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int *a, *b, *product;
    a = (int *)calloc(1, sizeof(int));
    b = (int *)calloc(1, sizeof(int));
    product = (int *)calloc(1, sizeof(int));
    scanf("%d", a);
    scanf("%d", b);
    *product = (*a) * (*b);
    printf("The result is %d\n", *product);
    free(a);
    free(b);
    free(product);
    return 0;
}

```
## Output:

<img width="1127" height="317" alt="image" src="https://github.com/user-attachments/assets/28097408-b984-4629-9441-53e1ff9d27f1" />


## Result:
Thus the program was executed and the output was verified successfully.
