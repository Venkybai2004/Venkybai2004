#include<stdio.h>
#include<conio.h> 
void main()
{
    int nu1,num2;
    char op ;
    printf("Enter a num1:");
    scanf("%d",&num1);
    
    printf("Enter a num2:");
    scanf("%d",&num2);
    
    printf("Enter operator:");
    scanf("\n%c",&op);
    
    if(op=='+')
    {
    printf("Sum:%d",num1+num2);
    }
    else if(op=='-')
    {
    printf("Diff:%d",num1-num2);
    }
    else if(op=='*')
    {
    printf("Quotient:%d",num1*num2);
    }
    else if(op=='/')
    {
    printf("product:%d",num1/num2);
    }
    else if(op=='÷')
    printf("modulo:%d",num1÷num2);
    }
    else
    printf("invalid operator")
    getchar();
}
