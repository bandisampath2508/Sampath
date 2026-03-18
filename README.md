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

//To find sum of n-natural numbers using for loop
#include<stdio.h>
void main()
{
int i,sum=0,n;
scanf("%d",&n);
for(i=1;i<=10;i++)
{
sum=sum+i;
}
printf("sum=%d\n",sum);
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

                                        //13-03-26//Friday
//To find the given number is prime or not
#include<stdio.h>
void main()
{
    int num,i,isPrime=1;
    printf("Enter the number: ");
    scanf("%d",&num);
    if (num<=1){
        isPrime=0;
    }
    else{
        for(i=2;i<=num/2;i++){
            if(num%i==0){
                isPrime=0;
                break;
            }
        }
    }
    if(isPrime){
        printf("%d is a prime number");
    }
    else{
        printf("%d is not a prime number");
    }
}

//To find the prime numbers in a given set of numbers
#include<stdio.h>
int main()
{
    int num,i,j,isPrime;
    printf("Enter the number: ");
    scanf("%d",&num);
    for(i=2;i<=num;i++){
        isPrime=1;
        for(j=2;j<=i/2;j++){
            if(i%j==0){
                isPrime=0;
                break;
            }
        }
        if(isPrime){
            printf("%d is a Prime number.\n",i);
        }
    }
    return 0;
}

//Program to find the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for (i=1;i<=5;i++)
    {
        for (j=1;j<=5;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

//To print the hallow pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n;j++){
            if(i==1||i==n||j==1||j==n){
                printf("*");
            }
            else{
                printf(" ");
             }
        }
        printf("\n");
         }
         return 0;
         }

//To print the staircas of stars
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for (i=1;i<=n;i++){
        for (j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("%d",i);
        }
        printf("\n");
    }
    return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for (i=5;i.=1;i--){
for (j=1;j<=i;j++){
printf("*");
}
printf("\n");
}
return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for(i=5;i>=1;i--){
for(j=1;j<=i;j++){
printf("%d",j);
}
printf("\n");
}return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    for (i=n-1;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
    

}

//To print the given pattern
#include<stdio.h>
int main()
{
    int i,j,s;
    
  for(i=1;i<=5;i++){
        for(s=1;s<=5-i;s++){
            printf(" ");
        }
        for(j=1;j<=i;j++){
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}

//To print the given program
#include<stdio.h>
void main()
{
    int i,j,n,num;
    num=1;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("%d",num);
            num++;
        }
        printf("\n");
    }
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for (i=1;i<=n;i++){
for (j=1;j<=n-j;j++){
printf(" ");
}
for(j=1;j<=(2*i-1);j++){
if(i==1||i==n||j==1||j==(2*i-1)){
printf("*");
}
else{
printf(" ");
}
printf(" ");
}
printf("\n");
}
return 0;
}

//To print the palindrome number
#include <stdio.h>
int main()
{
int n, rev = 0, r, temp;
printf("Enter a number: ");
scanf("%d", &n);
temp = n;
while(n > 0)
{
r = n % 10;
rev = rev * 10 + r;
n = n / 10;
}
if(temp == rev)
printf("Palindrome number");
else
printf("Not a palindrome");
return 0;
}

                                      //14-03-26//Saturday

//To find lcm of lcm of given number
#include<stdio.h>
int main()
{
int a,b,lcm;
scanf("%d%d",&a,&b);
int max=(a>b)?a:b;
while(1){
if (max%a==0 && max%b==0){
lcm=max;
break;
}
max++;
}
printf("lcm=%d",lcm);
return 0;
}

//To print gcd of givrn number
#include<stdio.h>
int main()
{
int a,b,gcd;
scanf("%d%d",&a&b);
for(int i=1;i<=a &&i<=b;i++){
if(a%i==0 && b%i==0)
gcd=i;
}
printf("gcd=%d",gcd);
return 0;
}

//To print the pattern given below
#include<stdio.h>
void main()
{
int i,j,n;
scanf("%d",&n);
for(i=n;i>=1;i--){
for(j=1;j<=i;j++){
printf("%d",i);
}
printf("\n");
}
}

//To print the given pattern
#include<stdio.h>
void main()
{
int i,j,n;
scanf("%d",&n);
for(i=n;i>=1;i--){
for(j=1;j<=i;j++){
printf("%d",j);
}
printf("\n");
}
}

//To print given number is perfect square or not
#include<stdio.h>
include<math.h>
int maint()
{
int n;
scanf("%d",&n);
int r=sqrt(n);
if(r*r==n)
printf("it is perfect square");
else
printf("not perfect square");
return 0;
}

