# LCM_of_Numbers-
Created by Abdulrahim Mulla

//LCM
#include<stdio.h>
#include<stdlib.h>
int main()

{
	int n1,n2,max_num;
	printf("Enter the two numbers : \n");
	scanf("%d %d",&n1,&n2);
	
	max_num = (n1>n2)?n1:n2;
	
	while(1)
		{
			if(max_num%n1==0 && max_num%n2==0)
			{
				printf("LCM of %d and %d is %d",n1,n2,max_num);
				break;
			}
			++max_num;
		}
		return 0;
	
}
