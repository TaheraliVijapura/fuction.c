# fuction.c
#include <stdio.h>

	int add ()
{
	int a,b;
	printf("enter sum value:");
	scanf("%d %d",&a,&b);
	printf("sum = %d",a+b);
}

	int cube()
	{
		int a;
		printf("\nenter the cube value:");
		scanf("%d",&a);
		printf("cube = %d",a*a*a);
	}
	
	int mul ()
	{
		int a,b;
		printf("\n enter the mul value:");
		scanf("%d%d",&a,&b);
		printf("mul ans = %d",a*a);
	}
		int positive ()
		{
			int a;
			printf("\n enter the value:");
			scanf("%d",&a);
			if (0<a)
			{
				printf("\npositive number");
			}
			else
			{
				printf("\nnegative number");
			}
		}
		int max()
		{
			int a,b;
			printf("\nenter the number :");
			scanf("%d%d",&a,&b);
			if (a>b)
			{
				printf("a is maximum number %d",a);
			}
			else
			{
				printf(" b is maximum number %d",b);
			}
		}

main()
{
	add();
	cube();
	mul();
	positive();
	max();
}
