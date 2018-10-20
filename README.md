# Array
#include<stdio.h>
#include<conio.h>
int main () 
{
	int score[7]={10,11,12,13,14,15,16};
	int answer[7];
	int count,sum=0;
	float avg;
	for(count=0;count<=7;count++)
	{
		sum+=score[count];
	}
	avg=sum/7;
	printf("%d \n",sum);
	printf("%d \n",avg);
	printf("\n");
	for(count=0;count<7;count++)
	{
		answer[7]=(score[count]-avg)*(score[count]-avg);
		printf("\n %d \n", answer[7]);
		printf("\n");
	}
	return 0;
}
