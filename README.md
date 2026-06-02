#include<stdio.h>

int main()

{
    int i, age[5];

    for (i=0; i<5;i++)

    {

        printf("Enter %d number: \n",i+1);
        scanf("%d",&age[i]);

    }
      for (i=0; i<5;i++)

    {
      printf("Enter %d number= %d",i+1,age[i]);

        printf("%d\n",age[i]);


    }



    return 0;

}
