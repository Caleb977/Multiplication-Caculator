#include<stdio.h>
int main(){
    int a;
    int b;
   
    puts("Enter the the number, you wish to see the multiplication table: ");
    scanf ("%d",&a);
    
for(b=0;b<101;b++){
    printf("%d*%d = %d\n",b,a,b*a);
  
}
return 0;
}
