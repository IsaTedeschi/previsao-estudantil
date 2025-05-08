# Análise de Desempenho Acadêmico com Técnicas de Balanceamento e Classificadores de Machine Learning

Este repositório contém o projeto de Trabalho de Conclusão de Curso (TCC), cujo objetivo foi analisar e prever o desempenho acadêmico de alunos com base em dados institucionais, utilizando diferentes técnicas de balanceamento de dados e algoritmos de classificação.

## 📌 Objetivo

Avaliar o impacto de técnicas de balanceamento em bases de dados desbalanceadas e comparar o desempenho de diversos classificadores de aprendizado de máquina na predição da **situação final dos alunos** (ex: Evadiu, Formado etc.), com base em variáveis como:

- Ano e período de ingresso no curso
- Ano e período de ingresso na disciplina 
- Média geral acadêmica (MGA)  
- Carga horária cursada
- Nota Final da disciplina

## ⚙️ Metodologia

1. **Pré-processamento dos dados**:
   - Limpeza e normalização
   - Transformação de atributos categóricos
   - Análise exploratória

2. **Balanceamento dos dados**:
   - OverSampling
   - Random Oversampler  
   - SMOTE (Synthetic Minority Over-sampling Technique)
   - Parâmetro Weight Class
   - Nenhuma técnica utilizada (NDA)
   

3. **Classificadores utilizados**:
   - Decision Tree  
   - Random Forest  
   - Logistic Regression
   - Linear Regression
   - Support Vector Machine (SVM)  
   - Multilayer Perceptron (MLP)
   - Naive Bayes

4. **Avaliação dos modelos**:
   - Acurácia  
   - Precisão  
   - Recall  
   - F1-Score  
   - Suporte  
   - ROC-AUC

## 📊 Resultados

Foram geradas **tabelas comparativas** e **gráficos** para visualizar o desempenho de cada classificador sob diferentes técnicas de balanceamento, permitindo analisar qual combinação ofereceu os melhores resultados para a base de dados estudada.

## 🛠️ Tecnologias e Bibliotecas

- Python  
- Pandas, NumPy, Scikit-learn, Matplotlib  
- imbalanced-learn  
- Jupyter Notebook  
- Arquivo CSV com dados acadêmicos anonimizados

