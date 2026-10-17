# 08 — Circuitos Digitais

## 1. O que são circuitos digitais?

Circuitos digitais são conjuntos de componentes eletrônicos que processam sinais digitais, geralmente interpretados como 0 e 1.

Eles podem ser construídos combinando portas lógicas e são utilizados em processadores, memórias, calculadoras e outros equipamentos.

## 2. Como analisar um circuito?

1. Identifique as entradas.
2. Observe as portas lógicas.
3. Resolva as operações na ordem indicada.
4. Utilize cada resultado na etapa seguinte.
5. Determine a saída final.

## 3. Exemplo resolvido

Considere:

S = (A AND B) OR C

Valores:

A = 1  
B = 1  
C = 0

Primeira operação:

A AND B = 1 AND 1 = 1

Segunda operação:

S = 1 OR 0 = 1

Resposta: `S = 1`.

## 4. Tabela-verdade

Para a expressão `S = (A AND B) OR C`:

| A | B | C | A AND B | S |
|---:|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 | 1 |
| 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 1 | 1 | 1 |

Como existem três entradas binárias, o número de combinações é 2³ = 8.

## 5. Exemplo com NOT

Considere:

S = NOT(A AND B)

Se A = 1 e B = 1:

1. A AND B = 1.
2. NOT 1 = 0.

Resposta: `S = 0`. Essa expressão corresponde a uma porta NAND.

## Resumo

Circuitos digitais combinam portas lógicas para realizar operações. A tabela-verdade apresenta a saída para todas as combinações possíveis das entradas.

## Exercícios

1. Calcule `S = (A AND B) OR C` quando A = 0, B = 1 e C = 1.
2. Calcule `S = NOT(A AND B)` quando A = 1 e B = 0.
3. Quantas combinações existem para quatro entradas binárias? Use 2⁴.
