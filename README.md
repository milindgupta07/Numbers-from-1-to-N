# Numbers-from-1-to-N
Using C language program is made which gives the output of numbers from 1 to N
#include <stdio.h>
int main() {
    int N, i = 1;
    scanf("%d", &N);
    while(i <= N) {
        printf("%d ", i);
        i++;
    }
    return 0;
}
