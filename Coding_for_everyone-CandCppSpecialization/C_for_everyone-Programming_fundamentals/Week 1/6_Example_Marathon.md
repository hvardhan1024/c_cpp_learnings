# Program to convert miles into kilometers


```c
/*
The distance of a marathon in kilometers
by Harsha
Sep 20, 2023
*/

#include<stdio.h>

int main(void)
{
    int miles = 26,yards=385;
    double kilometers;

    kilometers = 1.609 * (miles + yards/1760.0);
    printf("\nA marathon is %ls kilometers. \n\n",kilometers);

    return 0;
}
```

- comments
- int main means the function returns an integer
- initialization and declaration of variables
- return 0 denotes that the program ended correctly