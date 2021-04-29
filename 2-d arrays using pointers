#include<stdio.h>
main()
{
    int a[10][10],i,j,m,n,(*ptr)[10];
    ptr=a;
    printf("enter number of rows and columns");
    scanf("%d%d",&m,&n);
    printf("enter elements\n");
    for(i=0;i<m;i++)
    for(j=0;j<n;j++)
    scanf("%d",&a[i][j]);
    printf("the elements are\n");
    for(i=0;i<m;i++)
    {
        for(j=0;j<n;j++)
    {
      printf("%d\t ",*(*(ptr+i)+j));
     }
     printf("\n");
     
    }
}
