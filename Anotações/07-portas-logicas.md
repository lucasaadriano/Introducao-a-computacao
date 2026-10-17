# 07 — Portas Lógicas

## 1. O que são portas lógicas?

Portas lógicas são circuitos digitais que recebem valores binários e produzem uma saída de acordo com uma regra lógica.

As entradas e saídas são representadas por 0 e 1.

## 2. Porta AND (E)

A saída é 1 somente quando todas as entradas são 1.

| A | B | A AND B |
|---:|---:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## 3. Porta OR (OU)

A saída é 1 quando pelo menos uma entrada é 1.

| A | B | A OR B |
|---:|---:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

## 4. Porta NOT (NÃO)

A porta NOT inverte o valor da entrada.

| A | NOT A |
|---:|---:|
| 0 | 1 |
| 1 | 0 |

## 5. Porta XOR (OU exclusivo)

A saída é 1 quando as entradas são diferentes.

| A | B | A XOR B |
|---:|---:|---:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## 6. Portas NAND e NOR

- NAND: resultado da AND invertido.
- NOR: resultado da OR invertido.

Exemplo: se A = 1 e B = 1, AND produz 1 e NAND produz 0.

## 7. Exemplo de expressão lógica

Considere:

S = (A AND B) OR C

Se A = 1, B = 0 e C = 1:

1. A AND B = 1 AND 0 = 0.
2. S = 0 OR 1.
3. Resultado final: S = 1.

## Resumo

AND produz 1 quando todas as entradas são 1. OR produz 1 quando pelo menos uma entrada é 1. NOT inverte a entrada. XOR produz 1 quando as entradas são diferentes. NAND e NOR são versões invertidas de AND e OR.

## Exercícios

1. Calcule `0 AND 1`.
2. Calcule `0 OR 0`.
3. Calcule `NOT 1`.
4. Calcule `1 XOR 0`.
5. Calcule `(1 AND 0) OR 1`.
