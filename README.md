#include <stdio.h>
int main(){
	float mid,final,q1,q2,lab,sit;
	scanf("%f%f%f%f%f%f",&mid,&final,&q1,&q2,&lab,&sit);
	printf("%10s=%8.2f\n%10s=%8.2f\n","Mid",(mid*30)/100,"Final",(final*35)/120);
	printf("%10s=%8.2f\n%10s=%8.2f\n","Q1",(q1*12)/60,"Q2",(q2*13)/60);
	printf("%10s=%8.2f\n%10s=%8.2f\n","Lab",(lab*5)/16,"Sit",(sit*5)/16);
	float sum;
	sum=(mid*30)/100 + (final*35)/120 + (q1*12)/60 + (q2*13)/60 + (lab*5)/16  +(sit*5)/16; 
	printf("%3s%5.2f%3s","***",sum,"***");
}
