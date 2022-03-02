#include <stdio.h>
#include <math.h>


void main(){
    int a,b,c;
    float x1,x2,x3;
    printf("Enter the value of A B And C : \n");
    scanf("%d%d%d", &a,&b,&c);
    x1 = (-b + sqrt(pow(b,2)-4ac))/(2a) ;
    x2 = (-b - sqrt(pow(b,2)-4ac))/(2a);
    x3 = pow(b,2)-4ac;
    if(a==0 || x3<0){
        printf("it is not possible to find the roots");
    }
    else {
        printf("X1 is %f and X2 is %f",x1,x2);
    }

}