//Display numbers using array
#include<stdio.h>
void main()
{
int i,a[5],n;
scanf("%d",&n)
for(i=0;i<n;++i)
{
scanf("%d",&a[i]);
}
printf("displaying numbers:\n);
for(int i=0;i<n;++i)
{
printf("%d\n",a[i]);
}
}

//Write program to display array values in reverse order
#include<stdio.h>
void main()
{
int i,a[5],n;
scanf("%d",&n);
for(i=0;i<n;++i)
{
scanf("%d",&a[i]);
}
printf("displaying integers:\n");
for(int i=n-1;i>=0;i--);
{
printf("%d\n",a[i]);
}
}

//Program to find sum of array elements
#include<stdio.h>
void main()
{
int i,a[5],sum=0;
scanf("%d",&n);
for(i=0;i<=n;i++)
{
scanf("%d",&a[i]);}
printf("displaying integers:");
for(i=0;i<n;i++)
sum=sum+a[i]
{
printf("%d",sum);
}
}

//To find average of given array elements
#include<stdio.h>
void main()
{
int i,a[5],sum=0;
float avg;
scanf("%d",&n);
for(i=0;i<=n;i++)
{
scanf("%d",&a[i]);
printf("displaying elements");
for(i=0;i<=n;i++)
sum=(sum+a[i]);
avg=(sum)/n;
printf("avg %d=",avg);
}
}

//To print largest element in array
#include<stdio.h>
void main()
{
int n,i,max;
scanf("%d",&n);
int arr[n];
printf("enter elements:\n");
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
max=arr[0];
for(i=1;i<n;i++)
{
if(arr[i]>max){
max=arr[i];
}
}
printf("largest number=%d",max);
return 0;
}

//To search the given element in an array
#include<stdio.h>
int main()
{
int arr[100],n,i,key,found=0;
printf("enter number of elements: ");
scanf("%d",&n);
printf("enter the elements:\n");
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
printf("enter the element to search: ");
scanf('%d",&key);
for(i=0;i<n;i++)
{
if(arr[i]==key)
{
printf("element found at position %d",i+1);
found=1;
break;
}
}
if(found==0)
{
printf("element not found");
}
return 0;
}

//To check whether number is composite or not
#include<stdio.h>
int main()
{
int n,i,count=0;
printf("enter a number: ");
scanf("%d",&n);
for(i=1;i<=n;i+=)
{
if(n%i==0)
count++;
}
if(count>2)
printf("composite number");
else
printf("not a composite number");
return 0;
}

                                           //16-03-26//Monday
//Read string from user
#include<stdio.h>
int main()
{
char name[20];
printf("enter name:");
scanf("%s",name);
printf("your name is %s.",name);
return 0;
}

//To find length of string
#include<stdio.h>
int main()
{
char str[50]="SAMPATH";
int len=strlen(str);
printf("length of string: %d",len);
return 0;
}

// To convert  given  string into Lowercase,Uppercase,Stringreverse
#include<stdio.h>
#include<string.h>
int main()
{
char str[50]="SAMPATH";
char str1[50]="kalangi sathish";
char str2[50]="SAMPATH";
strlwr(str);
strupr(str1);
strrev(str2);
printf("in lower case:%s\n",str);
printf("in upper case:%s\n",str1);
printf("in reverse:%s,str2);
return 0;
}

//To compare two strings
#include<stdio.h>
#include<string.h>
int main()
{
char s1[20]="SAMPATH";
char s2[20]="HARI";
if(strcmp(s1,s2)==0)
{
printf("string 1 and 2 are equal):
}
else
{
printf("string 1 and 2 are not equal);
}
return 0;
}

//String concatenation and string copy
#include<stdio.h>
#include<string.h>
int main()
{
char s1[50]="SAMPATH";
char s2[50]="ARISTOTLE";
printf("output string after concatenation:%s\n",s1);
strcpy(s1,s2);
printf("output string after string copy:%s;s1);
return 0;
}

//Program to find length of string without using string function
#include<stdio.h>
int main()
{
char str[50]="SAMPATH"
get s[str];
int i=0,len=0;
while (str[i]!='\0'){
len++;
i++;
}
printf("length of string:%d",len);
return 0;
}

//Program to count number of words in given statement
#include<stdio.h>
int main()
{
char str[100]="B SAMPATH";
int i,count=1;
for(i=0;str[i]!='\0';i++)
{
if(str[i]==" ")
{
count++;
}
}
printf("number of words=%d",count);
return 0;
}

//Programe to concatinate two string without using string concept
#include<stdio.h>
int main()
{
char str1[100]="SAMAPATH";
char str2[20]="SAI";
int i=0,j=0;
while(str1[i]!='\0'){
i++;
}
while(str2[j]!='\0'){
str1[i]=str2[j];
i++;
j++;
}
str1[i]='\0';
printf("concatenated string:%s",str1);
return 0;
}

//Program to convert uppercase to lowercase without using string function
#include<stdio.h>
int main()
{
char str[20]="sampath";
int i=0;
while (str[i]!='\0'){
if(str[i]>'a' && str[i]<'z'){
str[i]=str[i]-32;
}
i++;
}
printf("uppercase string:%s",str);
return 0;
}

//Programe to convert uppercase to lowercase without using string function
#include<stdio.h>
int main()
{
char str[20]="SAMPATH";
int i=0;
while(str[i]!='\0');
if(str[i]>'A' && str[i]<'Z'){
str[i]=str[i]+32;
}
i++;
}
printf("lowercase string:%s",str);
return 0;
}

//Program to reverse a string without usinf string function
#include<stdio.h>
int main()
{
char str[20]="SAMPATH";
char rev[10];
int i,j=0,l;
l=strlen(str);
for(i=l-1;i>=0;i--){
rev[j]=str[i];
j++;
}
rev[j]='\0';
printf("reversed string:%s",rev);
return 0;
}

//To find given string is palindrome or not
#include<stdio.h>
#include<string.h>
void main()
{
char str[10]="malayalam";
int i,length,flag=0;
length=strlen(str);
for(i=0;i<length;i++){
if(str[i]!=str[length-i-1]){
flag=1;
break;
}
}
if (flag==1){
printf("%s is not palindrome",str);
else
printf("%s is a palindrome",str)
}
}

//To count number of vowels and consinants in sentence
#include<stdio.h>
void main()
{
char sentence[30]="sampath";
int i,vowels=0,consonants=0;
char ch;
for(i=0;sentence[i]!='\0';i=++){
ch=sentence[i];
if(ch>='a' && ch<='z'){
if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u')
vowels++;
else
consonants;
}
}
printf("vowels:%d\n",vowels);
printf("consonants:%d\n",consonants);
}

                                   //18-03-26//Wednesday
//Print largest element in array
#include <stdio.h>
int main()
{
  int n,i;
  int a[100];
  int max;
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  max=a[0];
  for (i=1;i<n;i++)
  {
    if (a[i]>max)
    max=a[i];
  }
  printf("%d",max);
  return 0;
}

//To print min and max element in array
#include <stdio.h>
int main()
{
  int i,n,a[100],min,max;
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  min=max=a[0];
  for (i=1;i<n;i++)
  {
    if(a[i]<min)
    min=a[i];
    if(a[i]>max)
    max=a[i];
  }
  printf("%d\n",min);
  printf("%d",max);
  return 0;
}

//To reverse an array
#include <stdio.h>
int main()
{
  int n,i,a[100];
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  for (i=0;i<n/2;i++)
  {
    int temp=a[i];
    a[i]=a[n-i-1];
    a[n-i-1]=temp;
  }
  for(i=0;i<n;i++)
  {
    printf("%d\n",a[i]);
  }
  return 0;
}

//To print duplicate element in array
#include <stdio.h>
int main()
{
  int n,i,j,a[100];
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  for (i=0;i<n;i++)
  {
    for (j=i+1;j<n;j++)
    {
      if (a[i]==a[j])
      {
        printf("%d\n",a[i]);
        break;
      }
    }
  }
  return 0;
}

//To execute matrix addition 
#include <stdio.h>
int main()
{
  int a[10][10],b[10][10],sum[10][10];
  int r,c,i,j;
  scanf("%d",&r);
  scanf("%d",&c);
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      scanf("%d",&a[i][j]);
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      scanf("%d",&b[i][j]);
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      sum[i][j]=a[i][j]+b[i][j];
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      printf("%d ",sum[i][j]);
    }
    printf("\n");
  }
  return 0;
}

//String uppercase,lowercase,reverse
#include <stdio.h>
#include <string.h>
  int main()
  {
    char str[20]="SAMPATH";
    char str1[20]="sampath";
    char str2[20]="SAMPATH";
    strlwr(str);
    strupr(str1);
    strrev(str2);
    printf("%s\n",str);
    printf("%s\n",str1);
    printf("%s",str2);
    return 0;
  }

//Employee structure
#include <stdio.h>
struct employee
{
  char name[50];
  int empid;
  float salary;
};
int main()
{
  struct employee emp;
  scanf("%s",&emp.name);
  scanf("%d",&emp.empid);
  scanf("%f",&emp.salary);
  printf("%s\n",emp.name);
  printf("%d\n",emp.empid);
  printf("%.2f",emp.salary);
  return 0;
}

//Student structure
#include <stdio.h>
struct student
{
    char name[20];
    int rollno;
    float m1,m2,m3;
};
int main()
{
    struct student s;
    int avg=0;
    scanf("%s",s.name);
    scanf("%d",&s.rollno);
    scanf("%f%f%f",&s.m1,&s.m2,&s.m3);
    sum=(s.m1+s.m2+s.m3)/3.0;
    printf("%s\n",s.name);
    printf("%d\n",s.rollno);
    printf("%.2f",avg);
    return 0;
}













