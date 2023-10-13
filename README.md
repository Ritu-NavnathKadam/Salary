# Salary
#include<stdio.h>
void main()
{
float s,fs,ts,rent,da,tax;
printf("Enter basic salary");
scanf("%f",&s);
rent=s*0.1;
da=s*0.3;
ts=s+rent+da;
printf("The salary with allowance is=%f\n",ts);
tax=s*0.05;        
fs=(s+rent+da)-tax;
printf("The final salary with tax is=%f\n",fs);



}
