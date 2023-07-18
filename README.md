#include <stdio.h>

int main()
    {
        int number = 0;
        printf("Enter Number Please:");
        scanf("%d", &number);
        
        if(number & 16){
            printf("1");
        }else{
            printf("%d", number);
        }
    }
