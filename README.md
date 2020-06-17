# sums
akshita
#include<stdio.h>
int sum(int x){
	if (x==0)
		return 0;
	return(x%10+sum(x/10));
}
int main(){
	int i;
	printf("enter the number");
	scanf("%d",&i);
	int s=sum(i);
	printf("%d",s);
	return 0;
}
