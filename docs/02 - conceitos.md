# Conceitos Fundamentais de C

## Estrutura básica

Todo programa em C precisa de uma função 'main que define onde é o inicio do programa.

```c

#include <stdio.h>
int main()
{
    printf("Olá, Mundo!");
    return 0;
}
```

-'include <stdio.h>' - Importa a biblioteca padrão que permite o C utilizar entradas e saídas.
    *stdio.h-->(Standard Input/Output).
-'int main()' - a função principal; o 'int' é pra dizer que ela retorna um numero inteiro no final.
-'return 0; - Indica que o programa terminou sem erros
    *Nas versões mais recentes do C, é opcional.

## printf

-'printf' é uma função de saída utilizada para imprimir um texto. Ela funciona com especificadores de variáveis dentro do texto:

| Especificador | Tipo de dado |
|---|---|
| `%d` | inteiro (int) |
| `%f` | número decimal (float) |
| `%c` | caractere (char) |
| `%s` | string (cadeia de caracteres) |

Exemplo:
```C
float altura = 1.87;
printf("Tenho %fm de altura\n",altura);
```

O '\n' no final da string representa uma quebra de linha. Ou seja; O que for printado posteriormente terá o retorno uma linha abaixo.

## Variaveis e Tipos

Diferente do Python, em C você precisa declarar o **tipo** de cada 
variável antes de usá-la:

```c
int idade = 20;        // número inteiro
float altura = 1.75;   // número decimal
char inicial = 'D';    // um único caractere (aspas simples)
```
### Laços de repetição

```c
for (int i = 0; i < 5; i++) {
    printf("%d\n", i);
}
```

## Compilando e executando

C precisa ser compilado antes de rodar (diferente do Python, que é 
interpretado direto). Usando o GCC:

```bash
gcc programa.c -o programa
./programa
```

## Próximos passos

Os exercícios práticos desses conceitos estão em `03-exercicios.md`.
    