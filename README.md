# num-to-base
#include <stdio.h>
int main()
{
    int num,base,i,arr[50],j=0;
    scanf("%d%d",&num,&base);
    while(num>0)
    {
        arr[j++]=num%base;
        num=num/base;
    }
    for(i=k-1;i>=0;i--)
    {
        printf("%d",arr[i]);
    }
}
