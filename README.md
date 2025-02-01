#include<stdio.h>
int main()
{
    char b;
    printf("welcome\n");
    printf("what is the capital of india?\n");
    printf("a.new delhi b.kolkata\n c.london d.new york\n");
    printf("select option;\n");
scanf("%d", &b); 
    if (b =='a')
    {
     printf("your answer is correct\n");   /* code */
    }
    else
    {
printf("your answer is incorrect\n");
    }
return 0;
}
