# kalkulator-sederhana




#include <stdio.h>

int main() {
    float a, b;
    char op;
    
    while(1) { 
        printf("Masukkan [operator angka]: ");
        scanf("%f %c %f", &a, &op, &b);
        
        if(op == '+') printf("= %.2f\n", a + b);
        else if(op == '-') printf("= %.2f\n", a - b);
        else if(op == '*') printf("= %.2f\n", a * b);
        else if(op == '/') printf("= %.2f\n", b != 0 ? a/b : 0);
        else printf("Operator salah!\n");
    }
    
    return 0;
}
