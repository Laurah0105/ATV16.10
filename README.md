#include <stdio.h>

int main () {
    int n;
    float preços[50];
    int i, j;
    float chave;
    int passos = 0;

    printf("Quantos preços quer cadastrar?");
    scanf("%d" , &n);

    printf("Digite os preços:\n");
    for (i = 0; i < N; i++) {
        scanf("%f", &preços[i]);
    }
    printf("\nLista de preços antes da ordenação:\n");
    for (i = 0; i< n; i++)  {
        printf("%.2f ", preços[i]);
    }
    printf("\n");
     
     for (i = 1;i < n; i++) {
        chave = preços[i];
        j = i -1;
        while (j >= o && preços[i] > chave) {
            preço[j + 1] = preços[j];
            j = j -1;
            passos++;
        }
        preços[j + 1] = chave;
     }
         printf("\nLista de preços e, ordem crescente:\n");
         for (i = 0; i < n; i++)  {
            printf("%.sf", preços[i]);
         }
         printf("\n");

         printf("\nNumero de passos realizados durante a ordenação: %d\n", passos);

         return 0;
}