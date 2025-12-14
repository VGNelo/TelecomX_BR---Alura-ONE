Telecom X – Análise de Evasão de Clientes
=========================================

Este repositório contém o notebook desenvolvido para o projeto de churn da Telecom X, com foco em entender os fatores que levam à evasão e apoiar a criação de estratégias de retenção. O trabalho foi realizado em Google Colab, utilizando Python e bibliotecas de análise de dados.

Objetivo
--------
- Coletar e tratar dados de clientes.
- Realizar análise exploratória de dados (EDA).
- Extrair insights estratégicos que orientem ações de retenção.
- Preparar o dataset para futuras etapas de modelagem preditiva.

Tecnologias Utilizadas
----------------------
- Python 3
- Pandas
- Matplotlib / Seaborn
- Google Colab
- GitHub

Estrutura do Repositório
------------------------
TelecomX_Churn/
│
├── notebooks/
│   └── TelecomX_Churn.ipynb   # Notebook principal (ETL + EDA + Insights)
├── data/
│   └── telecomx_clean.csv     # Dataset tratado e pronto para modelagem
└── README.md                  # Documentação do projeto

Pipeline de Trabalho
--------------------
1. ETL (Extração, Transformação e Carga)
   - Extração de dados via API/JSON.
   - Padronização de colunas e tratamento de nulos.
   - Exportação do dataset limpo.

2. EDA (Exploração de Dados)
   - Distribuição de churn.
   - Segmentação por contrato, tipo de internet e perfil demográfico.
   - Visualizações para identificar padrões e tendências.

3. Insights Estratégicos
   - Contratos mensais apresentam maior risco de churn.
   - Clientes com fibra óptica tendem a cancelar mais que DSL.
   - Idosos e clientes sem dependentes têm maior probabilidade de evasão.
   - Pagamentos digitais reduzem churn.

Próximos Passos
---------------
- Construção de modelos preditivos (Logistic Regression, Random Forest, XGBoost).
- Avaliação de métricas: AUC, Recall, Precision.
- Implementação de sistema de alerta para clientes com alto risco de churn.

Autor
-----
Projeto desenvolvido por Valdemir como parte do desafio de Data Science da Telecom X.
