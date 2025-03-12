# C-6
Reverse array
#include <stdio.h>

int main()
{
    int n;
    printf("enter the number of elements");
    scanf("%d", &n);
    int num[n];
    printf("enter the values of %d numbers:\n", n);
    for(int i=0;i<n;i++){
        scanf("%d", &num[i]);
    }
    printf("the numbers in reverse order:");
    for(int i=n-1;i>=0;i--){
        printf("%d\n",num[i]);
    }
    return 0;
}
