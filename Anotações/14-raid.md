# 14 — RAID

## 1. O que é RAID?

RAID significa *Redundant Array of Independent Disks*, expressão que pode ser traduzida como conjunto redundante de discos independentes.

É uma técnica que combina vários dispositivos de armazenamento para buscar objetivos como desempenho, redundância ou tolerância a falhas.

## 2. Por que utilizar RAID?

Dependendo da configuração, RAID pode oferecer:

- **Desempenho:** distribuir operações entre discos.
- **Redundância:** manter cópias ou informações adicionais para recuperação.
- **Disponibilidade:** permitir que o sistema continue funcionando após determinadas falhas.

RAID não substitui backups. Erros humanos, malware e outros incidentes podem afetar todos os discos de um conjunto.

## 3. RAID 0

RAID 0 distribui os dados entre dois ou mais discos. Essa técnica é chamada de *striping*.

**Vantagem:** pode melhorar o desempenho e combinar a capacidade dos discos.

**Desvantagem:** não oferece redundância. A falha de um disco pode causar a perda dos dados do conjunto.

Exemplo: dois discos de 1 TB podem oferecer aproximadamente 2 TB de capacidade nominal em RAID 0.

## 4. RAID 1

RAID 1 mantém cópias dos dados em dois ou mais discos. Essa técnica é chamada de espelhamento (*mirroring*).

**Vantagem:** a cópia pode permitir que o sistema continue funcionando após a falha de um disco.

**Desvantagem:** a capacidade útil é menor do que a soma das capacidades dos discos espelhados.

Exemplo: dois discos de 1 TB em RAID 1 oferecem aproximadamente 1 TB de capacidade útil.

## 5. RAID 5

RAID 5 distribui dados e informações de paridade entre pelo menos três discos.

A paridade ajuda a reconstruir os dados quando um disco falha.

Características:

- Exige pelo menos três discos.
- Pode tolerar a falha de um disco.
- Reserva parte da capacidade para a paridade.

Exemplo: três discos de 1 TB em RAID 5 oferecem aproximadamente 2 TB de capacidade útil.

## 6. RAID 6

RAID 6 utiliza dupla paridade distribuída e exige pelo menos quatro discos.

Pode tolerar a falha de até dois discos simultaneamente, dentro das condições previstas por esse nível RAID.

Exemplo: quatro discos de 1 TB em RAID 6 oferecem aproximadamente 2 TB de capacidade útil.

## 7. Comparação

| Nível | Técnica principal | Mínimo de discos | Tolerância a falhas |
|---|---|---:|---|
| RAID 0 | Distribuição de dados | 2 | Não tolera falha de disco sem perda do conjunto |
| RAID 1 | Espelhamento | 2 | Pode tolerar a falha de um disco em um espelho de dois discos |
| RAID 5 | Distribuição com paridade | 3 | Pode tolerar a falha de um disco |
| RAID 6 | Distribuição com dupla paridade | 4 | Pode tolerar a falha de dois discos |

## 8. RAID é a mesma coisa que backup?

Não.

RAID organiza dispositivos de armazenamento para melhorar o desempenho ou manter o funcionamento diante de determinadas falhas de disco.

Backup é uma cópia independente dos dados, utilizada para recuperá-los após perda, exclusão acidental, corrupção ou outros incidentes.

RAID e backup podem ser utilizados juntos, pois resolvem problemas diferentes.

## Resumo

RAID combina dispositivos de armazenamento para obter diferentes benefícios. RAID 0 prioriza desempenho e capacidade; RAID 1 utiliza espelhamento; RAID 5 utiliza paridade simples; RAID 6 utiliza dupla paridade.

## Exercícios

1. Qual nível RAID não oferece redundância?
2. Qual é a técnica principal do RAID 1?
3. Quantos discos são necessários, no mínimo, para RAID 5?
4. Qual é a diferença entre RAID 5 e RAID 6?
5. Por que RAID não substitui backup?
