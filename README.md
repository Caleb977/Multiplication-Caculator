#include<stdio.h>
int main(){
    int a;
    int b;
    int c;
   
    puts("Enter the the number, you wish to see the multiplication table: ");
    scanf ("%d",&a);
    
    puts("What number do you which to end the multiplication table:");
    scanf("%d",&c);
    
for(b=0;b<c+1;b++){
    printf("%d*%d = %d\n",b,a,b*a);
  
}
return 0;
}
