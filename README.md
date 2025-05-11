# 🔧 Manutenção Preditiva: Análise Exploratória de Dados com Python

Este projeto demonstra um pipeline básico de **tratamento e análise exploratória de dados (EDA)** aplicado a um cenário de **manutenção preditiva industrial**, utilizando o dataset público **[Machine Predictive Maintenance - Classification](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)**.

----------

## 🎯 Objetivo

Construir uma solução que:

1.  📥 **Carrega os dados brutos** de sensores e registros de falhas (arquivo CSV)
    
2.  🧼 **Realiza tratamento e limpeza dos dados** com Python
    
3.  📊 **Gera gráficos com matplotlib** para análise e descoberta de padrões
    

----------

## 📂 Etapas do Pipeline

-   **Leitura e tratamento dos dados**
    
    -   Carregamento do CSV com pandas
        
    -   Conversão de tipos e limpeza de dados nulos ou inconsistentes
        
-   **Análise exploratória (EDA)**
    
    -   Distribuição de variáveis numéricas e categóricas
        
    -   Relações bivariadas (ex: Torque vs Rotational Speed)
        
    -   Correlações entre variáveis
        
    -   Visualização de outliers
        
-   **Visualização**
    
    -   Gráficos com `matplotlib` para interpretação de padrões e relações
        
    -   Análises com suporte estatístico (ex: correlação de Pearson)
        

----------

## 🛠️ Tecnologias e Bibliotecas

-   Python 3.10+
    
-   pandas
    
-   numpy
    
-   matplotlib
    
-   jupyter (opcional para visualização interativa)
    

----------

## 📈 Exemplos de Análises

-   **Torque vs Velocidade de Rotação**: gráfico de dispersão e correlação
    
-   **Distribuição de Torque por Tipo de Produto**: boxplot
    
-   **Correlação entre sensores e falhas**
    
-   **Contagem de tipos de produto ou falha**