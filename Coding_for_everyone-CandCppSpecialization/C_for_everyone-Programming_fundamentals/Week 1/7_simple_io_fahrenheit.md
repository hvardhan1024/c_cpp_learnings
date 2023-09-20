# Simple input/output - fahrenheit


```c
/*
Conversion of fahrenheit to Celsius
C = (F -32)/1.8
by Harsha
Sep 20, 2023
*/

#include <stdio.h>
int main(void)
{
    int fahrenheit, celsius;
    printf("Please enter fahrenheit as an integer: ");
    scanf("%d",&fahrenheit);
    celsius = (fahrenheit-32)/1.8; // conversion
    printf("\n %d fahrenheit is %d celsius.\n",fahrenheit,celsius);

    return 0;
}
```