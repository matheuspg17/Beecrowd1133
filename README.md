# Resolução exercício Beecrowd1133

## Descrição do problema
Escreva um programa que leia 2 valores X e Y e que imprima todos os valores entre eles cujo resto da divisão dele por 5 for igual a 2 ou igual a 3.

## Como Funciona
1. O programa recebe dois números inteiros do usuário nas variáveis `num1` e `num2`.
2. Uma estrutura condicional (`if/else`) compara os números para identificar qual é o `numeromaior` e qual é o `numeromenor`.
3. Uma estrutura de repetição `for` percorre o intervalo estrito, iniciando em `numeromenor + 1` até um valor menor que `numeromaior`.
4. Dentro do laço, a condicional `if (i % 5 == 2 || i % 5 == 3)` utiliza o operador de resto (`%`) combinado com o operador lógico OU (`||`) para validar os critérios solicitados.
5. Os números que atendem à condição são impressos um por linha no console.