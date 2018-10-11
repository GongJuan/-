# include<stdio.h>
# define k 10
main()
{
int a[k],b[k];
int i,j;
printf("输入10个数：");
for(i=0;i<10;i++)
{
scanf("%d",&a[i]);
}
printf("你输入的数为：");
for(i=0;i<10;i++)
{
printf("%d ",a[i]);
}
printf("\n");
for(i=9,j=0;i>=0;i--,j++)  //??????
{
b[j]=a[i];
}
printf("倒序之后的数为：");
for(i=0;i<10;i++)
{
printf("%d ",b[i]);
}
printf("\n");
}
