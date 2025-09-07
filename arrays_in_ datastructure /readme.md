  #PROGRAM TO STORE THE CONTENT IN THE ARRAY AND ACCES USING THE LOOP 
```
#include <stdio.h>

int main() {
    
    int a[5],i;
    printf("enter the array elements ");
    for (i=0; i<4; i++)
    scanf("%d",&a[i]);

printf(" the array elements are ");
for (i=0; i<4 ; i++)
{
    printf("%d ",a[i]);
}
    return 0;
}
```
### Space near the %d will make the code fault
