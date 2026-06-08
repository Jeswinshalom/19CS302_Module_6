# EX 27 C program to add value E,R to list which already have P,R,I,N,T  in that  using realloc() and print all value in the list.
## DATE:
## AIM:
To write a C program to add value E,R to list which already have P,R,I,N,T  in that  using realloc() and print all value in the list.

## Algorithm
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Check eligible for marriage.
6. If age >= 21, print "Eligible".
7. If false, print " Not Eligible".
8. End.
   
## Program:
```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    char *list = malloc(5);
    int i;

    list[0] = 'P'; list[1] = 'R'; list[2] = 'I'; list[3] = 'N'; list[4] = 'T';
    list = realloc(list, 7);
    list[5] = 'E'; list[6] = 'R';

    for (i = 0; i < 7; i++)
        printf("%c ", list[i]);

    free(list);
    return 0;
}
```

## Output:

<img width="1146" height="167" alt="image" src="https://github.com/user-attachments/assets/ad3715ae-0da4-4fff-96f8-3c45e69c9cd1" />

## Result:
Thus the program was executed and the output was verified successfully.
