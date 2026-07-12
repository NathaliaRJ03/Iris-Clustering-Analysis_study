# 🌸 Iris Clustering - Unsupervised Machine Learning

Este projeto apresenta a aplicação de algoritmos de **Aprendizado de Máquina Não Supervisionado (Unsupervised Machine Learning)** utilizando o famoso conjunto de dados **Iris**. O objetivo é comparar diferentes técnicas de clusterização e analisar como cada algoritmo agrupa os dados sem utilizar os rótulos das espécies durante o treinamento.

## 📌 Objetivos

* Carregar e explorar o conjunto de dados Iris.
* Aplicar diferentes algoritmos de clusterização.
* Comparar os resultados obtidos entre os modelos.
* Avaliar a qualidade dos agrupamentos utilizando matrizes de confusão.
* Visualizar os clusters gerados por cada algoritmo.
* Construir um dendrograma para análise da clusterização hierárquica.

---

## 📊 Dataset

O projeto utiliza o **Iris Dataset**, disponibilizado pela biblioteca **Scikit-Learn**, contendo:

* 150 amostras
* 3 espécies de flores

  * Setosa
  * Versicolor
  * Virginica
* 4 atributos numéricos

  * Comprimento da sépala
  * Largura da sépala
  * Comprimento da pétala
  * Largura da pétala

---

## 🤖 Algoritmos Utilizados

### K-Means

* Clusterização baseada em centróides.
* Definição de **3 clusters**.
* Comparação dos grupos encontrados com as classes reais.

### DBSCAN

* Clusterização baseada em densidade.
* Identificação automática de regiões densas.
* Detecção de possíveis ruídos (outliers).

### Agglomerative Clustering

* Clusterização Hierárquica Aglomerativa.
* Formação de grupos por meio da união sucessiva dos dados.
* Construção do dendrograma utilizando o método de Ward.

---

## 📈 Avaliação

Para comparar os agrupamentos encontrados com as classes reais do dataset, foram utilizadas:

* Confusion Matrix
* Visualização gráfica dos clusters
* Dendrograma Hierárquico

---

## 🛠️ Tecnologias

* Python
* Scikit-Learn
* NumPy
* Matplotlib
* SciPy

---

## 📚 Conceitos Aplicados

* Unsupervised Machine Learning
* Clusterização
* K-Means
* DBSCAN
* Agglomerative Clustering
* Hierarchical Clustering
* Dendrogram
* Confusion Matrix
* Data Visualization

---

## 📂 Estrutura do Projeto

```
├── Clusters.ipynb
├── README.md
```

---

## 🚀 Resultados

Durante o desenvolvimento foram realizadas:

* Exploração do conjunto de dados Iris.
* Implementação dos algoritmos K-Means, DBSCAN e Agglomerative Clustering.
* Comparação dos agrupamentos encontrados.
* Avaliação dos modelos utilizando matrizes de confusão.
* Visualização dos clusters.
* Construção e interpretação do dendrograma para análise hierárquica dos dados.

---

## 🎯 Objetivo do Projeto

Este projeto faz parte dos meus estudos em **Ciência de Dados** e **Machine Learning**, com foco na compreensão de técnicas de **aprendizado não supervisionado**, comparação de algoritmos de clusterização e interpretação dos resultados obtidos em diferentes abordagens.

---

**Desenvolvido por Nathalia Duarte**
