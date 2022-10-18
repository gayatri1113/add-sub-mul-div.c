//# add-sub-mul-div.c//
#include<stdio.h>
int main()
{
int a,b,add,sub,mul,div;
printf("enter first number");
scanf("%d",&a);
printf("enter second number");
scanf("%d",&b);
add=a+b;
sub=a-b;
mul=a*b;
div=a/b;
printf("\naddition=%d",add);
printf("\nsubtraction=%d",sub);
printf("\nmultiplication=%d",mul);
printf("\ndivision=%d",div);
return 0;
}
