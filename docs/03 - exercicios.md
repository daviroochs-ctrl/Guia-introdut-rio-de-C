# Exercícios práticos

Exercícios resolvidos durante o aprendizado de C, organizados por tema.

## 1. Olá, mundo com variável

**Enunciado:** crie um programa que armazene seu nome em uma variável e 
exiba uma saudação usando `printf`.

```c
#include <stdio.h>

int main() {
    char nome[] = "Davi";
    printf("Olá, %s!\n", nome);
    return 0;
}
```

## 2. Calculadora simples

**Enunciado:** Defina dois números inteiros e exiba a soma, subtração, 
multiplicação e divisão entre eles.

```c
#include <stdio.h>

int main() {
    int a = 10, b = 3;

    printf("Soma: %d\n", a + b);
    printf("Subtração: %d\n", a - b);
    printf("Multiplicação: %d\n", a * b);
    printf("Divisão: %d\n", a / b);

    return 0;
}
```

**Observação:** como `a` e `b` são `int`, a divisão descarta a parte 
decimal (`10 / 3` resulta em `3`, não `3.33`). Para obter o valor com 
casas decimais, é necessário usar `float` ou `double`.

## 3. Par ou ímpar

**Enunciado:** verifique se um número é par ou ímpar usando o operador 
resto (`%`).

```c
#include <stdio.h>

int main() {
    int numero = 7;

    if (numero % 2 == 0) {
        printf("%d é par\n", numero);
    } else {
        printf("%d é ímpar\n", numero);
    }

    return 0;
}
```

## 4. Contagem com laço for

**Enunciado:** exiba os números de 1 a 10 usando um laço `for`.

```c
#include <stdio.h>

int main() {
    for (int i = 1; i <= 10; i++) {
        printf("%d\n", i);
    }
    return 0;
}
```

## 5. Tabuada

**Enunciado:** exiba a tabuada de um número usando um laço.

```c
#include <stdio.h>

int main() {
    int numero = 5;

    for (int i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", numero, i, numero * i);
    }

    return 0;
}
```

## Próximos passos

Materiais e links usados como apoio estão listados em `04-referencias.md`.