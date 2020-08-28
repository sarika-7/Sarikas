#include <stdio.h>
int main()
{
    int n,i,count=0;
   char s[n];
   scanf("%d",&n);
   scanf("%s",s);
   for(i=0;s[i]!=0;i++)
   {
       
       count++;
   }
   for(i=count-1;i>=0;--i)
   {
       printf("%c",s[i]);
   }
   return 0;
}

