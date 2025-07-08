#include <stdio.h>

int main() {
    SetConsoleOutputCP(1251);
    int t1, t2, t3;

    printf("Ведіть три значення: \n");
    scanf("%d %d %d", &t1, &t2, &t3);

    double rate1 = 1.0 / t1;
    double rate2 = 1.0 / t2;
    double rate3 = 1.0 / t3;

    double total_rate = rate1 + rate2 + rate3;
    double time = 1.0 / total_rate;

    printf("час необхідний для з'їдання пирога: %.2f годин\n", time);
    return 0;
}
# -1
