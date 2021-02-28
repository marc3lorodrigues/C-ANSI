# Estrutura de Decisão
As estruturas de decisão tem como objetivo fazer o desvio de execução das instruções. O desvio pode ser feito através da avaliação de uma expressão lógica  oriundos de valores estáticos ou variáveis. Vejamos as estruturas:

* if... / if...else...;
* switch.

## Comando if... / if...else...
Comando responsável pela avaliação uma expressão lógica e direcionamento da execução do programa com base na condição imposta na expressão. Quando o bloco possuir mais de uma instrução deverá ser definido seu inicio e seu fim com {}.Podemos construir estruturas seguindo os modelos abaixo:

#### Simplesmente IF
Exemplos:
```
if (x==10)
  printf("Expressão verdadeira");

if (y== 0)
  printf("Expressão verdadeira");
else
  printf("Expressão verdadeira");
``` 

#### IFs Aninhados
Exemplo:
``` 
if (x==10)
  printf("If principal");
  if (w == 10) then
    printf("if aninhado");
  else
    printf("else aninhado");
Else
  printf("if aninhado");
``` 

#### Escada de IF
Exemplo:
``` 
if (x==1)
  printf("bloco 1");
else if (x==2)
  printf("bloco 2");
else if (x==3)
  printf("bloco 3");
else       
  printf("nenhuma das opções");
``` 
 

## switch
Comando responsável pela escolha de uma opção entre N opções. Tem como característica a definição de constantes de valores que são comparadas á expressão e executa um bloco referente á constante.
Exemplo:
``` 
switch (x)
{
  case 1:
    printf("Opção 1");
  case 2:
    printf("Opção 2");
  default:
    printf('Para qualquer outra opção');
}
``` 


 

 

 
