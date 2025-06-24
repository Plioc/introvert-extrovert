# introvert-extrovert

# Análise de Comportamento: Extrovertidos vs. Introvertidos

Este projeto tem como objetivo analisar padrões comportamentais entre indivíduos extrovertidos e introvertidos com base em um conjunto de dados do Kaggle. A análise envolve limpeza, tratamento de dados, visualizações e aplicação de algoritmos de aprendizado supervisionado para prever a personalidade com base em comportamentos observados.

---

## 📂 Dados

O dataset utilizado foi retirado do Kaggle:

🔗 [Extrovert vs Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)

O conjunto de dados contém variáveis como:
- Tempo gasto sozinho
- Frequência de eventos sociais
- Ansiedade em público
- Comportamento em redes sociais

---

## 🔧 Tecnologias e Ferramentas

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (KNNImputer, PCA, DecisionTree, LogisticRegression, RandomForest)
- Jupyter Notebook
- HTML + CSS (visualização web)
- GitHub Pages (publicação)

---

## 🧼 Limpeza e Pré-processamento

- Tratamento de dados faltantes com KNNImputer (numéricos)
- Preenchimento de dados categóricos com moda por grupo de personalidade
- Normalização com MinMaxScaler
- Separação entre extrovertidos e introvertidos para análises comparativas

---

## 📊 Visualizações

- Boxplots comparativos
- Matriz de correlação
- Análise PCA (redução de dimensionalidade)
- Fronteiras de decisão dos modelos (visualização com PCA)

---

## 🤖 Modelos Supervisionados

Três modelos foram testados:

- 🔹 **Regressão Logística**: 93% de acurácia
- 🌳 **Árvore de Decisão**: 86% de acurácia
- 🌲 **Random Forest**: 91% de acurácia

A Regressão Logística apresentou o melhor desempenho geral.

---

## 🧾 Conclusão

A análise mostrou que existem padrões consistentes que permitem distinguir introvertidos de extrovertidos com base em seus comportamentos. Os modelos supervisionados alcançaram boa acurácia, indicando que é possível prever a personalidade a partir de dados comportamentais.

---

## 🌐 Publicação

O projeto completo pode ser acessado neste link (via GitHub Pages):

🔗 [Veja a versão online do projeto](https://seu-usuario.github.io/seu-repo/)  
*(Substitua pelo link real depois que publicar)*

---

## 📌 Como Executar

1. Clone o repositório
2. Instale as dependências necessárias (pandas, scikit-learn, etc.)
3. Execute o notebook Jupyter para acompanhar a análise passo a passo

