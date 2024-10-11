# Análise de Score de Cliente em um Banco

## Descrição

Este projeto tem como objetivo realizar uma análise do score de clientes em um banco, utilizando técnicas de classificação para prever se um cliente é considerado um bom ou mau pagador. Através da análise de dados, o projeto busca auxiliar o banco em suas decisões de concessão de crédito.

## Objetivos

- Importar a base de dados de clientes.
- Verificar e tratar dados ausentes.
- Criar algoritmos de classificação para prever scores de clientes.
- Identificar o melhor modelo de classificação.
- Analisar as características que influenciam o score do cliente.

## Tecnologias Utilizadas

- Python
- Pandas
- Scikit-Learn

## Passos do Projeto

1. **Importação da Base de Dados**: Utilizando a biblioteca Pandas para carregar e visualizar os dados.
2. **Tratamento de Dados**: Verificação de valores vazios e transformação de colunas de texto em numéricas, usando `LabelEncoder` da Scikit-Learn.
3. **Divisão da Base**: Separação dos dados em conjuntos de treino e teste.
4. **Treinamento de Modelos**: Implementação de algoritmos de classificação, como Árvore de Decisão e K-Nearest Neighbors (KNN).
5. **Avaliação dos Modelos**: Cálculo da acurácia dos modelos para determinar qual apresenta o melhor desempenho.
6. **Análise de Importância**: Identificação das características mais relevantes que influenciam o score de crédito dos clientes.

## Resultados

O modelo de Árvore de Decisão obteve uma acurácia de 82%, enquanto o modelo KNN teve 74%. Esses resultados indicam que a Árvore de Decisão é a melhor opção para prever scores de crédito.

## Conclusão

O projeto demonstra a importância do tratamento e análise de dados para obter resultados significativos. Além disso, revela como modelos de classificação podem ser utilizados para prever comportamentos e tomar decisões mais informadas.
