
# Projeto de Detecção de Fraudes em Cartões de Crédito

## Descrição
Este projeto utiliza um dataset de transações com cartões de crédito para identificar transações fraudulentas utilizando Python e várias bibliotecas de machine learning. O dataset contém transações que ocorreram em dois dias, onde temos 492 fraudes em 284,807 transações.

## Bibliotecas Utilizadas
- Pandas para manipulação de dados.
- Seaborn e Matplotlib para visualizações.
- Imbalanced-learn para balanceamento de dados.
- Scikit-learn para modelagem e avaliação.

## Processo
1. **Carregamento de Dados**: Os dados são carregados e examinados para valores nulos.
2. **Exploração de Dados**: Visualizações são criadas para entender a distribuição das classes e correlações entre características.
3. **Preparação de Dados**: Os dados são balanceados usando SMOTE para lidar com a desigualdade na distribuição das classes.
4. **Divisão de Dados**: O conjunto de dados é dividido em conjuntos de treino e teste.
5. **Modelagem**: Três modelos são treinados para prever transações fraudulentas:
   - Árvore de Decisão
   - Floresta Aleatória
   - Regressão Logística
6. **Avaliação**: Os modelos são avaliados com base em relatórios de classificação e curvas ROC.

## Resultados
Os modelos são comparados para escolher o melhor com base no desempenho de previsão e métricas AUC-ROC.

## Como Executar
Instale as dependências e execute o Jupyter Notebook para reproduzir a análise e os resultados.

## Fontes
- Dataset: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
