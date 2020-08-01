#include<stdio.h>
int main(){
    int a;
    int b;
    int c=0;
    puts("Enter the the number, you wish to see the multiplication table: ");
    scanf ("%d",&a);
    
for(b=0;b<101;b++){
    printf("%d*%d = %d\n",c,a,c*a);
    c= c+1;
}
return 0;
}
