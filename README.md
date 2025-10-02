# Beta Bank - Previsão de Churn de Clientes

## Descrição do Projeto
Este projeto tem como objetivo prever a **evasão de clientes** do Beta Bank utilizando técnicas de **Machine Learning**. A partir de dados de comportamento dos clientes, buscamos identificar aqueles com maior risco de churn e fornecer insights estratégicos para retenção.

## Objetivos
- Construir modelos preditivos de churn com alta performance.
- Comparar diferentes algoritmos de classificação.
- Analisar o impacto de diferentes features no risco de evasão.
- Avaliar métricas de desempenho, priorizando **F1-score** e **AUC-ROC**.

## Dataset
O dataset contém informações sobre os clientes do Beta Bank, incluindo:
- Dados demográficos (idade, gênero, localização)
- Histórico de transações e movimentações financeiras
- Interações com produtos e serviços do banco
- Status de churn (cliente ativo ou evadido)

> Nota: Os dados utilizados neste projeto são fictícios ou anonimizados para fins de estudo.

## Metodologia
1. **Análise Exploratória de Dados (EDA)**  
   - Visualização de distribuições e correlações  
   - Identificação de valores ausentes e outliers

2. **Pré-processamento**  
   - Tratamento de valores faltantes  
   - Codificação de variáveis categóricas  
   - Normalização e padronização (StandardScaler)  

3. **Modelagem**  
   - Regressão Logística  
   - Árvore de Decisão  
   - Random Forest  
   - Gradient Boosting (LightGBM)

4. **Tratamento de Desbalanceamento**  
   - Oversampling (SMOTE)  
   - Undersampling  

5. **Avaliação de Modelos**  
   - F1-score, AUC-ROC  
   - Matriz de confusão  
   - Comparação de métricas entre modelos

## Resultados
- O modelo com melhor performance foi o **LightGBM**
- Features mais relevantes: `feature1`, `feature2`, `feature3`.  
- Insights estratégicos foram gerados para ações de retenção de clientes.

## Conclusão
O projeto demonstra como técnicas de Machine Learning podem auxiliar bancos a **identificar clientes em risco de churn** e implementar estratégias de retenção mais eficientes.

