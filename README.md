# vetor_ling_C
ponteiros

#include <stdio.h>
#include <stdlib.h>

int main() {
    
  int *pont; 
  int cont, quant_num, novo_num, soma;
  quant_numeros = 12;
  pont = (int *) malloc(quant_num * sizeof(int));

  printf("Digite 12 valores para o vetor");
  printf("\n==============================================\n");
  
  for (cont = 0; cont < quant_num; cont++)
  {
    printf("Digite o %dº valor para o vetor: ", cont+1);
    scanf("%i",&ponteiro[cont]);
  }
  
  novo_num = 10;
  soma = quant_num + novo_num;
  pont = (int *) realloc(pont, soma * sizeof (int));
  
  printf("\nDigite mais 10 valores para o vetor");
  printf("\n==============================================\n");
  
  for (cont = cont; cont < soma; cont++)
  {
    printf("Digite o %dº valor para o vetor: ", cont+1);
    scanf("%i",&pont[cont]);
  }
  
  printf("\n======== Todos os 22 valores do vetor ========\n");
  
  for (cont = 0;cont < soma; cont++)
  {
    printf("%.2i ",pont[cont]);
  }
    
  free(pont);
    
  return 0;
