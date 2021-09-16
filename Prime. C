#include<stdio.h>

int prime(int,int);
main()
{
    int n,res;
    printf("Enter a number ");
    scanf("%d",&n);
    res=prime(n,n/2);
    if(res==1)
    {
        printf("Number is prime");
    }
    else
    {
        printf("Number is not prime");
    }
    return 0;
}
int prime(int n,int i)
{
    if(i==1)
    {
        return 1;
    }
    else
    {
        if(n%i==0)
        {
            return 0;
        }
        else
        {
            return prime(n,i-1);
        }
    }
}
