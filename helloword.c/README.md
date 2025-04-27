# Programa: Hello World em C

Este repositório contém um código simples na linguagem C que exibe a mensagem "Hello World" no console. Este programa é frequentemente utilizado como o exemplo mais básico ao iniciar o aprendizado de programação em qualquer linguagem.

## Objetivo

- Demonstrar como criar e executar um programa básico em C.
- Introduzir a estrutura básica de um programa na linguagem C.

## Estrutura do Código

1. **Inclusão de Bibliotecas**
   - `#include <stdio.h>`: Necessária para funções de entrada e saída, como `printf`.
   - `#include <stdlib.h>`: Necessária para o uso de funções como `system`.

2. **Função Principal**
   - A função `main` é o ponto de entrada do programa.
   - Funções utilizadas:
     - `printf`: Exibe uma mensagem no console.
     - `system("PAUSE")`: Pausa a execução do programa até o usuário pressionar uma tecla.
   - Código:
     ```c
     main()
     {
         printf("Hello Word\n");
         system("PAUSE");
         return 0;
     }
     ```

## Como Executar o Programa

1. Copie o código para um arquivo chamado `hello.c`.
2. Compile o arquivo utilizando um compilador C (como `gcc`):
   ```bash
   gcc hello.c -o hello
