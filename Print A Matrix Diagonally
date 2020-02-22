/*Input 1 2 3
        4 5 6
        7 8 9
 Output 1 4 2 7 5 3 8 6 9   */

#include <stdio.h>

int main()
{
   int i,j,p,k,c=0,m,n;
   scanf("%d %d",&m,&n);
   int arr[m][n];
   for(i=0;i<m;i++)
       for(j=0;j<n;j++)
       scanf("%d",&arr[i][j]);
               int r1=0,rl=m-1,cl=n-1,c1=0;
               int o=m*n;
    for(i=0;i<=rl;i++)
    {
        p=i;
        for(j=0;j<=i;j++)
        {
             printf("%d ",arr[p][j]);
             c++;
            p--;
        }
    }
    c1++;
    for(i=rl;i<=rl;)
    {
        p=i;
        for(j=c1;j<=cl;j++)
        {
            printf("%d ",arr[p][j]);
            p--;
            c++;
        }
        c1++;
        if(c==o)
        break;
    }

    return 0;
}
