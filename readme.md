
## Previsão do Preço de Varejo Sugerido pelo Fabricante (MSRP) de Carros

# Objetivo

O objetivo deste projeto de ciência de dados é desenvolver um modelo preditivo para estimar o Preço de Varejo Sugerido pelo Fabricante (MSRP) de carros. Previsões precisas de preços são cruciais tanto para fabricantes como para consumidores, permitindo uma melhor tomada de decisões em termos de produção, marketing e compras.

# Metodologia

Neste projeto, utilizamos o PySpark, uma poderosa estrutura de processamento de dados, para analisar e modelar as relações entre várias características do carro e seus preços. A seguir, um resumo da metodologia:


1. Pré-processamento de dados:

Limpamos e pré-processamos os dados para lidar com valores ausentes e inconsistências.
Normalizamos as variáveis numéricas para melhorar o desempenho do modelo.

2. Treinamento do modelo:

Treinamos um modelo de RandomForestRegressor usando o PySpark.
O modelo é treinado para prever o MSRP de um carro com base em suas características.

3. Avaliação do modelo:

Avaliei o desempenho do modelo usando métricas como R² e RMSE.
