#include<stdio.h>
int main()
{
    int a=7;
    int b=5;
    int add;
    int sub;
    int multiply;
    float divide;
    float rem;
    printf("Sum of two number:\n");
    printf(" Value of a is:%d\n",a);
    printf("Value of b is:%d\n",b);
    add=a+b;
    printf("Sum of a and b is:%d\n",add);
    printf("Difference of two number:\n");
    sub=a-b;
    printf("Subtraction of a and b is:%d\n",sub);
    printf("Multiplication of two number:\n");
    multiply=a*b;
    printf("Multiply of a of b is:%d\n",multiply);
    printf("division of two number:\n");
    divide=a/b;
    printf("Result of division:%f\n",divide); 
    printf("Remainder:\n");
    rem=a%b;
    printf("Left after divison:%f\n",rem);
printf("vlaue of a and b:\n");

    if(a>b)
        printf("A is greater than b:\n");

else
printf("B is greater than a");

printf("Check number is odd or even:\n");
if(a%2==0)

    printf("A is even number:\n");
else if(b%2==0)
    printf("B is a even number:\n");
else
printf("A and B  both are  odd number:\n");
printf("Check number is positive or negative:\n");
    if(a>0 && b>0)
        printf("Number is positive:\n");
    else
        printf("Number is negative:\n");



