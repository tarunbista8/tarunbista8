#include<stdio.h>
#include<conio.h>
int main()
{
	int num, i ;
	long fact = 1;
	printf ("Enter a number whose factorial is to be calculated :") ;
	scanf ("%d",&num) ;
	for (i=1;i<=num;i++)
	{
		fact*= i ; /* fact = fact*i */
	}
	printf ("The factorical is : %d", fact ) ;
}
