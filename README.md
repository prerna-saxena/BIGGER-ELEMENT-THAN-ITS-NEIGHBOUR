# BIGGER-ELEMENT-THAN-ITS-NEIGHBOUR



// Online C compiler to run C program online
#include <stdio.h>

void  main() {
    int n, i, arr[10], m=0, c;
    printf("ENTER AN ARRAY\n");
    scanf("%d", &n);
    while(n--)
    {
        scanf("%d", &arr[i]);
        if(arr[i]>m)
        {
            m=arr[i];
            c++;
        }
        
        
    }
    printf("%d", c);
    return 0;
}
