## Program 30: Write a program to calculate n factorial using RECURSION

#include <stdio.h>

int factorial(int n);

int main()

{

int n;

printf("enter n : ");

scanf("%d", &n);

printf("factorial is : %d", factorial(n));

return 0;

}

int factorial(int n) 

{

if(n == 0) 

{

return 1;

}

int factnm1 = factorial(n-1);

int factn = factnm1 * n;

return factn;

}

**OUTPUT:enter n : 4**

**factorial is : 24**
