#include<stdio.h>
void swap_ref(int*, int*);
void swap_val(int, int);
 
 
void swap_val(int a, int b)
{
   int temp;
 
   temp = b;
   b = a;
   a = temp;
}
void swap_ref(int *a, int *b)
{
   int temp;
 
   temp = *b;
   *b = *a;
   *a = temp;   
}

 

 
int main()
{
   int x, y;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
 
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
   swap_ref(&x, &y); 
   swap_val(x, y); 
   
   printf("After Swapping using call by reference\nx = %d\ny = %d\n", x, y);
   printf("After Swapping using call by value\nx = %d\ny = %d\n", x, y);
   
   return 0;
}
