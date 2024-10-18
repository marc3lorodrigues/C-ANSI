# C ANSI
Este repositório é destinado a exemplos de codigos C ANSI.

## LINGUAGEM C ANSI

O "C" foi desenvolvido por Dennis Ritchie e Brian W. Kernighan no inicio da década de 70. Possui características como código compacto e velocidade de compilação, isso o popularizou muito visto que as máquinas da época tinha grandes restrições de memória. Mas essa característica também adverte ao programador a necessidade de elaborar um códigos otimizados e com grau de legibilidade bom.

Possui a característica de ser relativamente portátil visto que possui uma implementação pequena do compilador bem como das bibliotecas que o acompanham, bibliotecas essas que advém muito do seu poder.

### Trabalhando com C ANSI
[Diretivas](Diretivas.md) <br>
[Tipos de Dados](tiposdedados.md)<br>
[Variáveis](variaveis.md)<br>
[Comandos de Entrada e Saída](ComandosEntradaSaida.md)<br>
[Operadores](Operadores.md) <br>
[Estrutura de Decisão](EstruturasDecisao.md) <br>
[Estrutura de Repetição](estruturaRepeticao.md) <br>
[Outros Comandos](OutrosComandos.md)<br>



 ### Trabalhando com C ANSI
  <ol>
    <li>Diretivas</li>
      São instruções passadas para o processador.

*  INCLUDE = Diretiva responsável pela importação de arquivos. <br>
Exemplos: 
```
#include <stdio.h>
#include <string.h>
 ```


  <li>Tipos de Dados</li>
  

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


<br><br>

  <li>Variáveis</li>
Variáveis são identificadores utilizados para o armazenamento de valores na memória. São divididas em grupos conforme seus tipos. O nome da variável poderá ser definido após seu tipo de dado e deverá ser único no bloco. Podem ser compostos de letras e números porem deverão ser iniciados sempre com letras. Não é permitido símbolos especiais exceto o sublinhado(_). A variável poderá ser utilizada em seu bloco de definição e todos os sub-algoritmos que estiver subordinados ao mesmo bloco.


#### Sintaxe:
* Quanto a forma de declarar, a variável deverá sempre preceder ao tipo de dado. Deverá ser separada por virgula quando do mesmo tipo.
```
int Idade;
float altura, peso;
``` 

* Atribuição de valores;
```
idade = 4;
altura = 1,2;
```               

 

 

  <li>Comando de Entrada/Saída</li>
  <li>Operadores</li>
  <li>Estruturas de Decisão</li>
  <li>Estrutura de Repetição</li>
  <li>Outros comandos</li>
  </ol> 
  </li>

  
