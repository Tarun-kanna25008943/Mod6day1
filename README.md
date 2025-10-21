# EX-01 Program to Calculate the Area of a Triangle Using Pointers

## AIM:
To write a C program that calculates the area of a triangle for a given base (100) and height (50) using pointers.

## ALGORITHM:

1. Start
2. Declare height, base, and pointers ptr1, ptr2.
3. Assign addresses: ptr1 = &height, ptr2 = &base.
4. Read height and base using scanf("%f %f", ptr1, ptr2).
5. Calculate area: area = 0.5 * (*ptr1) * (*ptr2).
6. Print height, base, and area.
7. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    float height,base;
    float *ptr1,*ptr2;
    ptr1 = &height;
    ptr2 = &base;
    printf("Enter the height and base of the triangle: ");
    scanf("%f %f",ptr1,ptr2);
    float area = 0.5*(*ptr1)*(*ptr2);
    printf("Area of the triangle with base %.2f and height %.2f = %.2f",*ptr1,*ptr2,area);
    
}
```

## OUTPUT:
<img width="765" height="126" alt="image" src="https://github.com/user-attachments/assets/843e78c3-f0de-4e85-abd1-1ac31b6c3136" />


## RESULT:
The program successfully calculates and displays the area of a triangle using pointers for base and height.
