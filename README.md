# C ANSI
Este repositório é destinado a exemplos de codigos C ANSI.

## LINGUAGEM C

O "C" foi desenvolvido por Dennis Ritchie e Brian W. Kernighan no inicio da década de 70. Possui características como código compacto e velocidade de compilação, isso o popularizou muito visto que as máquinas da época tinha grandes restrições de memória. Mas essa característica também adverte ao programador a necessidade de elaborar um códigos otimizados e com grau de legibilidade bom.

Possui a característica de ser relativamente portátil visto que possui uma implementação pequena do compilador bem como das bibliotecas que o acompanham, bibliotecas essas que advém muito do seu poder.

### Diretivas
São instruções passadas para o processador.

*  INCLUDE = Diretiva responsável pela importação de arquivos. <br>
Exemplo: 
``` #include <stdio.h> ```

### Tipos de Dados
É o nome dado para um valor ou conjunto de valores que podem ser armazenados em suas respectivas variáveis. 

* char
  * Classificação: Texto
  * Faixa de Valores: -128 a 127
  * Tamanho: 01
* int
  * Classificação: Inteiro
  * Faixa de Valores: -32768 a 32767
  * Tamanho: 02
* float
  * Classificação: Fracionário
  * Faixa de Valores: 3.4e-38 a 3.4e+38
  * Tamanho: 04
* double
  * Classificação: Fracionário
  * Faixa de Valores: 1.7e-308 a 1.7e+308
  * Tamanho: 08
* void
  * Classificação: Vazio
  * Faixa de Valores: nenhum
  * Tamanho: 0

#### Obs: Na linguagem C não existe o tipo string, por isso usaremos sempre um array de char;



