# swapping of two numbers without 3rd variable


#include <stdio.h>

int main()
{
    int num1,num2;
    
    printf("enter a: ");
    scanf("%d",&num1);
    printf("enter b: ");
    scanf("%d",&num2);
    printf("Before swapping: \n");
    printf("a=%d and b=%d",num1,num2);
    num1=num1+num2;
    num2=num1-num2;
    num1=num1-num2;
    printf("\nAfter swapping: \n");
    printf("a=%d and b=%d",num1,num2);

    return 0;
}
