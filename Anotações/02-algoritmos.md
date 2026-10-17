# 02 — Algoritmos

## 1. O que é um algoritmo?

Um algoritmo é uma sequência organizada de passos utilizada para resolver um problema ou realizar uma tarefa.

Uma receita culinária é um exemplo de algoritmo, pois apresenta instruções em uma ordem específica.

Na computação, os algoritmos descrevem os passos necessários para resolver problemas.

## 2. Entrada, processamento e saída

- **Entrada:** dados fornecidos.
- **Processamento:** operações realizadas.
- **Saída:** resultado produzido.

## 3. Exemplo: calcular uma média

Considere duas notas: 8 e 6.

1. Receber as duas notas.
2. Somar as notas.
3. Dividir o resultado por 2.
4. Apresentar a média.

Cálculo:

Média = (8 + 6) / 2

Média = 14 / 2

Média = 7

## 4. Algoritmo em Python

```python
nota1 = 8
nota2 = 6

media = (nota1 + nota2) / 2

print(media)
```

Saída: `7.0`

## 5. Algoritmos com decisões

Podemos utilizar condições para escolher o que o programa fará.

```python
media = 7

if media >= 6:
    print("Aprovado")
else:
    print("Reprovado")
```

Como a média é 7, o programa apresenta `Aprovado`.

## 6. Algoritmos com repetição

Uma repetição permite executar instruções várias vezes.

```python
for numero in range(1, 4):
    print(numero)
```

Saída:

```text
1
2
3
```

## 7. Características de um algoritmo

- Clareza: os passos devem ser compreensíveis.
- Ordem: as instruções devem seguir uma sequência lógica.
- Precisão: cada instrução deve indicar o que fazer.
- Finitude: o algoritmo deve terminar.

## Resumo

Um algoritmo descreve como resolver um problema passo a passo. Um programa implementa essa lógica utilizando uma linguagem de programação.

## Exercícios

1. Escreva os passos para somar dois números.
2. Calcule a média de 7 e 9.
3. O que significa entrada, processamento e saída?
4. Para que serve uma condição `if`?
