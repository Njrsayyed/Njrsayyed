// simple calculator
//or
//write a program to add,sub,mult,and divide two number accpect from user switch 
#include <stdio.h>
void main() 
{
int n1,n2,add,sub,mult,div,option;
printf("enter the first number n1=");
scanf("%d",&n1);
printf("enter the second number n2=");
scanf("%d",&n2);
printf("\n menu");
printf("\n 1 : addtion");
printf("\n 2 : subtraction");
printf("\n 3 :multiplication");
printf("\n 4 : divide");
printf("\n enter any option (1=4)");
scanf("%d",&option);
switch (option)
{
case 1:
add =n1+n2;
printf(" addtion of n1 & n2 is %d",add);
break;
case 2:
sub =n1-n2;
printf("subtarct of n1 & n2 is %d",sub);
break;
case 3:
mult =n1*n2;
printf("multiplation=%d",mult);
break;
case 4:
div=n1/n2;
printf("div=%d",div);
break;
default:
printf("inculid option....");
}
}
