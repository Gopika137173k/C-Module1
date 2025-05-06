## Datatypes & Operators-Quotient Finder in C

## Aim
To write a C program to find the **quotient** of two integer numbers.

## Algorithm
1. Declare variables `a`, `b`, and `quotient`.
2. Read two integers `a` and `b` from the user.
3. Calculate the quotient by dividing `a` by `b` and store the result in the variable `quotient`.
4. Print the values of `a`, `b`, and `quotient` using the `printf` function.
5. Return 0 to indicate successful execution.

## Program
```
#include <stdio.h>
int main() {
    int a, b, quotient; 
    printf("Enter the dividend (a): ");
    scanf("%d", &a);
    printf("Enter the divisor (b): ");
    scanf("%d", &b);
    if (b != 0) {
        quotient = a / b;
        printf("Dividend (a): %d\n", a);
        printf("Divisor (b): %d\n", b);
        printf("Quotient: %d\n", quotient);
    } else {
        printf("Error: Division by zero is not allowed.\n");
    }
    return 0;
}

``
## Output
Sample Output 1:
Enter the dividend (a): 20
Enter the divisor (b): 4
Dividend (a): 20
Divisor (b): 4
Quotient: 5
Sample Output 2:
Enter the dividend (a): 15
Enter the divisor (b): 0
Error: Division by zero is not allowed.

## Result
Program was impelemented and executed.

    
