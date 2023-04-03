#include <stdio.h>
int survey(int a[10])
{
  int i,fir=0,sec=0,thir=0,four=0;
  for(i=0;i<10;i++)
    {
      if(a[i]==1)
        fir++;
      else if(a[i]==2)
        sec++;
      else if(a[i]==3)
        thir++;
      else if(a[i]==4)
        four++;
      else
        printf("Wrong value entered");
    }
  printf("\n Count of reviews \n 1.- Very Good = %d\n 2.-Good = %d\n 3.- Average =%d \n 4.-Need to improve =%d",fir,sec,thir,four);
}

int main(void) {
 int a[10],i;
  printf("\n Enter\n 1.- Very Good \n 2.-Good \n 3.- Average \n 4.-Need to improve\n");

  for(i=0;i<10;i++)
    {
      scanf("%d",&a[i]);
      printf("\nReview saved\n");
    }
  survey(a);
  
  return 0;
}
