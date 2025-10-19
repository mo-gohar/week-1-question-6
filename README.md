# week-1-question-6
#include <stdio.h>

int main() {
    int temperature, time;

    printf("Enter the water temperature: ");
    scanf("%d", &temperature);

    if (temperature < 0) {
        printf("Invalid input.\n");
    } else if (temperature <= 30) {
        time = 7;
        printf("Required heating time = %d minutes.\n", time);
    } else if (temperature <= 60) {
        time = 5;
        printf("Required heating time = %d minutes.\n", time);
    } else if (temperature <= 90) {
        time = 3;
        printf("Required heating time = %d minutes.\n", time);
    } else if (temperature <= 100) {
        time = 1;
        printf("Required heating time = %d minute.\n", time);
    } else {
        printf("Invalid input.\n");
    }

    return 0;
}
