                                       //9-03-26//MONDAY
//To display our name.
#include<stdio.h>
int main()
{
printf("My name is Sampath");
printf("Welcome to SIMATS");
return 0;
}

//To find area of square
#include<stdio.h>
int main()
{
int side;
int area;
scanf("%d",&side);
area=side*side;
printf("%d",area);
return 0;
}

//To add two integer values
#include<stdio.h>
int main()
{
int a,b;
int c;
scanf("%d%d",&a,&b);
c=a+b;
printf("%d",c);
return 0;
}

//add two floating points
#include<stdio.h>
int main()
{
float a,b;
float sum;
scanf("%f%f",&a,&b);
sum=a+b;
printf("%f",sum);
return 0;
}

//To find the area of circle
#include<stdio.h>
int main()
{
float r;
float area;
scanf("%f",&r);
area=3.14*r*r;
printf("%f",area);
return 0;
}

//To find area and perimeter of rectangle
#include<stdio.h>
int main()
{
int l,b,area,perimeter;
scanf("%d%d",&l,&b);
area=l*b
perimter=2*(l+b);
printf("%d",area);
printf("%d",perimeter);
return 0;
}

//To find area of the traingle
#include<stdio.h>
int main()
{
float a,b,area;
scanf("%f%f",&a,&b);
area=0.5*a*b;
printf("%f",area);
return 0;
}

//Converting celsius to fahrenheit scale
#include<stdio.h>
int main()
{
float C,F;
scanf("%f",&C);
F=(C*9/5)+32;
printf("%f",F);
return 0:
}

//To convert Fahrenheit to celsius scale
#include<stdio.h>
int main()
{
float C,F;
scanf("%f",&F);
C=(F-32)*5/9;
printf("%f",C);
return 0;
}

//To find the Simple interest
#include<stdio.h>
int main()
{
float P,T,R,SI;
scanf("%f%f%f",&P,&T,&R);
SI=(P*T*R)/100;
printf("%f",SI);
return 0;
}

                                               //10-03-26//TUESDAY
//Find area of circle
#include<stdio.h>
void main()
{
const float pi=3.14;
float r=10,area;
area=pi*r*r;
printf("%.2f",area);
}

//Find area of circle using define
#include<stdio.h>
#define pi 3.14
void main()
{
int r;
float area;
scanf("%d",r);
area=pi*r*r;
printf("%.2f",area);
}

//Decimal to octal
#include<stdio.h>
void main()
{
int a=44;
printf("octal number =%o",a);
}

//Decimal to hexadecimal
#include<stdio.h>
void main()
{
int a=20;
printf("hexadecimal number is =%x",a);
}

//Octal to decimal
#include<stdio.h>
void main()
{
int a=040;
printf("decimal number is =%d",a);
}

//Hexadecimal to decimal
include<stdio.h>
void main()
{
int a=0x20;
printf("decimal number is =%d",a);
}

//Print the character and find ASCII
#include<stdio.h>
void main()
{
printf("ch=%c\n",c);
print("ch=%d hence an integer",ch);
printf("ch=%c\n",ch+1);
printf("ch=%d hence an integer\n",ch+1);
}

//Division
#include<stdio.h>
int main()
{
int a=3;
int =q,r;
q=a/2;
r=a%2;
printf("quotient =%d\n",q);
printf("remainder =%d",r);
return 0;
}

//Area of triangle
#include<stdio.h>
int main()
{
int b=3,h=3;
float area;
area=(1/2.0)*b*h;
printf("area=%.2f",area);
return 0;
}

// To swap two integers using third variable
#include<stdio.h>
int main()
{
int a=10,b=20,t;
printf("a=%d\tb=%d\n",a,b);
t=a;
a=b;
b=t;
printf("a=%d\tb=%d",a,b);
return 0;
}

//Swaping without using third variable
#include<stdio.h>
int main()
{
int a=10,b=20;
printf("a=%d\tb=%d\n",a,b);
a=b;
b=a/2;
printf("a=%d\tb=%d',a,b);
return;
}

//To display a number if it is negative
#include<stdio.h>
int main()
{
int number;
scanf("%d",&number);
if(number<0){
printf("you entered %d\n",number);
}
printf("The if statement is easy");
return 0;
}

//To find whether a integer is odd or even
#include<stdio.h>
int main()
{
int n;
printf("Enter the number= ");
scanf("%d",&number);
if (n%2==0){
printf("%d is even",n);
}
else{
printf("%d is odd",n);
}
return 0;
}

//Eligible to vote or not
#include<stdio.h>
int main()
{
int age;
printf("Enter the age =");
scanf("%d",&age);
if (age>18)
{
print("%d is eligible to vote",age);
}
else{
printf("%d is not elligible to vote",age);
}
return 0;
}

//To find a student pass or fail
#include<stdio.h>
int main()
{
int n;
printf("Enter the n= ");
scanf("%d",&n);
if (n>=35)
{
printf("%dis pass",n);
}
else
{
printf("%d is fail",n);
}
return 0;
}
