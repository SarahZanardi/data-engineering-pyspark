# Spark - Data Engineering 🚀

Este projeto tem como objetivo apresentar conceitos fundamentais de engenharia de dados utilizando **Apache Spark** com **PySpark**, explorando os recursos do ambiente **Databricks**.

## Conteúdo

### 🔍 Conhecendo um notebook no Databricks
Introdução ao ambiente Databricks: como utilizar notebooks, executar células de código, configurar clusters e navegar pela interface.

### 🧱 PySpark DataFrame
Explicação sobre a estrutura de dados principal do Spark: os DataFrames. Comparação com Pandas e suas vantagens em ambientes distribuídos.

### 📂 Lendo um dataset
Demonstração de como carregar datasets em formatos como CSV, Parquet e JSON em DataFrames com `spark.read`.

### 🧬 Checando os datatypes de algumas colunas
Uso do método `.printSchema()` e inspeção dos tipos de dados de colunas específicas.

### 🧮 Selecionando colunas e índices
Exemplos de seleção de colunas usando `.select()` e filtragem de linhas com `.filter()` e `.where()`.

### 📊 Visualizando estatísticas descritivas
Utilização de métodos como `.describe()` e `.summary()` para obter estatísticas básicas do conjunto de dados.

### ➕ Adicionando colunas em DataFrames
Como criar novas colunas a partir de expressões, funções e colunas existentes com `.withColumn()`.

### ➖ Removendo colunas em DataFrames
Remoção de colunas usando `.drop()` para otimizar e preparar os dados.

### ✏️ Renomeando colunas em DataFrames
Renomeação com `.withColumnRenamed()` para melhor legibilidade ou padronização.

### ⚠️ Trabalhando com missing values
Técnicas para identificar, remover ou imputar valores ausentes usando funções como `.dropna()`, `.fillna()` e `.na`.

---

## 💻 Requisitos

- Conta no [Databricks](https://databricks.com/)
- Conhecimentos básicos de Python
- Familiaridade com SQL é um diferencial

## 📎 Referências

- [Documentação oficial do PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Documentação do Databricks](https://docs.databricks.com/)

---


