# -
c语言基础
#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>


/*
int main(void)
{
	
	int a, b, c;
	a = 0;
	b = 10;
	c = 20;
	printf("%d,%d,%d\n",a,b,c);


		return 0;
}

*/

/*
int main(void)
{
	char a=0, b=0, c=0;
	a = 45;
	b = a++;
	c = a;
	printf("a:%d,b:%d,c:%d",a, b, c);


	return 0;
}

*/
/*
int main(void)
{

	unsigned char height = 170;
	height = 170;

	printf("%d\n",height);

	return 0;
}*/


/*
int main(void)

{ 
	float a = 0;
	a = 3;
	3 % 2;
	//printf("%f\n",a/2);
	printf("%f\n", 2 % a);
	return 0;
}

*/
/*
int main(void)
{ 
	int a = 5;
	a++;

	printf("%d\n", a++);
	printf("%d\n", a);
	return 0;
}
*/

/*
int main(void)

{
	char age = 0;
	age = 22;
	--age;
	printf("%d\n", age);
	printf("%d\n", --age);
	return 0;
}
*/
/*
int main(void)
{
	char a = 0;
	char b = 0;
	char c = 0;

	a = 1;
	b = 2;
	c = 3;

	printf("%d\n", a<c && ++b==c);
	return 0;
}
*/
/*
int main(void)
{
	int score = 0;
	score = 30;
	printf("%d\n", score<60 && score>0);
	printf("%d\n", score >= 60);
	return 0;
}
*/
/*
int main(void)
{

	int a = 0;
	a = 10;
    printf("%d\n", sizeof(a));
	return 0;
}
*/
/*
int main(void)

{
	float a = 7.5, d = 3.5;
	int b = 2, c = 0;
	c = a*b;
	printf("%d\n", c);
	c = (int)a*b;
	printf("%d\n", c);
	c = (int)(a*b);
	printf("%d\n", c);
	c = a*b*d;
	printf("%d\n", c);
	c = (int)a*b*d;
	printf("%d\n", c);
	c = (int)(a*b*d);
	printf("%d\n", c);
	c = (int)a*b*(int)d;
	printf("%d\n", c);
	return 0;
}*/

/*
int main(void)
{ 
	int a = 0;
	int b = 0;
	int max = 0;
	printf("请输入两个数值：\n");
	scanf_s("%d,%d", &a, &b);
	max = a;
	if (max > b)
	{
		printf("max:%d", a);

	}
	return 0;
}
*/

int main(void)
{
	int a = 0;
	
	printf("请输入一个数值：\n");
	scanf("%d", &a);
	if (a%2 != 0)
	{
		printf("%d是奇数",a);
	}
	return 0;
}
