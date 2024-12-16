# Conjectura de Collatz

Este repositório contém um projeto sobre a **Conjectura de Collatz**, que explora as sequências geradas a partir de números inteiros positivos e os analisa utilizando métricas estatísticas. O projeto inclui a geração das sequências de Collatz para os números de 1 a 10, a análise estatística dos dados gerados e a visualização gráfica dessas trajetórias.

## Descrição

A **Conjectura de Collatz** é um problema matemático que envolve uma sequência gerada a partir de um número inicial. A sequência é formada com as seguintes regras:
1. Se o número é par, divide-se por 2.
2. Se o número é ímpar, multiplica-se por 3 e soma-se 1.
3. O processo é repetido até que o número atinja 1.

O objetivo deste trabalho foi:
- Gerar as sequências de Collatz para os números de 1 a 10.
- Calcular e exibir métricas estatísticas como média, mediana, desvio padrão, valor mínimo e valor máximo de cada sequência.
- Visualizar as trajetórias das sequências por meio de um gráfico.

## Funcionalidades

1. **Geração das Sequências de Collatz**: 
   - Para cada número de 1 a 10, é gerada sua sequência de Collatz e a sequência é armazenada.

2. **Análise Estatística**:
   - Para cada sequência, são calculadas as seguintes métricas:
     - Média
     - Mediana
     - Desvio padrão
     - Valor mínimo
     - Valor máximo
     - Quantas interações até convergir?

3. **Visualização Gráfica**:
   - O gráfico exibe as trajetórias das sequências de Collatz para os números de 1 a 10.
   - Cada sequência é plotada no gráfico com o número de passos no eixo x e o valor da sequência no eixo y.

## Requisitos

- Python 3.x
- Bibliotecas:
  - `numpy`
  - `matplotlib`

