# Laptop Price Prediction

## Descrição

Este projeto foi desenvolvido para a disciplina Projeto Aplicado II do curso de Banco de Dados da Universidade Presbiteriana Mackenzie.

A proposta consiste em desenvolver uma análise preditiva de preços de laptops, utilizando técnicas de análise exploratória de dados (EDA) e aprendizado de máquina.

Os dados utilizados foram obtidos a partir de uma base pública do Kaggle, contendo especificações técnicas detalhadas e preços, em euros, de aproximadamente 1.146 modelos de laptops.

Dataset: https://www.kaggle.com/datasets/abdelrahmanemad594/laptop-prices/data

---

## Contexto

Este projeto é desenvolvido no contexto da empresa fictícia DataPrice Analytics, especializada em análise de dados e inteligência de mercado no setor de tecnologia.

A empresa atua apoiando varejistas e fabricantes na definição de estratégias de precificação, utilizando modelos preditivos baseados em dados históricos.

O objetivo é gerar insights estratégicos sobre a formação de preços no mercado de laptops e desenvolver um modelo aplicável ao ambiente de negócios.

---

## Objetivo

Desenvolver um modelo preditivo capaz de estimar o preço de laptops com base em suas especificações técnicas, além de identificar quais características possuem maior impacto na formação do preço.

---

## Perguntas de Negócio

- Quais características técnicas mais influenciam o preço de um laptop?
- É possível prever o preço com base nas especificações do equipamento?
- Qual modelo de regressão apresenta melhor desempenho na predição?

---

## Etapas do Projeto

### 1. Aquisição e Preparação dos Dados

- Leitura do dataset em formato CSV  
- Remoção de colunas irrelevantes  
- Conversão de variáveis (ex: RAM e frequência da CPU) para formato numérico  
- Tratamento de valores ausentes  
- Padronização dos dados  

---

### 2. Análise Exploratória de Dados (EDA)

- Análise da distribuição dos preços  
- Identificação de outliers  
- Análise de correlação entre variáveis  
- Visualizações para entendimento dos dados  

---

### 3. Modelagem Preditiva

- Regressão Linear (baseline)  
- Random Forest  
- XGBoost  

Comparação de desempenho entre os modelos.

---

## Tecnologias Utilizadas

- Python  
- pandas  
- numpy  
- matplotlib  
- scipy  
- scikit-learn  
- xgboost  

---

## Métricas de Avaliação

Os modelos são avaliados utilizando:

- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- R² (Coeficiente de Determinação)  

Também é utilizada validação cruzada com 5 folds para garantir maior robustez nos resultados.

---

## Estrutura do Projeto

```bash
laptop-prize-analysis/
│
├── data/
│   └── laptop_prices.csv
│
├── notebooks/
│   └── laptop_price_analysis.ipynb
│
├── docs/
│   └── relatorio_etapa_2.docx
│
└── README.md


## Integrantes e Instituição

Ryan Rodrigues Pereira  
Nour Hussein Barakat  
Guilherme de Araújo Espírito Santo  

Universidade Presbiteriana Mackenzie  
Curso: Banco de Dados  
Projeto Aplicado II — 2026  
