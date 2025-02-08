#include <stdio.h>

int main() {
int i,n,sum=0,even=0,odd=0;
for(i=0;i<=10;++i)
{
    sum=sum+i;
    if(i%2==0)
    even=even+i;
    else
    odd=odd+i;
}

printf("even sum=%d\n",even);
printf("odd sum=%d\n",odd);

    return 0;
}
