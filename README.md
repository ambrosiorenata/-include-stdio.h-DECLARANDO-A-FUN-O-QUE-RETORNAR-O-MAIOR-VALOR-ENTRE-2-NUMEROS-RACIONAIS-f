# -include-stdio.h-DECLARANDO-A-FUN-O-QUE-RETORNAR-O-MAIOR-VALOR-ENTRE-2-NUMEROS-RACIONAIS-f
#include <stdio.h>

//DECLARANDO A FUNÇÃO QUE RETORNAR O MAIOR VALOR ENTRE 2 NUMEROS RACIONAIS  
  float maior_valor(float a, float b)
{
    if(a > b) return a;
    else return b;
}

//SOLICITANDO AO USUARIO OS DADOS DA VARIAVEIS
    int main()
{
       float  a, b;
      
       printf("Informe o primeiro número: ");
       scanf("%f", &a);
      
       printf("Informe o segundo número: ");
       scanf("%f", &b);
      
      //VERIFICANDO A CONDICIONAL 
       printf("\nO maior valor é: %.3f", maior_valor(a,b));
      
    return 0;
}
