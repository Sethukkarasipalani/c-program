# c-program
#include<stdio.h>
int main()
{
int num;
printf("enter a number");
scanf("%d",&num);
printf("octal equivalent:");
while(num!=0)
{
printf("%d",num%8);
num/=8;
}
printf("\n");
return 0;
}
