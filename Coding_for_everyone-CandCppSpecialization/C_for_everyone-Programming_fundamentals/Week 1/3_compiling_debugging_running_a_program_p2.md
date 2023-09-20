# Compiling, debugging and running a program part 2


## Steps to run a compiled program

- `ls` command can be used in a terminal to list out the files
- run the program by using `sample.exe` in the terminal

## How to create a program from scratch 
- vi `add3.c`
```c
/* Read three floats and print sum
Sep, 20, 2023
*/

#include <stdio.h>

int main(void){
    float a,b,c,sum;
    printf("Input three floats: ");
    scanf("%f%f,"&a,&b,&c);
    sum = a+b+c;
    printf("sum=%f\n\n",sum )
    return 0;
}
```
- compile by using `gcc -o add3.exe add3.c`
