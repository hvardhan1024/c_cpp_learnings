# Simple input/output - miles


```c
/*
Distance of a marathon in yards
by Harsha
Sep 20, 2023
*/

#include <stdio.h>
int main(void)
{
    int miles=26, yards=385;
    double kilometers;

    kilometers = 1.609 * (miles + yards/1760.0);
    printf("\nA marathon is %ls kilometers. \n\n",kilometers);

    return 0;
}
```