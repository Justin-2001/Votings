# Votings
#include<stdio.h>

int main()
{ 
    char name[20], last[20];
    int age;
    
    printf("Name: ");
    scanf("%s %s", name, last);
    printf("Age: ");
    scanf("%d", &age);
    
    if(age >= 18){
        printf("%s %s You're Qualified to vote!!", name, last);
    }else if(age <18 ){
        printf("%s %s You're not allowed to vote!", name, last);
    }else {
        printf("Invalid");
    }
    
    return 0;
}
