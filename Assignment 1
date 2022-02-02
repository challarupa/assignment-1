#include <stdio.h>
int main()
{
    int n, m,i, j,first[10][10], second[10][10], sum[10][10], diff[10][10];
    printf("Enter no of rows and columns of the first matrix");
    scanf("%d%d", &m,&n);
    printf("Enter the elements of the first matrix %d", m*n);
    for(i=0; i<m; i++) 
        for(j=0; j<n;j++)  
            scanf("%d",&first[i][j]);
    printf("Enter the elements of the second matrix %d", m*n);
    for(i=0; i<m; i++) 
        for(j=0; j<n; j++)
            scanf("%d", &second[i][j]);
    printf("The first matrix is:");
    for(i=0;i< m; i++)
    {
        for(j= 0; j<n; j++)
        {
            printf("%d",first[i][j]);
        }
    printf("\n");
    }
    printf("The second matrix is:");
    for(i=0; i<m; i++)
    {
        for(j=0;j< n;j++)
        {
            printf("%d", second[i][j]);
        }
    printf("\n");
    }
    for(i=0;i<m; i++)
        for(j=0;j<n; j++)
            sum[i][j] = first[i][j] + second[i][j];
    printf("the addition of two  matrices is:");
    for(i=0; i< m; i++)
    {
        for(j=0; j<n; j++)
        {
            printf("%d", sum[i][j]);
        }
        printf("\n");
    }
    for(i=0;i<m;i++)
        for(j=0; j<n; j++)
            diff[i][j] = first[i][j] - second[i][j];
    printf("The substraction of two matrices is:");
    for(i=0; i<m;i++)
    {
        for(j=0; j<n; j++)
        {
            printf("%d", diff[i][j]);
        }
        printf("\n");
    }
    return 0;
}
