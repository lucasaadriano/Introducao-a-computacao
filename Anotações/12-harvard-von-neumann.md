# 12 — Arquiteturas Harvard e Von Neumann

## 1. O que é arquitetura de computador?

A arquitetura de um computador descreve características fundamentais de sua organização e funcionamento, incluindo a maneira como a CPU acessa instruções e dados.

Duas arquiteturas estudadas em computação são Harvard e Von Neumann.

## 2. Arquitetura Von Neumann

Na organização clássica Von Neumann, as instruções dos programas e os dados compartilham a mesma memória principal.

### Exemplo

Um programa possui uma instrução para somar dois números. A memória mantém as instruções e os dados necessários, e a CPU busca as informações para executar a operação.

### Gargalo de Von Neumann

Como instruções e dados compartilham recursos de comunicação na organização clássica, o acesso a eles pode disputar os mesmos caminhos. Essa limitação é conhecida como gargalo de Von Neumann.

## 3. Arquitetura Harvard

Na arquitetura Harvard, instruções e dados utilizam memórias separadas. Tradicionalmente, também possuem caminhos de acesso separados.

Essa organização pode permitir que instruções e dados sejam acessados de forma independente.

## 4. Comparação

| Característica | Von Neumann clássica | Harvard clássica |
|---|---|---|
| Memória de instruções e dados | Compartilhada | Separada |
| Caminhos de acesso | Compartilhados | Separados |
| Acesso independente | Mais limitado pela organização compartilhada | Pode ocorrer por caminhos separados |

Sistemas modernos podem combinar características das duas arquiteturas.

## 5. Exemplo para memorizar

Imagine uma biblioteca com uma única fila para consultar livros e documentos. Isso lembra a organização compartilhada de Von Neumann.

Agora imagine duas filas independentes: uma para instruções e outra para dados. Isso lembra a organização Harvard.

Essa comparação é apenas uma analogia para facilitar o entendimento.

## Resumo

Na arquitetura Von Neumann clássica, instruções e dados compartilham a memória principal. Na arquitetura Harvard, instruções e dados utilizam memórias separadas.

## Exercícios

1. Qual arquitetura utiliza memória compartilhada para instruções e dados?
2. Qual arquitetura separa as memórias de instruções e dados?
3. O que é o gargalo de Von Neumann?
4. Por que sistemas modernos podem combinar características das duas arquiteturas?
