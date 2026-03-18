# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in six subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in six subjects.

## Algorithm
1. Start. 
2. Declare six variable value of type int for marks. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Find total and average. 
6. Print the result 
7. End.    

## Program:
```
developed by kalaivani P
212222060104
#include <stdio.h>
int main()
{
    int m1, m2, m3, m4, m5, m6;
    float total, average, percentage;
    scanf("%d %d %d %d %d %d", &m1, &m2, &m3, &m4, &m5, &m6);
    total = m1 + m2 + m3 + m4 + m5 + m6;
    average = total / 6.0;
    percentage = average;  
    printf("Total marks = %.2f\n", total);
    printf("Average marks = %.2f\n", average);
    printf("Percentage = %.2f\n", percentage);
    return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/a5e83f30-3de6-4667-97d0-c49dbb7f8c99)



## Result:
Thus the program was executed and the output was verified successfully.
