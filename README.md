#include <stdio.h>

int main() {
    int num = 1;
    int sum = 0;

    printf("Enter positive numbers to ADD (zero or negative number to STOP)\n");

    while (num > 0) {
        printf("Enter a number: ");
        scanf("%d", &num);

        if (num > 0) {
            sum = sum + num;
        }
    }

    printf("Total sum is: %d\n", sum);

    return 0;
}
