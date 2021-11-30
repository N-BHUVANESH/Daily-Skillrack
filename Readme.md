#include <stdio.h>
multiply(int a,int b){
    return a*b;
}
int main()
{
    int number1, number2;
    scanf("%d%d",&number1,&number2);

    printf("%d",multiply(number1,number2));

    return 0;
}
