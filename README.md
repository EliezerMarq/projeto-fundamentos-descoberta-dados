# 📊 Fundamentos da Descoberta de Dados — Supermercado do Chile

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do curso de Ciência de Dados da EBAC, no módulo de Fundamentos da Descoberta de Dados.

O objetivo foi realizar uma análise exploratória de uma base de produtos de um supermercado do Chile, aplicando conceitos de estatística descritiva e visualização de dados utilizando Python.

## 🎯 Objetivos

- Explorar a base de dados de produtos;
- Analisar os preços dos produtos por categoria;
- Comparar média e mediana;
- Analisar a dispersão dos preços através do desvio padrão;
- Identificar possíveis outliers;
- Analisar os descontos praticados;
- Comparar categorias e marcas;
- Criar visualizações estáticas e interativas.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Plotly
- Jupyter Notebook

## 📊 Análises realizadas

### 1. Média e mediana dos preços

Foi realizada uma análise da média e da mediana da coluna `Preco_Normal` agrupada por categoria.

A comparação entre essas duas medidas permitiu identificar categorias em que valores elevados influenciam significativamente a média.

### 2. Desvio padrão

Foi calculado o desvio padrão dos preços por categoria para avaliar a dispersão dos dados.

A categoria `lacteos` apresentou o maior desvio padrão, indicando uma maior variabilidade dos preços.

### 3. Boxplot

Foi utilizado um boxplot para analisar a distribuição dos preços da categoria com maior desvio padrão e identificar possíveis valores discrepantes (outliers).

### 4. Média de descontos

Foi criado um gráfico de barras para comparar a média de descontos entre as diferentes categorias de produtos.

### 5. Visualização interativa

Foi criado um treemap utilizando Plotly para analisar a relação entre:

- Categoria;
- Marca;
- Média de desconto.

## 🔎 Principais insights

A análise mostrou diferenças significativas entre as categorias de produtos.

A categoria `lacteos` apresentou o maior desvio padrão, indicando grande dispersão nos preços.

Além disso, a diferença entre média e mediana nessa categoria sugere a influência de produtos com preços elevados na média.

A utilização de visualizações permitiu identificar padrões e possíveis outliers que seriam mais difíceis de perceber apenas através das estatísticas descritivas.

## 📁 Estrutura do projeto

```text
projeto-fundamentos-descoberta-dados/
│
├── M13_Projeto_Supermercado_Chile.ipynb
├── MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv
└── README.md
