# Programa: Operações Matemáticas em C

Este repositório contém um programa em C que realiza e exibe o resultado de diversas operações matemáticas básicas, como adição, subtração, multiplicação e divisão. O código também demonstra o uso de precedência de operadores matemáticos.

## Objetivo

- Demonstrar como realizar operações matemáticas básicas na linguagem C.
- Explorar a precedência de operadores matemáticos dentro de expressões.

## Estrutura do Código

### 1. **Inclusão de Bibliotecas**
- `#include <stdio.h>`: Biblioteca padrão usada para funções de entrada e saída, como `printf`.
- `#include <stdlib.h>`: Biblioteca padrão que fornece a função `system` para pausar o programa.

### 2. **Função Principal**
A função `main` realiza as seguintes operações:
- Adição: `10 + 10`
- Subtração: `10 - 5`
- Multiplicação: `10 * 10`
- Divisão: `10 / 5`
- Expressões mais complexas com múltiplos operadores:
  - `10 + 5 * 2 / 5`
  - `(10 + 5) * 2 / 5` (com o uso de parênteses para alterar a precedência).

#### Código:
```c
main()
{
    printf("10 + 10 = %d\n\n", 10 + 10);
    printf("10 - 5 = %d\n\n", 10 - 5);
    printf("10 * 10 = %d\n\n", 10 * 10);
    printf("10 / 5 = %d\n\n", 10 / 5);
    printf("10 + 5 * 2 / 5 = %d\n\n", 10 + 5 * 2 / 5);
    printf("(10 + 5) * 2 / 5 = %d\n\n", (10 + 5) * 2 / 5);

    system("PAUSE");
    return 0;
}
