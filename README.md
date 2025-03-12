#include <stdio.h>

int main()
{
    int a=22,b=4;
    printf("max=%d\n",((a+b)+abs(a-b)/2));
    printf("min=%d\n",((a+b)-abs(a-b)/2));
    return 0;
}
