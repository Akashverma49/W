#include<stdio.h>
int main()
{
	int a,b,i;
	printf("Enter the first number :\n");
	scanf("%d",&a);
	printf("Enter the second number :\n");
	scanf("%d",&b);
	for(i=0;i<b;i++)
	a++;
	{
		printf("sum of two number is =  %d",a++);
	}
	return 0;
}
