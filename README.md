#include <stdio.h>

int main() {
    // Carta 1
    char codigo1[4];
    int pop1, tur1;
    float area1, pib1;

    // Carta 2
    char codigo2[4];
    int pop2, tur2;
    float area2, pib2;

    printf("Digite Carta 1 (codigo pop area pib tur): ");
    scanf("%s %d %f %f %d", codigo1, &pop1, &area1, &pib1, &tur1);

    printf("Digite Carta 2 (codigo pop area pib tur): ");
    scanf("%s %d %f %f %d", codigo2, &pop2, &area2, &pib2, &tur2);

    printf("\nCarta 1 -> %s %d %.2f %.2f %d\n", codigo1, pop1, area1, pib1, tur1);
    printf("Carta 2 -> %s %d %.2f %.2f %d\n", codigo2, pop2, area2, pib2, tur2);

   

