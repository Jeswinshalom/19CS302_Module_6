# EX 28 Create a C program to print 12 months in numbers using enumeration.

enum year{Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec}; 
## DATE:
## AIM:
To write a C program to print 12 months in numbers using enumeration.
 ## Algorithm
 1. Start.
2. Declare enum type
3. Declare all days in a week
4. Print result
5. End

## Program:
```c
#include <stdio.h>
enum year {Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec};
int main() {
    enum year m;
    for(m = Jan; m <= Dec; m++)
        printf("%d ", m + 1);
    return 0;
}
```

## Output:

<img width="1131" height="156" alt="image" src="https://github.com/user-attachments/assets/1e4db1f5-40fc-41af-b35f-df1534da4781" />


## Result:
Thus the program was executed and the output was verified successfully.
