# PROGRAMMING FOR PROBLEM SOLVING ESC-18105
NAME-ANURAG PANDEY
ROLL NO-1915010
BRANCH-COMPUTER SCIENCE
SECTION-CSE(A1)

LOGO
DEPARTMENT OF COMPUTER SCIENCE ENGINEERING
GURU NANAK DEV ENGINEERING COLLEGE,LUDHIANA
PROGRAM No 1:-PROGRAM TO PRINT WELCOME MESSAGE

  #include <stdio.h>  
  int main()
  {
      puts("Welcome To Budding Engineers");
  } 

OUTPUT

Welcome To Budding Engineers 

PROGRAM No 2:-PROGRAM TO PRINT THE ADDRESS

#include <stdio.h>  
int main()  
{
    puts("Principal\nPanth Rattan Shiri Gurcharan Singh Tohra Complex\nGuru Nanak Dev Engineering College\nGill Park\nLudhiana -       141006\nIndia");  
}  

OUTPUT

 Principal  
 Panth Rattan Shiri Gurcharan Singh Tohra Complex  
 Guru Nanak Dev Engineering College  
 Gill Park  
 Ludhiana - 141006  
 India  

PROGRAM No 3:-PROGRAM TO FIND THE SUM OF TWO NUMBERS

#include <stdio.h>
int main()
{
        int a,b,c;  
        printf("enter the numbers");  
        scanf("%d %d",&a,&b);                            
        c=a+b;
        printf("sum of numbers is %d\n",c);  
        return 0;  
}

OUTPUT

 enter the numbers 13
 12
 sum of numbers is 25

PROGRAM No 4:-PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHIET

#include <stdio.h>
void main()
{
float f,c;
printf("enter temperature ");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("temp in celcius is %.2f\n",c);
}

OUTPUT

enter temperature 98
temp in celcius is 36.67

PROGRAM No 5:-PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE

#include <stdio.h>
void main()
{
float diameter, perimeter, area;
printf("enter diameter");
scanf("%f", &diameter);
perimeter = 22/7 * diameter;
area = perimeter * diameter / 4.0;
printf("\n\nDia: %.2f\nPerimeter: %.2f\nArea: %.2f\n\n",diameter, perimeter, area);
}

OUTPUT

enter diameter 14
Dia: 14.00
Perimeter: 42.00
Area: 147.00

PROGRAM No 6:-PROGRAMM TO SWAP TWO NUMBERS WITHOUT USING 3rd VARIABLE

#include <stdio.h>
void main()
{
  int a,b;
  printf(" enter number");
  scanf("%d",&a);
  b=a;
  a=a%10;
  b=b/10;
  b=a*10+b;
  printf("reverse no is %d",b);
  }

OUTPUT

enter number 32  
reverse no is 23  

PROGRAM No 7:-PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD

#include <stdio.h>
void main()
{
        int a;
        printf("enter number: ");
        scanf("%d",&a);
        if (a%2==0)
        printf("%d is even",a);
        else
        printf("%d is odd",a);
}

OUTPUT

enter number: 15
15 is odd

PROGRAM No 8:-PROGRAM TO FIND FACTORIAL OF A NUMBER

#include <stdio.h>
void main()
{
        int a,n=1,i;
        printf("enter i");
        scanf("%d",&i);
        for(a=1;a<=i;a++)
        n=n*a;
        printf("factorial of a is %d \n",n);
}

OUTPUT

enter i 5  
factorial of a is 120   

PROGRAM No 9:-PROGRAM TO REVERSE A NUMBER

#include <stdio.h>
void main()
{
        int a,n,r=0;
        printf("enter number");
        scanf("%d",&n);
        while(n>0)
        {
                a=n%10;
                r=r*10+a;
                n=n/10;
        }
        printf("reverse no is %d \n",r);
}

OUTPUT

enter number 321  
reverse no is 123

PROGRAM No 10:-PROGRAM TO PRINT FIZZBUZZ

