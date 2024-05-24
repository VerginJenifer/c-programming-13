# C program to calculate total, average and percentage of three subjects for engineering admission.
## AIM:
To Write a C program to calculate total, average and percentage of three subjects for engineering admission
## ALGORITM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the marks of three subjects, total marks, average marks, and percentage.
4. Prompt the user to enter the marks for the first subject and read the input.
5. Prompt the user to enter the marks for the second subject and read the input.
6. Prompt the user to enter the marks for the third subject and read the input.
7. Calculate the total marks by summing up the marks of the three subjects.
8. Calculate the average marks by dividing the total marks by the number of subjects (3).
9. Calculate the percentage by dividing the total marks by the maximum possible marks (300) and then multiplying by 100.
10. Print the total marks, average marks, and percentage.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int x,y,z;
    float total,average,percentage;
    scanf("%d%d%d",&x,&y,&z);
    total=x+y+z;
    average=total/3;
    percentage=average;
    printf("Total marks = %.2f\nAverage marks = %.2f\nPercentage = %.2f",total,average,percentage);
    return 0;
    
}
```

## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-13/assets/136251012/bda09c0c-4056-4ef2-b1e2-1012b963f2ba)

## RESULT:
Thus, a C program to calculate total, average and percentage of three subjects for engineering admission was executed succcessfully.
