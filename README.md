# positive-or-negative-number

#include<stdio.h>
int main()
{
double number;
printf("enter the number");
scanf("%d",&number);
if(number<0.0)
printf("entered number is Negative");
else if(number>0.0)
printf("entered number is positive");
else
printf("entered number is0.0);
return 0;
}
