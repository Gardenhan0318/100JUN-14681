# 100JUN-14681
STUDY
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>



int main(void)
{
	int x;
	int y;
	printf("x좌표는 ");
	scanf("%d", &x);
	
	printf("y좌표는 ");
	scanf("%d", &y);
	
	for (-1000 <= x && x <= 1000, -1000 <= y && y <= 1000)

		
    if (x > 0 && y > 0)
	{
		printf("점(x, y)의 사분면 번호 1");
	}

	if (x < 0 && y > 0)
	{
		printf("점 (x, y)의 사분면 번호 2");
	}

	if (x < 0 && y < 0)
	{
		printf("점 (x, y)의 사분면 번호 3");
	}

	if (x > 0 && y < 0)
	{
		printf("점 (x, y)의 사분면 번호 4");
	}

	return 0;

}
