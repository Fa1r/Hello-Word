# Hello-Word
2017/8/29
#include <stdio.h>
#include <stdlib.h>
int main()
{
	int a,b,c;
    b=0;
    scanf("%d",&a);
    for(c=2;c<=a-1;c++)
{
	if(a%c==0)
{	
    b=1;
    printf("%d",c);
}
}
	if(b==0)
    printf("质数");
    else
    printf("合数");

	system("pause");
	return 0;
}
