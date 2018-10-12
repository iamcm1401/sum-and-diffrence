# sum-and-diffrence
#include<stdio.h>
int main()
{
int int1,int2,s1,s2;
float float1,float2,s3,s4;

scanf("%d%d",&int1,&int2);
scanf("%f%f",&float1,&float2);
s1=int1+int2;
s2=int1-int2;
s3=float1+float2;
s4=float1-float2;
printf("%d %d",s1,s2);
printf("\n");
printf("%.1f %.1f",s3,s4);

return 0;
}
    
