#include <stdio.h>

int main(){
    char str[100];
    printf("Enter your name\n");
    scanf("%s",str);
    
    int a;
    printf("Enter your roll no:\n");
    scanf("%d",&a);
    
    int b;
    printf("Enter your marks no:\n");
    scanf("%d",&b);

    printf("Your name is %s\n",str);
    printf("Your roll no is:%d\n",a);
    printf("Your marks is:%d\n",b);

    if(b>=90 && b<=100)
    {
        printf("Your grade is A\n");
    }
    else if(b>=80 && b<=90)
    {
        printf("Your grade is B\n");
    }
    else if(b>=80 && b<=90)
    {
        printf("Your grade is C\n");
    }
    else if(b>=70 && b<=80)
    {
        printf("Your grade is D\n");
    }
    else{
        printf("You are not passed\n");
    }
    
    return 0;
}
