# Program-to-enter-a-decimal-number-calculate-and-display-binary-equivalent
#include<stdio.h>
void main()
{
int num,bin_eq[50],i;
printf(" enter a number :");
scanf("%d",&num);
for(i=0;num>0;i++)
{
bin_eq[i]=num%2;
num=num/2;
}
printf("\n binary equivalent of the given number is");
for(i=i-1;i>=0;i--)
{
printf("%d",bin_eq[i]);
}
}
