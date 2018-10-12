#include<stdio.h>
#include<math.h>
int main()
{
    int n,power,ans;
    printf("Enter the number whose power is to be calculated:");
    scanf("%d",&n);
    printf("Enter the power the number is to be raised:");
    scanf("%d",&power);
    ans=pow(n,power);
    printf("The answer is: %d",ans);
return 0;
}
