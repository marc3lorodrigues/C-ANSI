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

### Funções de String
* gets <br>
Lê uma string a partir do teclado.
```
gets(Nome);
```


* strcpy <br>
Copia a string destino para a string de origem.
```
strcpy(strorigem,strdestino);
```
* strcat <br>
Anexa a palavra origem na palavra destino.
```
strcat(strorigem,strdestino);
```
* strlen <br>
retorna o comprimento da string.
```
i = strlen(str);
```

* strcmp <br>
Compara as strings retornando zero se forem iguais.
```
i = strcmp(strorigem,strdestino);
```

