## Write a programme to find sum of cube of 'n' number.

```
Input: 4
Output: 30
```

---

```C
#include<stdio.h>
int main(){
    int a;
    int total=0;
    printf("Input: ");
    scanf("%d",&a);
    for(int i=1 ; i<=a ; i++){
        total += (i*i*i);
    }
    printf("Output: %d",total);
    return 0;
}
```