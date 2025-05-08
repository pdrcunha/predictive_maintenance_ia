# 🔧 Manutenção Preditiva: Pipeline de Dados com Python

Este projeto demonstra um pipeline completo de engenharia e ciência de dados aplicado a um cenário de **manutenção preditiva industrial**, utilizando o dataset público **[Machine Predictive Maintenance - Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)**.

---

## 🎯 Objetivo

Construir uma solução que:

1. 📥 **Carrega dados brutos** de sensores e registros de falhas (planilha CSV)
2. 🧼 **Realiza limpeza, normalização e enriquecimento** dos dados com Python
3. 🧠 **Treina um modelo simples de machine learning** para prever falhas
4. 📊 **Gera gráficos e visualizações empresariais** (dashboards locais)
5. 🛢️ **Salva os dados processados em um banco relacional** (opcional)

---

## 📂 Etapas do Pipeline

- **Leitura e ingestão de dados (ETL básico)**  
  - CSV → pandas
  - Limpeza de nulos, tipos e inconsistências
  - Conversão de tipos, padronização

- **Análise exploratória (EDA)**  
  - Distribuições, correlações, padrões

- **Visualização de insights**
  - Gráficos com `matplotlib`

- **Modelagem preditiva simples**
  - Regressão logística ou Random Forest
  - Avaliação com matriz de confusão e f1-score

- **Exportação de dados processados**
  - CSV limpo
  - Opcional: inserção no PostgreSQL ou SQLite

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.10+
- pandas
- numpy
- matplotlib
- scikit-learn (pip install -U scikit-learn) pois e uma lib compilada e não estou usando o conda
- joblib
- jupyter
- psycopg2 (para banco de dados)
- libpq-dev (apt install libpq-dev)


---

## 📈 Exemplos de Visualizações

- Frequência de falhas por tipo de máquina  
- Correlação entre sensores e falha  
- Importância das variáveis  
- Matriz de confusão do modelo preditivo  

---

