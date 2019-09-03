#include<stdio.h>
void main()
{
        int a[10],i,n,k;
        printf("enter n");
        scanf("%d,&n");
        printf("enter k");
        scanf("%d,&k");
        for(i=0;i<n;i++)
        {
                scanf("%d",&a[i]);
        }
        printf("the array elements are:");
        if(a[i]>=k)
        {
                i=0;
                while(i<n)
                {
                        a[i]=a[i]+1;
                        i++;
                }

        }
        else
        {
                printf("array is");
        for(i=0;i<n;i++)
        {
                printf("%d",a[i]);
        }
        
}
        else
        {
                printf("array is");
        for(i=0;i<n;i++)
        {
                printf("%d",a[i]);

        }
        }
# sanjanathammayya.github.io
