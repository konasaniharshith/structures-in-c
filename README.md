# structures-in-c
structures
#include<stdio.h>
int main()
{
   struct employee
   {
      char empname[20];
      int empage;
      int emppno;
      float empsal;
    };
    struct employee ee[20]
      int i;
      printf("Name Age Phone Number\nSalary");
      for(i=0;i<20;i++)
      {
         scanf("%s  %d  %d  %f\n",&ee[i]);
      }
      for(i=0;i<20;i++)
      {
         printf("%s  %d  %d  %f\n",ee[i]);
      }
      retirn 0;
}
Nmae Age Phone Number 
Salary
Input : Ravi 24 9876543321
        150000 and so on....
Output : Ravi 24 9876543321
         150000 
