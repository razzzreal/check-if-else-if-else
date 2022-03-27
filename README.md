#include<stdio.h>
void main()
{
    int a;
    printf ("enter a number");
    scanf(" %d",&a);
    if(a<20)
    {
        printf("a is less than 20");
        
    }
    else if(a<100)
    {
        printf ("a is less than 100");
        
    }
    else
    {
        printf("a is greater then 100");
    }
}
