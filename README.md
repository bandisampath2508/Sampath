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

//To convert days into months and days
#include<stdio.h>
int main()
{
int totaldays;
int months,days;
printf("Enter totaldays= ");
scanf("%d",&totaldays);
months=totaldays/30;
days=totaldays%30;
printf("months="%d/n",months);
printf("days="%d",days);
return 0;
}

//To convert days into years,months and days
#include<stdio.h>
int main()
{
int Totaldays;
int years,months,days;
printf("Enter Totaldays=");
scanf("%d",Totaldays);
years=Totaldays/365;
months=Totaldays%365;
days=Totaldays%30;
printf("Years=%d\n",years);
printf("Months=%d\n",months);
printf("Days=%d",days);
return 0;
}

//To find the grade of a student
#include<stdio.h>
int main()
{
int marks;
printf("Enter the marks= ");
if (marks<0||marks>100){
printf("Number is invaid");
}
else if (marks>=90){
printf("Grade=S");
}
else if (marks>=80){
printf("Grade=A");
}
else if (marks>=70){
printf("Grade=B);
}
else if (marks>=60){
printf("Grade=C");
}
else if (marks>=50){
printf("Grade=D");
}
else(marks<50){
printf("Fail");
{
return 0;
}

//Finding the greatest number
#include<stdio.h>
int main()
{
int c=10,b=22,a=9;
if (a>b){
if (a>c);
printf("%d",a);
else;
printf("%d",c);
}
else{
if (b>=c);
printf("%d",b);
else;
printf("%d",c);
}
return 0;
}

                                        //11-03-26//Wednesday

//To find biggest among three
#include<stdio.h>
int main()
{
scanf("%d%d%d",&num1,&num2,&num3);
if(num1>num2)&&(num1>num3)
printf("max=",num1);
}
else if(num2>num3){
printf("max="num2);
}
else{
printf("max=",num3);
}
return 0;
}

//To check whether the number is in the range 1 to 100
#include<stdio.h>
int main()
{
int num;
scanf("%d",&num);
if(num>=1&&num<=100){
printf("within range");
}
else{
printf("not in range");
}
return 0;
}

//To find the character in the range a to z
#include<studio.h>
int main()
{
char n;
scanf("%c",&n);
if(n>=a&&n<=z){
printf("within range");
}
else{
printf("not in range");
}
return 0;
}

//To increment a value
#include<stdio.h>
void main()
{
int x,i;
i=10;
x=++i;
printf("x:%d",x);
printf("i:%d",i);
}

//conditional operators
#include<stdio.h>
void main()
{
int max;
max=(a>b)?a:b;
printf("maximum number =%d\n",max);
}

//To find the days in week
#include<stdio.h>
int main()
{
int day;
scanf("%d",&day);
switch day;{
case 1:
printf("monday");
break;
case 2:
printf("tuesday");
break;
case 3:
printf("wednesday");
break;
case 4:
printf("thursday");
break;
case 5:
printf("friday");
break;
case 6:
printf("saturday");
break;
case 7:
printf("sunday");
break;
default:
printf("invalid"):
}
return 0;
}

//Program to break statement
#include<stdio.h>
int main()
{
int i;
for (i=1;i<=10;i++){
if(i==5)
break;
printf("%d\n",i);
}
return 0;
}

//Goto statement
#include<stdio.h>
int main()
{
int i=1;
start:
if(i<=5){
printf("%d\n",i);
i++;
goto start;
}
return 0;
}

//Continue statement
#include<stdio.h>
int main()
{
int i;
for (i=1;i<=10;i++){
if(i==5)
continue:
printf("%d\n",i);
}
return 0;
}

//To describe 1 to 10
#include<stdio.h>
void main()
{
int i=1;
while(i<=10)
{
printf("%d\n",i);
i++;
}
printf("end");
}

//To describe odd numbers from 1 to 10
#include<stdio.h>
void main()
{
int 1;
while(i<10);
if (i%2==1)
{
printf("%d\n",i);
i++;
}
printf("end");
}

//To describe even numbers
#include<stdio.h>
void main()
{
int i=1;
while(i<=10);
if(i%2==0){
printf("%d\n",i);
i++;
}
printf("end");
}

//To find the find 10 natural numbers
#include<stdio.h>
void main()
{
int i=1,sum=0;
while(i<=10)
{
sum=sum+i;
i++;
}
printf("sum=%d\n",sum);
printf("end");
}

//To find sum of odd numbers
#include<stdio.h>
void main()
{
int i=1,sum=0;
while(i<=10);
if(i%2==1)
{
sum=sum+i;
}
i++;
printf("sum=%d\n",sum);
printf("end");
}

//To find the sum of even numbers
#include<stdio.h>
void main()
{
int i=1,sum=0;
while(i<=10);
if(i%2==0)
{
sum=sum+i;
}
i++;
printf("sum=%d\n",sum);
printf("end");
}

//To find the factorial of a given number
#include<stdio.h>
void main()
{
int i=1,factorial=1;
while(i<=5)
{
factorial=factorial*i;
i++;
}
printf("factorial=%d\n",factorial);
printf("end");
}

//To print the Fabomacci series
#include<stdio.h>
void main()
{
int i=0,first=0,second=1,next;
while(i<=10)
{
printf("%d\n",first);
next=first+second;
first=second;
second=next;
i++;
}
}

//To print 1 to 10 in reverse order
#include<stdio.h>
void main()
{
int i=10;
while(i>=1)
{
printf("%d\n",i);
}
printf("end");
}

//To check the number whether it is in the range of 1 to 1000
#include<stdio.h>
int main()
{
int num;
scanf("%d",&num);
if(num>=1&&num<=1000){
printf("within range");
}
else{
printf("not in range");
}
return 0;
}

//To checkj the number in the range of 1 to 200
#include<stdio.h>
int  main()
{
int num;
scanf("%d",&num);
if(num>=1&num<=200){
printf("within range");
}
else{
printf("not in range");
}
return 0;
}

                                        //12-03-26//Thursday
//Programe to reverse an integer
#include<stdio.h>
void main()
{
int num,reversed=0;
printf("enter an integer:");
scanf("%d",&num);
while(num!=0){
int digit=num%10;
reversed=reversed*10+digit;
num=num/10;
}
printf("reversed number=%d\n",reversed);
}

//Programe to find given number is palindrome or not
#include<stdio.h>
void main()
{
int num,ori,rem,reversed=0;
scanf("%d",&num);
ori=num;
while(num!=0)
{
rem=num%10;
reversed=reversed*10+rem;
num=num/10;
}
if(ori==reversed)
printf("pal");
else
printf("not pal");
}

//Programe to check whether number is armstrong or not
#include<stdio.h>
void main()
{
int num,reversed=0;
scanf("%d",&num);
while(num!=0)
{
int digit=num%10;
reversed=reversed+digit*digit*digit;
num=num/10;
}
printf("an=%d",reversed);
}

//Programe to find sum of digits
#include<studio.h>
void main()
{
int num,digit,sum=0;
scanf("%d",&sum);
while(num!=0)
{
digit=num%10;
sum=sum+digit;
num=num/10;
}
printf("sum=%d",sum);
}

//To print a number is happy number
#include<stdio.h>
int main()
{
int n,o,digit,sum;
scanf("%d",&n);
o=n;
while(o!=1&&o!=4)
{
sum=0;
while(o>0)
{
digit=o%10;
sum=sum+digit*digit;
o=o/10;
}
o=sum;
}
if(o==1)
printf("%d id happy number",n);
else
printf("%d is not happy number",n);
return 0;
}

//To print number is automorphic 
#include<stdio.h>
int main()
{
int n,sq,o;
scanf("%d",&n);
sq=n*n;
o=n;
while(o>0)
{
if(o%10!=sq%10)
{
printf("not");
return 0;
}
o=o/10;
sq=sq/10;
}
printf("automorphic");
return 0;
}

//To print number is harshad number or not
#include<stdio.h>
void main()
{
int n,o,digit,sum=0;
scanf("%d",&n);
o=n;
while (n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
if(o%sum==0)
{
printf("harshad no");
}else{
printf("not");
}
}

//To print number is magic number or not
#include<stdio.h>
int main()
{
int n,o,digit,sum;
scanf("%d",&n);
o=n;
while(n>9)
{
sum=0;
while(n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
}
if(n==1)
printf("magic no");
else
printf("not");
return 0;
}

//To print even  number using for loop
#include<stdio.h>
void main()
{
for(int i=1;i<=10;i++)
{
if(i%2==0)
{
printf("%d\n",i);
}
}
}

//To print first n even numbers using for loop
#include<stdio.h>
void main()
{
int i,sum=0,n;
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if (i%2==0)
{
sum=sum+i;
}
}
printf("%d\n",i);
}

//To find factorial using for loop
#include<stdio.h>
void main()
{
int i,fact=1,n;
scanf("%d",&n);
for(i=1;i<=10;i++)
{
fact=fact*i;
}
printf("fact=%d\n",fact);
}

//To print multiplication table
#include<stdio.h>
void main()
{
int i,n,m;
scanf("%d",&n);
for(i=1;i<=10;i++)
{
m=n*i
}
printf("%dX%d=%d\n",i,n,m);
}

//To print factors of given number
#include<stdio.h>
void main()
{
int i,n;
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if (n%i==0)
printf("factors=%d\n",i);
}
}

//To find given number is perfect or not
#include<stdio.h>
void main()
{
int i,n,sum=0,t;
scanf("%d",&n);
for(i=1;i<=n;i++)
{
if(n%i==0)
{
sum=sum+i;
}
}
if(t==sum)
{
printf("%d is perfect",t);
}else{
printf("%d is not perfect",t);
}
}


