# EX 26 C program to find sum and average in the range from 18 to 25 using pointer.
## DATE:
## AIM:
To write a C program to find sum and average in the range from 18 to 25 using pointer.

## Algorithm
1. Start.
2. Create a structure and data member using pointer.
3. Prompt the user to enter a value.
4. Print the structure values.
5. End.
## Program:
```c
#include<stdio.h>
int main()
{
    int m, n, *a, *b;
    scanf("%d%d",&m, &n);
    a = &m;
    b = &n;
    float sum, avg;
    for(int i=*a; i<=*b; i++)
    {
        sum += i;
    }
    avg = sum/(*b-*a+1);
    printf("Sum= %.2f, Average= %.2f",sum, avg);
    return 0;
}
```

## Output:
<img width="1138" height="250" alt="Screenshot 2026-06-08 150705" src="https://github.com/user-attachments/assets/5f9e9e48-feb5-419b-b3dc-6fb8d537ffd0" />



## Result:
Thus the program was executed and the output was verified successfully.
