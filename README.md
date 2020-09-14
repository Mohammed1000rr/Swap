# Swap 

#include <stdio.h>

#include <stdlib.h>

void swap(int , int);

int main()

{

   int x , y;
   
   printf("Please Enter x:");
   
   scanf("%d" , &x);
   
   printf("Please Enter y:");
   
   scanf("%d" , &y);

   swap(x,y);

    return 0;
    
}

void swap(int x,int y)

{

    x = x+y;
    
    y = x-y;
    
    x = x-y;

    printf("x = %d , y = %d ",x,y);

}
