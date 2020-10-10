 #include<stdio.h>
 int main()
{
	int a,b;
	printf("enter the two values to swap\n ");
	scanf("%d  %d",&a,&b);
	printf("before swapping a=%d and b=%D\n,a,b");
	
	a=a+b;
	b=a-b;
	a=a-b;
	
	printf("after swapping a=%d and b=%D",&a,&b ");
	return 0;
}		
