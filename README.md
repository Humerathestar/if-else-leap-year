#include<stdio.h>
int main(){
    int year;
    printf("enter a year");
    scanf("%d",&year);
    
    if(year%4==0){
        printf("is a leap year");}
        else{
            printf(" is not a leap year");}
        return 0;}
