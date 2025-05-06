## Conditional Statements-Compare Two Numbers
## Aim
Write a C program to read values of x and y and print whether x == y or x != y using an if-else statement.

## Algorithm
Declare variables x and y.

Read two integers x and y from the user.

Check if x is equal to y using the if statement.

If x is equal to y, print "X is equal to Y".

If x is not equal to y, print "X is NOT equal to Y".

## Program
```
#include <stdio.h>
int main() {
    int x, y;
    printf("Enter the value of x: ");
    scanf("%d", &x);
    
    printf("Enter the value of y: ");
    scanf("%d", &y);
    if (x == y) {
        printf("X is equal to Y\n");
    } else {
        printf("X is NOT equal to Y\n");
    }

    return 0;
}
``

## Output
Sample Output 1 (Equal Values)
Enter the value of x: 10
Enter the value of y: 10
X is equal to Y
Sample Output 2 (Unequal Values)
Enter the value of x: 5
Enter the value of y: 8
X is NOT equal to Y


## Result
the programme was implemented and executed