#include <stdio.h>
int main()
{
        int a,i;
        printf("enter number ");
        scanf("%d",&a);
        for(i=1;i<=a;i++)
        {
                if(i%15==0)
                printf("fizzbuzz\n");
                else if(i%5==0)
                printf("buzz\n");
                else if(i%3==0)
                printf("fizz\n");
                else
                printf("%d\n",i);
        }
        return 0;
}

OUTPUT

enter number 30
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
17
fizz
19
buzz
fizz
22
23
fizz
buzz
26
fizz
28
29
fizzbuzz

PROGRAM No 11:-PROGRAM TO PRINT DAYS OF A WEEK

#include <stdio.h>
void main()
{
        char ch;
        printf("enter s for sunday\n m for monday\n t for tuesday\n w for wednesday\n h for thursday\n f for friday\n a for saturday\n");
        scanf(" %s",&ch);
        switch (ch)
        {
                case 's':
                printf("sunday");
                break;
                case 'm':
                printf("monday");
                break;
                case 't':
                printf("tuesday");
                break;
                case 'w':
                printf("wednesday");
                break;
                case 'h':
                printf("thrusday");
                break;
                case 'f':
                printf("friday");
                break;
                case 'a':
                printf("saturday");
                break;
                default :
                printf("wrong input");
                break;
                case 'w':
                printf("wednesday");
                break;
                case 'h':
                printf("thrusday");
                break;
                case 'f':
                printf("friday");
                break;
                case 'a':
                printf("saturday");
                break;
                default :
                printf("wrong input");
                break;
        }
}

OUTPUT

enter s for sunday
 m for monday
 t for tuesday
 w for wednesday
 h for thursday
 f for friday
 a for saturday
a
saturday

PROGRAM No 12:-PROGRAM TO MAKE A CALCULATOR

#include <stdio.h>
int main()
{
        int a,b,c;
        char cal;
        printf("enter a and b and operator");
        scanf("%d %d %c",&a,&b,&cal);
        switch (cal)
        {
                case '+':
                c=a+b;
                printf("%d",c);
                break;
                case '-':
                c=a-b;
                printf("%d",c);
                break;
                case '*':
                c=a*b;
                printf("%d",c);
                break;
                case '/':
                c=a/b;
                printf("%d",c);
        }
        printf("\n");
}

OUTPUT

enter a and b and operator 12  
15  
+  
27

PROGRAM No 13:-PROGRAM TO CHECK WHETHER A YEAR IS LEAP YEAR OR NOT

#include <stdio.h>
int main()
{
        int year;
        printf("enter year ");
        scanf("%d",&year);
        if (year%4==0)
        printf("%d is a leap year\n",year);
        else
        printf("%d is not a leap year\n",year);
        return 0;
}

OUTPUT

enter year 2019
2019 is not a leap year

PROGRAM No 14:-PROGRAM TO CHECK WHETHER A NUMBER IS PRIME OR NOT

#include <stdio.h>
void main()
{
int x=0,i,n;
printf("enter number ");
scanf("%d",&i);
for(n=1;n<=i;n++)
{
if(i%n==0)
x++;
}
if(x==2)
{
printf("no is prime\n");
}
else
{
printf("no is not prime\n");
}
}

OUTPUT

enter number 31
no is prime

PROGRAM No 15:-PROGRAM TO CHEACK WHETHER A NUMBER IS PALLINDROME OR NOT

#include <stdio.h>
void main()
{
        int i,a,n,r=0;
        printf("enter number");
        scanf("%d",&n);
        i=n;
        while(n>0)
        {
                a=n%10;
                r=r*10+a;
                n=n/10;
        }
        printf("reverse no is %d \n",r);
        if(i==r)
        printf("no is pallindrome");
        else
        printf("no is not pallindrome");
}

OUTPUT

enter number 121
reverse no is 121
no is pallindrome

