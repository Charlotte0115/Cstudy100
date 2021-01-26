# Cstudy100
#include <stdio.h>

int main (void)
{
    int income = 0;
    double tax;
    const double tax_rate = 0.12;
    
    income = 10526;
    tax = income * tax_rate;
    printf("세금은 : %.2lf입니다.\n", tax)
    
    return 0;
}
