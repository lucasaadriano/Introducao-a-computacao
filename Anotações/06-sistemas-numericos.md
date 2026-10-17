# 06 — Sistemas Numéricos

## 1. O que é um sistema numérico?

Um sistema numérico é uma forma de representar números utilizando símbolos e regras.

| Sistema | Base | Símbolos |
|---|---:|---|
| Decimal | 10 | 0 a 9 |
| Binário | 2 | 0 e 1 |
| Octal | 8 | 0 a 7 |
| Hexadecimal | 16 | 0 a 9 e A a F |

No hexadecimal, A representa 10, B representa 11, C representa 12, D representa 13, E representa 14 e F representa 15.

## 2. Binário para decimal

Cada posição representa uma potência de 2, começando pela direita com 2⁰.

Exemplo: converter `1011₂` para decimal.

1011₂ = 1 × 2³ + 0 × 2² + 1 × 2¹ + 1 × 2⁰

= 8 + 0 + 2 + 1

= 11₁₀

Resposta: `1011₂ = 11₁₀`.

## 3. Decimal para binário

Dividimos o número por 2 e anotamos os restos. Depois, lemos os restos de baixo para cima.

Exemplo: converter 13 para binário.

13 ÷ 2 = 6, resto 1  
6 ÷ 2 = 3, resto 0  
3 ÷ 2 = 1, resto 1  
1 ÷ 2 = 0, resto 1

Lendo os restos de baixo para cima:

`1101`

Resposta: `13₁₀ = 1101₂`.

## 4. Binário para hexadecimal

Agrupamos os bits de quatro em quatro, da direita para a esquerda.

Exemplo:

`11011010₂` → `1101 1010` → `D A`

Resposta: `11011010₂ = DA₁₆`.

## 5. Conversões em Python

```python
numero = 13

print(bin(numero))
print(hex(numero))
print(oct(numero))
```

Saída:

```text
0b1101
0xd
0o15
```

Os prefixos indicam binário, hexadecimal e octal, respectivamente.

## 6. Exercícios resolvidos

### Converter `1001₂` para decimal

1001₂ = 1 × 2³ + 0 × 2² + 0 × 2¹ + 1 × 2⁰

= 8 + 0 + 0 + 1

= 9₁₀

### Converter 10 para binário

10 ÷ 2 = 5, resto 0  
5 ÷ 2 = 2, resto 1  
2 ÷ 2 = 1, resto 0  
1 ÷ 2 = 0, resto 1

Resposta: `1010₂`.

## Resumo

O sistema decimal utiliza base 10, enquanto o binário utiliza base 2. Para converter binário em decimal, somamos as potências de 2 correspondentes aos bits iguais a 1. Para converter decimal inteiro positivo em binário, dividimos por 2 e lemos os restos de baixo para cima.

## Exercícios para praticar

1. Converta `111₂` para decimal.
2. Converta `10000₂` para decimal.
3. Converta 6 para binário.
4. Converta 15 para binário.
5. Converta `1111₂` para hexadecimal.
