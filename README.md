# Plub6580873
#include <stdio.h>
#include <math.h>
int main()
{
    int a,b,c;
    printf("Input your numbers:");
    scanf("%d,%d,%d",&a,&b,&c);
    
    float  x1,x2;
    x1=(-b+sqrt(pow(b,2)-(4*a*c)))/(2*a);
    x2=(-b-sqrt(pow(b,2)-(4*a*c)))/(2*a);
   
    printf("%.2f,%.2f",x1,x2);
    return 0;
}

