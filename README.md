# C37
Tree recursion 
#include<stdio.h>
void tree(int n){
 if(n<0)return;
 printf("%d",n);
   tree(n-1);
   tree(n-2);
   tree(n-3);
 }
 int main()
 {
  (tree(3));
  return 0;
 }
