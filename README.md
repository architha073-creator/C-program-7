# C-program-7
Next and previous character 
#include<stdio.h>
int main()
{
    char name,previous,next;
    printf("enter");
    scanf("%c",& name);
    if (name=='a')
    {
        previous='z';
        next='b';
    }
    else if (name=='z')
    {
        next='a';
        previous='y';
    }
    else
    {
        next=name+1;
        previous=name-1;
    }
    printf("previous=%c",previous);
    printf("next=%c",next);
    return 0;
}
