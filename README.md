# swapping-number
To swap two numbers without temporary variable
#include <stdio.h>

int main() {
 int x,y;
 printf("Enter the numbers");
 scanf("%d %d",&x,&y);//x=5 and y=2
 x=x+y;//x=7
 y=x-y;//y=5
 x=x-y;//x=2
 printf("the swapped values are %d %d",x,y);
    return 0;
}