PROGRAM No 16:-PROGRAM TO PRINT FIBONACCI SERIES

#include <stdio.h>
int main()
{
        int a=1,b=1,s,i;
        printf("enter i");
        scanf("%d",&i);
        printf(" %d %d ",a,b);
        for(a=1;a<=i;)
        {
                s=a+b;
                printf("%d ",s);
                b=a;
                a=s;
        }
        return 0;
}

OUTPUT

enter i 20
1 1 2 3 5 8 13 21  

PROGRAM No 17:-PROGRAM TO ENTER AND PRINT 10 ELEMENTS USING 1-D ARRAY

#include <stdio.h>
int main()
{
        char name[10];
        int marks;
        int i;
        for (i=0;i<10;i++)
        {
                printf("enter name ");
                scanf("%s",&name);
                printf("enter marks ");
                scanf("%d",&marks);
        }
}

OUTPUT

enter name a 
enter marks 1
enter name b
enter marks 2
enter name c
enter marks 3
enter name d
enter marks 4
enter name e
enter marks 5
enter name f
enter marks 6
enter name g
enter marks 7
enter name h
enter marks 8
enter name i
enter marks 9
enter name j
enter marks 10

PROGRAM No 18:-PROGRAM TO PRINT A TWO MATRIX

#include<stdio.h>
int main()
{
int a[3][3],b[3][3],i,j;
printf("enter matrix a");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
printf("matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",a[i][j]);
printf("\n");
}
printf("\n");
printf("matrix b\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",b[i][j]);
printf("\n");
}
printf("\n");
return 0;
}

OUTPUT

  enter matrix a
1
2
3
4
5
6
7
8
9
enter matrix b
1
2
3
4
5
6
7
8
9
matrix a
1 2 3 
4 5 6 
7 8 9 

matrix b
1 2 3 
4 5 6 
7 8 9 

PROGRAM No 19:-PROGRAM TO ADD TWO MATRIX

#include <stdio.h>
int main()                                                                
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[i][j]=a[i][j]+b[i][j];
}
printf("\n");
printf("sum of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",c[i][j]);
printf("\n");
}
printf("\n");
}

OUTPUT

enter matrix a
1
2
3
4
5
6
7
8
9
enter matrix b
1
2
3
4
5
6
7
8
9

sum of matrix
2 4 6 
8 10 12 
14 16 18 

PROGRAM No 20:-PROGRAM TO TRANSPOSE A MATRIX

#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)                                                         
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",a[i][j]);
printf("\n");
}
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
b[j][i]=a[i][j];
}
printf("\n");
printf("transpose of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",b[i][j]);
printf("\n");
}
printf("\n");
return 0;
}

OUTPUT

enter matrix a
1
2
3
4
5
6
7
8
9
matrix a
1 2 3 
4 5 6 
7 8 9 

transpose of matrix
1 4 7 
2 5 8 
3 6 9

PROGRAM No 21:-PROGRAM TO SUBTRACT TWO MATRIX

#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)                                                        
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[i][j]=a[i][j]-b[i][j];
}
printf("\n");
printf("subtraction of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",c[i][j]);
printf("\n");
}
printf("\n");
return 0;
}

OUTPUT

enter matrix a
1
0
0
0
1
0
0
0
1
enter matrix b
1
0
0
0
1
0 
0
0
1

subtraction of matrix
0 0 0 
0 0 0 
0 0 0

PROGRAM No 22:- PROGRAM TO MULTIPLY TWO MATRIX

#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j,k,sum=0;
printf("enter matrix a\n");
for(i=0;i<=2;i++)                                        
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
{
for(k=0;k<=2;k++)
{
sum=sum+a[i][k]*b[k][j];
}
printf("\n");
c[i][j]=sum;
sum=0;
}
}
printf("multiplicationof matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf(" %d ",c[i][j]);
printf("\n");
}
printf("\n");
}

OUTPUT

