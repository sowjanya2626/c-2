# c-2
length of the array by using size of the array
#include <stdio.h>

int main()
{
    int num[]={33,8,77,6,99,0,4};
    int length = sizeof(num)/sizeof(num[0]);
    printf("length=%d:\n",length);
    return 0;
}
