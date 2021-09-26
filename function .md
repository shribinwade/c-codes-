#include <stdio.h>
#include <stdlib.h>

int main() {
    int a, b, c, d;
    scanf("%d %d %d %d", &a, &b, &c, &d);
    int ans = max_of_four(a, b, c, d);
    printf("%d", ans);

    return 0;
}

     max_of_four(a, b, c, d){
     int x,y,z;

     z=(x=a>b?a:b)>(y=c>d?c:d)?x:y;
     return z;

     }

