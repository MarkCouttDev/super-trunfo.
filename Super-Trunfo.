#include <stdio.h>
#include <string.h>

int main() {
    // ===== Dados para Carta 1 =====
    char estado1, codigo1[4], cidade1[50];
    unsigned long int populacao1;
    float area1, pib1;
    int pontos1;
    float densidade1, pibPerCapita1;

    // ===== Dados para Carta 2 =====
    char estado2, codigo2[4], cidade2[50];
    unsigned long int populacao2;
    float area2, pib2;
    int pontos2;
    float densidade2, pibPerCapita2;

    // ===== Cadastro Carta 1 =====
    printf("=== Cadastro da Carta 1 ===\n");
    printf("Estado (letra A a H): ");
    scanf(" %c", &estado1);
    printf("Código da carta: ");
    scanf("%s", codigo1);
    printf("Nome da cidade: ");
    scanf(" %[^\n]", cidade1);
    printf("População: ");
    scanf("%lu", &populacao1);
    printf("Área (km²): ");
    scanf("%f", &area1);
    printf("PIB (bilhões R$): ");
    scanf("%f", &pib1);
    printf("Pontos turísticos: ");
    scanf("%d", &pontos1);

    densidade1 = populacao1 / area1;
    pibPerCapita1 = (pib1 * 1000000000) / populacao1;

    // ===== Cadastro Carta 2 =====
    printf("\n=== Cadastro da Carta 2 ===\n");
    printf("Estado (letra A a H): ");
    scanf(" %c", &estado2);
    printf("Código da carta: ");
    scanf("%s", codigo2);
    printf("Nome da cidade: ");
    scanf(" %[^\n]", cidade2);
    printf("População: ");
    scanf("%lu", &populacao2);
    printf("Área (km²): ");
    scanf("%f", &area2);
    printf("PIB (bilhões R$): ");
    scanf("%f", &pib2);
    printf("Pontos turísticos: ");
    scanf("%d", &pontos2);

    densidade2 = populacao2 / area2;
    pibPerCapita2 = (pib2 * 1000000000) / populacao2;

    // ===== Menu Interativo =====
    int opcao;
    printf("\n=== Menu de Comparação ===\n");
    printf("Escolha o atributo para comparar:\n");
    printf("1 - População\n");
    printf("2 - Área\n");
    printf("3 - PIB\n");
    printf("4 - Pontos turísticos\n");
    printf("5 - Densidade demográfica\n");
    printf("Opção: ");
    scanf("%d", &opcao);

    printf("\n=== Resultado da Comparação ===\n");
    printf("Carta 1: %s\n", cidade1);
    printf("Carta 2: %s\n", cidade2);

    switch (opcao) {
        case 1:
            printf("Atributo: População\n");
            printf("%s: %lu\n", cidade1, populacao1);
            printf("%s: %lu\n", cidade2, populacao2);
            if (populacao1 > populacao2)
                printf("Vencedora: %s\n", cidade1);
            else if (populacao2 > populacao1)
                printf("Vencedora: %s\n", cidade2);
            else
                printf("Empate!\n");
            break;

        case 2:
            printf("Atributo: Área\n");
            printf("%s: %.2f km²\n", cidade1, area1);
            printf("%s: %.2f km²\n", cidade2, area2);
            if (area1 > area2)
                printf("Vencedora: %s\n", cidade1);
            else if (area2 > area1)
                printf("Vencedora: %s\n", cidade2);
            else
                printf("Empate!\n");
            break;

        case 3:
            printf("Atributo: PIB\n");
            printf("%s: R$ %.2f bilhões\n", cidade1, pib1);
            printf("%s: R$ %.2f bilhões\n", cidade2, pib2);
            if (pib1 > pib2)
                printf("Vencedora: %s\n", cidade1);
            else if (pib2 > pib1)
                printf("Vencedora: %s\n", cidade2);
            else
                printf("Empate!\n");
            break;

        case 4:
            printf("Atributo: Pontos turísticos\n");
            printf("%s: %d\n", cidade1, pontos1);
            printf("%s: %d\n", cidade2, pontos2);
            if (pontos1 > pontos2)
                printf("Vencedora: %s\n", cidade1);
            else if (pontos2 > pontos1)
                printf("Vencedora: %s\n", cidade2);
            else
                printf("Empate!\n");
            break;

        case 5:
            printf("Atributo: Densidade demográfica\n");
            printf("%s: %.2f hab/km²\n", cidade1, densidade1);
            printf("%s: %.2f hab/km²\n", cidade2, densidade2);
            if (densidade1 < densidade2)
                printf("Vencedora: %s\n", cidade1);
            else if (densidade2 < densidade1)
                printf("Vencedora: %s\n", cidade2);
            else
                printf("Empate!\n");
            break;

        default:
            printf("Opção inválida! Tente novamente.\n");
            break;
    }

    return 0;
}

