#include<stdio.h>  //  header file
 int main()       
 {
    int x,y;       // initializing variables

    printf("Enter the number : "); //print a number
    scanf("%d",&x); // input a number

    printf("Enter the number : ");
    scanf("%d",&y);  // input a number

    int sum = (x * y);  // product of two numbers
    printf("%d",sum);   // getting output
    return 0;
 }
