# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:06-03-2025
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Start.
2. Declare three variable value of type int for marks.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Find total and average.
6. Print the result
7. End 

## Program:
```
program to calculate the total marks, average, and percentage of marks obtained in seven subjects
Developed by Karthick Kannan SP
Register number:212222060114

#include <stdio.h>
int main() {
 int sub1, sub2, sub3, total;
 float average;
 scanf("%d %d %d", &sub1,&sub2,&sub3);
 total = sub1 + sub2 + sub3;
 average = total / 3.0;
 printf("\nTotal : %d\n", total);
 printf("Average : %.2f\n", average);
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/6fd1b3d2-6bcb-4055-8233-b708db515e17)



## Result:
Thus the program was executed and the output was verified successfully.
