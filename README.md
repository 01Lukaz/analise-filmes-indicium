# analise-filmes-indicium

# Desafio de Ciência de Dados - Análise Cinematográfica para PProductions

##  Descrição do Problema

Este projeto foi desenvolvido como parte do desafio para a vaga de Cientista de Dados da Indicium. O objetivo é realizar uma análise detalhada sobre um banco de dados cinematográfico para orientar o estúdio de Hollywood "PProductions" sobre qual tipo de filme deve ser o próximo a ser desenvolvido, visando maximizar o sucesso comercial e de crítica.

##  Dados Utilizados

O conjunto de dados principal, `imdb_top_1000.csv`, contém informações sobre os 1000 filmes mais bem avaliados no IMDb. As principais colunas incluem título, ano de lançamento, gênero, nota IMDb, faturamento (Gross), diretor e elenco.

## Objetivos do Projeto

A análise foi guiada para responder às seguintes questões de negócio:

1.  **Análise Exploratória (EDA):** Identificar as principais características e correlações entre as variáveis do dataset.
2.  **Recomendação de Filme:** Qual filme seria recomendado para uma pessoa aleatória?
3.  **Fatores de Faturamento:** Quais são os principais fatores que se relacionam com uma alta expectativa de faturamento?
4.  **Desempenho de Diretores:** Qual o desempenho médio dos diretores mais presentes no dataset?
5.  **Modelo Preditivo:** Construir um modelo de Machine Learning capaz de prever a nota IMDb de um filme com base em suas características.

##  Metodologia Aplicada

O projeto foi estruturado seguindo as seguintes etapas:

1.  **Limpeza e Pré-processamento:** Tratamento de valores ausentes (como na coluna `Gross`), remoção de caracteres desnecessários (como em `Runtime`) e conversão de tipos de dados para facilitar a análise.
2.  **Análise Exploratória de Dados (EDA):** Geração de visualizações para entender a distribuição dos dados, a relação entre faturamento, nota IMDb e gênero, e a performance de diretores e atores.
3.  **Engenharia de Features:** Criação de novas variáveis a partir das existentes para melhorar o desempenho do modelo (ex: one-hot encoding para a coluna `Genre`).
4.  **Modelagem Preditiva:** Treinamento e avaliação de múltiplos algoritmos de regressão (como Regressão Linear, Random Forest, etc.) para prever a nota IMDb. A performance foi medida utilizando as métricas RMSE (Root Mean Squared Error) e R² (R-squared).


