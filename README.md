# 🧬 Predição de Diabetes com Machine Learning

Este projeto tem como objetivo desenvolver um sistema de apoio à decisão capaz de identificar indivíduos com risco elevado de desenvolver diabetes, a partir de dados clínicos e comportamentais.

Utilizando técnicas de Machine Learning supervisionado, foram treinados, avaliados e comparados diferentes modelos preditivos, com foco em aplicações de triagem populacional e prevenção de doenças crônicas não transmissíveis.

O projeto foi estruturado seguindo boas práticas de ciência de dados, incluindo validação cruzada, otimização de hiperparâmetros, tratamento de desbalanceamento de classes e avaliação robusta de desempenho.

## Objetivo

Construir e avaliar modelos de classificação supervisionada capazes de prever o diagnóstico de diabetes, priorizando:

- Alta sensibilidade (recall), minimizando falsos negativos
- Boa capacidade discriminativa (ROC-AUC)
- Equilíbrio entre precisão e recall (F1-score)

## 🗂 Dataset

Base de dados utilizada:  
**CDC Behavioral Risk Factor Surveillance – Diabetes Health Indicators**
Link direto: [CDC Diabetes Health Indicators](https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators)

- **Registros:** Dados anonimizados de cidadãos entrevistados
- **Variável alvo:** Diagnóstico de diabetes (binário)
- **Features:** Indicadores clínicos, comportamentais e demográficos

## Metodologia

O pipeline de desenvolvimento seguiu as seguintes etapas:

1. Entendimento do problema e formulação da abordagem
2. Limpeza e pré-processamento
3. Seleção automática de atributos
4. Balanceamento das classes com SMOTE
5. Treinamento e otimização de modelos
6. Validação cruzada estratificada
7. Avaliação final e comparação de desempenho

## Técnicas Utilizadas

- **Pré-processamento:** StandardScaler
- **Balanceamento:** SMOTE
- **Modelos avaliados:**
  - Regressão Logística
  - K-Nearest Neighbors (KNN)
- **Otimização:** GridSearch + Validação Cruzada Estratificada
- **Métricas:**
  - Precision
  - Recall
  - F1-score
  - ROC-AUC

### Interpretação

O modelo demonstrou elevada capacidade de identificar corretamente indivíduos com risco de diabetes, sendo especialmente adequado para aplicações de **triagem inicial em saúde**, onde a minimização de falsos negativos é prioritária.

Apesar da presença de falsos positivos, o desempenho geral indica que a solução pode atuar como ferramenta eficiente de apoio à decisão, auxiliando na priorização de exames e intervenções preventivas.
