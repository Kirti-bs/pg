# pg

Taylor series - 1st post

#include<stdio.h>
#include<math.h>
#define PI 3.142

void main()
 {
   int i ,degree;
   float x,sum=0,term,nume,fact;
   clrscr();
   prints("Enter value of degree\n");
   scanf("%d",&degree);
   X=degree*(PI/180);
   nume=x;
   fact=1;
   i=2;

  do
  {
    term=nume/fact;
    nume=-nume*x*x;
    fact=fact*i*(i+1);
    sum=sum+term;
    i=i+2;
  }
    while(fans(term)>=0.00001);
    printf("The sine of %d is %.3f",degree,sin(x));

}
