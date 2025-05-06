## Conditional Statements: Positive Number Checker
## Aim
To write a C program that reads a value A from the user and checks whether it is a positive number or not.

## Algorithm
Declare a variable to store the input value A.

Use the scanf function to read the value of A from the user.

Check if the value of A is greater than zero.

If A is greater than zero, print a message indicating that it's a positive number.

Otherwise, print a message indicating that it's not a positive number.

End the program.

## Program

```
#include <stdio.h>
int main() {
    int A; 
    printf("Enter a number: ");
    scanf("%d", &A);
    if (A > 0) {
        printf("The number is positive.\n");
    } else {
        printf("The number is not positive.\n");
    }
    return 0;
}
``

## Output
Sample Output 1:
Enter a number: 10
The number is positive.
Sample Output 2:
Enter a number: -3
The number is not positive.

## Result
Program was implemented and executed.
