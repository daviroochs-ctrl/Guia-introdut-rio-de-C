# Exemplo básico: Hello World

Este é o programa mais simples possível em C, usado tradicionalmente 
como primeiro contato com qualquer linguagem.

## Código completo

```c
#include <stdio.h>

int main() {
    printf("Olá, mundo!\n");
    return 0;
}
```

## Explicação linha por linha

```c
#include <stdio.h>
```
Importa a biblioteca padrão de entrada/saída. Sem essa linha, o compilador 
não reconheceria a função `printf`.

```c
int main() {
```
Declara a função principal do programa — todo programa em C começa a 
execução por aqui. O `int` antes de `main` indica que essa função vai 
devolver um número inteiro ao sistema operacional quando terminar.

```c
    printf("Olá, mundo!\n");
```
Imprime o texto no terminal. O `\n` no final move o cursor para a linha 
seguinte, como um "Enter".

```c
    return 0;
```
Encerra a função `main`, devolvendo o valor `0` — por convenção, `0` 
significa que o programa terminou sem erros.(Não é mais obrigatório)

```c
}
```
Fecha o bloco da função `main`.

## Como compilar e rodar

```bash
gcc exemplo.c -o exemplo
./exemplo
```

Saída esperada:

```
Olá, mundo!
```

## Variação: usando uma variável

```c
#include <stdio.h>

int main() {
    char nome[] = "Davi";
    printf("Olá, %s! Bem-vindo ao C.\n", nome);
    return 0;
}
```

Aqui, `%s` é o especificador de formato para strings (visto em 
`02-conceitos.md`), e a variável `nome` é inserida no lugar dele.