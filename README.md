#include <stdio.h>

int main() { int t1, t2, t3; double rate1, rate2, rate3, total_rate, total_time;

printf("Ведіть три значення: ");
scanf("%d %d %d", &t1, &t2, &t3);

rate1 = 1.0 / t1;
rate2 = 1.0 / t2;
rate3 = 1.0 / t3;

total_rate = rate1 + rate2 + rate3;

total_time = 1.0 / total_rate;

printf("Час, необхідний для з'їдання пирога: %.2lf години\n", total_time);

return 0;
}
