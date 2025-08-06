# Projeto de Análise de Evasão de Clientes

## Descrição

Este projeto tem como objetivo identificar os principais fatores que influenciam a evasão de clientes (churn) em uma empresa de serviços de telecomunicações. Utilizando técnicas de análise exploratória de dados e modelos de machine learning supervisionado, buscamos prever quais clientes têm maior probabilidade de cancelar seus serviços e propor estratégias eficazes de retenção.

---

## Etapas do Projeto

### 1. Carregamento e Preparação dos Dados
- Importação do conjunto de dados original
- Tratamento de valores ausentes
- Conversão de variáveis categóricas
- Normalização de variáveis numéricas (quando necessário)

### 2. Análise Exploratória
- Visualização da distribuição de churn
- Boxplots e scatter plots para investigar relações entre variáveis
- Matriz de correlação para variáveis numéricas

### 3. Divisão dos Dados
- Separação em conjuntos de treino e teste (80/20)
- Garantia de balanceamento entre classes (opcional: SMOTE)

### 4. Modelagem Preditiva
Modelos utilizados:
- Regressão Logística
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

Cada modelo foi treinado, testado e avaliado com métricas como:
- Acurácia
- Precisão
- Recall
- F1-score

### 5. Análise de Importância de Variáveis
- Coeficientes em modelos lineares (Logística, SVM)
- Importância por impureza (Random Forest)
- Permutation Importance (KNN)

### 6. Relatório Final
- Consolidação dos resultados dos modelos
- Identificação dos fatores mais relevantes para evasão
- Propostas de estratégias de retenção baseadas nos dados

---

## Principais Fatores Identificados

- Tipo de contrato (mensal aumenta risco de churn)
- Tempo de permanência (`tenure`)
- Gasto total (`TotalCharges`)
- Uso de serviços adicionais (backup, suporte técnico, streaming)
- Perfil demográfico (sem parceiro ou dependentes)

---

## Estratégias de Retenção Recomendadas

- Incentivar contratos de longo prazo
- Oferecer pacotes de serviços adicionais
- Engajar clientes nos primeiros meses
- Monitorar perfis com baixo gasto ou tempo de permanência
- Revisar política de cobrança eletrônica

---

## Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## Como Executar

1. Clone o repositório
2. Instale as dependências com `pip install -r requirements.txt`
3. Execute o notebook principal `churn_analysis.ipynb`
4. Siga as instruções e células para reproduzir a análise

---

## Autor

Estevão — Projeto desenvolvido com foco em análise preditiva e estratégias de retenção de clientes.
