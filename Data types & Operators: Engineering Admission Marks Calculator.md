# Data types & Operators:Engineering Admission Marks Calculator

## Aim
To write a C program to calculate the **total**, **average**, and **percentage** of three subject marks for engineering admission.

## Algorithm
1. Declare variables `a`, `b`, `c`, `total`, `average_marks`, and `percentage`.
2. Read marks `a`, `b`, and `c` from the user.
3. Calculate `total` as the sum of `a`, `b`, and `c`.
4. Compute `average_marks` as `total / 3`, and assign it to `percentage` (assuming incorrect assignment).

## Program
```
#include <stdio.h>
int main() {
    int a, b, c;                
    int total;                  
    float average_marks, percentage;
    printf("Enter marks for subject A: ");
    scanf("%d", &a);
    printf("Enter marks for subject B: ");
    scanf("%d", &b);
    printf("Enter marks for subject C: ");
    scanf("%d", &c);
    total = a + b + c;
    average_marks = total / 3.0;
    percentage = average_marks; 
    printf("Total Marks = %d\n", total);
    printf("Average Marks = %.2f\n", average_marks);
    printf("Percentage = %.2f%%\n", percentage);
    return 0;
}
```

## Output
Sample Output 1
Enter marks for subject A: 85
Enter marks for subject B: 90
Enter marks for subject C: 80
Total Marks = 255
Average Marks = 85.00
Percentage = 85.00%
Sample Output 2
Enter marks for subject A: 60
Enter marks for subject B: 70
Enter marks for subject C: 65
Total Marks = 195
Average Marks = 65.00
Percentage = 65.00%


## Result
Program was implemented and executed.
