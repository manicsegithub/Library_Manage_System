# Library_Manage_System

#include<stdio.h>
#include<stdlib.h>

int main()
{
int days;
printf("Enter the Number of days: ");
scanf("%d",&days);
if(days>=1 && days<=5){
printf("\n Fine Amt is 5 Rupees");
}
if else(days>=6 && days<=10){
printf("\n Fine Amt is 10 Rupees");
}
if else(days>=11 && days<=15){
printf("\n Fine Amt is 15 Rupees");
}
else{
printf("\n Membership will be Cancelled");
}
return 0;
}
