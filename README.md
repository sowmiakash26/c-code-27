#include<stdio.h>
int add(int *a, int *b){
return *a+*b;

}
int main()
{
    int num1,num2;
    printf("Enter num1 and num2 : \n");
    scanf("%d %d", &num1,&num2);
    int sum = add(&num1,&num2);
    printf("total: %d \n", sum);
    return 0;

    }