enter matrix a
1
2
3
4
5
6
7
8
9
enter matrix b
1
2
3
4
5
6
7
8
9
multiplicationof matrix
 30  36  42 
 66  81  96 
 102  126  150 

PROGRAM No 23:-PROGRAM TO SQUARE A NUMBER USING FUNCTIONS

#include <stdio.h>
int square(int );
void main()
{
       int a,res;
       printf("enter number ");
       scanf("%d",&a);
       res=square(a);
       printf("square is %d\n",res);
}
int square(int a)
{
       int res;
       res=a*a;
       return res;
}

OUTPUT

enter number 15
square is 225

PROGRAM No 24:-PROGRAM TO SWAP A NUMBER BY CALLING FUNCTION BY VALUE

#include <stdio.h>
int swap(int num1,int num2);
void main()
{       
        int a,b,c;
        printf("enter the numbers a and b ");
        scanf("%d %d",&a,&b);
        printf("numbers before swap are %d and %d\n",a,b);
        c=swap(a,b);
        printf(" numbers after swap are %d and %d\n",a,b);
}
int swap(int num1,int num2)
{
        int c;
        c=num1;
        num1=num2;
        num2=c;
}

OUTPUT

enter the numbers a and b 12
13
numbers before swap are 12 and 13
numbers after swap are 12 and 13

PROGRAM No 25:-PROGRAM TO SWAP TWO NUMBERS BY CALLING FUNCTION BY REFRENCE

#include <stdio.h>
int swap(int *num1,int *num2);
void main()
{      
        int a,b,c;
        printf("enter the numbers a and b ");
        scanf("%d %d",&a,&b);
        printf("numbers before swap are %d and %d\n",a,b);
        c=swap(&a,&b);
        printf(" numbers after swap are %d and %d\n",a,b);
}
int swap(int *num1,int *num2)
{
        int c;
        c=*num1;
        *num1=*num2;
        *num2=c;
}

OUTPUT

enter the numbers a and b 12
13
numbers before swap are 12 and 13
numbers after swap are 13 and 12

PROGRAM No 26:-PROGRAM TO FIND FACTORIAL USINF RECURSION

#include <stdio.h>
int factorial(int);
int main()
{
        int n,f;
        printf("enter the number ");
        scanf("%d",&n);
        if(n<0)
        printf("factorial is not defined");
        else
        {
                f=factorial(n);
                printf("factorial of number is %d\n",f);
        }
return 0;
}                                                                         
int factorial(int n)
{
        if(n==1)
        return 1;
        else                                                              
        return (n*factorial(n-1));
}

OUTPUT

enter the number 5
factorial of number is 120

PROGRAM No 27:-PROGRAM TO PRINT FIBBONACCI SERIES USING RECURSSION

#include <stdio.h>
int fibbo(int num1);
void main()
{       
        int n,c,i=0;
        printf("enter the number ");
        scanf("%d",&n);
        for (c=1;c<=n;c++)
        {
                printf(" %d ",fibbo(i));
                i++;                                                      
        }
        printf("\n");
}       
int fibbo(int n)
{       
        if (n==0 || n==1)
        return n;
        else
        return (fibbo(n-1)+fibbo(n-2));
}

OUTPUT

enter the number 8
 0  1  1  2  3  5  8  13 

PROGRAM No 28:-PROGRAM TO DISPLAY A STUCTURE

#include <stdio.h>
struct xyz
{       
char name[5];
int marks;      
};              
int main()
{       
struct xyz p;
for(int i=0;i<=4;i++)
{
printf("enter name ");
scanf("%s",p.name);
printf("\n enter marks");
scanf("%d",&p.marks);
}
return 0;
}

OUTPUT

enter name a
 enter marks 1
enter name b
 enter marks 2
enter name c
 enter marks 3
enter name d
 enter marks 4
enter name e
 enter marks 5

    © 2019 GitHub, Inc.
    Terms
    Privacy
    Security
    Status
    Help

    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

