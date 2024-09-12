# 01
#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
	srand(time(NULL));

		int num = rand()%100+1;
		int guess;
		while (1)
		{
			printf("please input the number\n");
			scanf_s("%d", &guess);
			if (guess < num)
			{
				printf("the number is small");
			}
			else if (guess > num)
			{
				printf("the munber is big");
			}
			else
			{
				printf("binggo");
				break;
			}
		}

	return 0;

