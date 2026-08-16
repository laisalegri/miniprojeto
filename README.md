# 📊 Mini-Projeto Avaliativo — Análise de Dados de Varejo

Projeto desenvolvido como parte do **Mini-Projeto Avaliativo — Módulo 1 — Semana 07**, do curso **Carreira Tech — Trilha Análise de Dados — Manipulação de Dados com Python e SQL**, do programa SCTEC.

**Aluna:** Laís Kugik Varela Alegri  
**Turma:** 05

---

## 🎯 Objetivo

Realizar uma **Análise Exploratória de Dados (AED)** aplicada a uma base de dados de varejo, colocando em prática conhecimentos de manipulação, limpeza, exploração e visualização de dados utilizando Python.

O projeto busca transformar dados brutos em informações úteis para identificar padrões, inconsistências e possíveis insights que possam auxiliar áreas de negócio e gestão na tomada de decisões baseadas em dados.

---

## 📁 Dataset

A análise foi realizada utilizando uma base de dados de varejo disponibilizada pelo **Kaggle**, contendo informações relacionadas às vendas, clientes, produtos, categorias e características dos consumidores.

https://www.kaggle.com/datasets/namespaiva/base-varejo/data 

Durante o projeto foram analisados dados referentes ao período de **2019 a 2022**.

---

## 🛠️ Tecnologias e bibliotecas utilizadas

- 🐍 **Python**
- 🐼 **Pandas** — manipulação e análise dos dados
- 🔢 **NumPy** — cálculos estatísticos e operações com arrays
- 📊 **Matplotlib** — criação dos gráficos
- 🎨 **Seaborn** — visualização de dados
- 📓 **Jupyter Notebook / Google Colab**
- 🔀 **Git e GitHub** — versionamento e disponibilização do projeto

---

## 🔎 Etapas do projeto

### 1. Carregamento dos dados

A base `Base Varejo.csv` foi carregada utilizando o Pandas e foram verificadas:

- quantidade de registros;
- quantidade de colunas;
- nomes das colunas;
- tipos de dados;
- informações gerais do DataFrame.

Também foi explorada a leitura do arquivo utilizando o módulo nativo `csv` do Python.

### 2. Limpeza e tratamento dos dados

Foram realizadas algumas etapas de preparação da base:

- identificação de valores ausentes;
- remoção de colunas completamente vazias;
- identificação e remoção de registros duplicados;
- tratamento de inconsistências;
- conversão da coluna de data para o tipo `datetime`;
- renomeação das colunas para facilitar a interpretação dos dados.

Durante o processo foram identificadas e removidas **96.553 linhas duplicadas**.

Também foi identificado um produto com código **107** sem identificação de nome e categoria.

### 3. Estatística descritiva

Foi realizada uma análise estatística da coluna referente à **quantidade de filhos dos clientes**, utilizando medidas como:

- média;
- mediana;
- moda;
- desvio padrão;
- mínimo;
- máximo;
- quartis;
- quantidade de registros.

### 4. Análise exploratória

Foram utilizadas funções de agrupamento, como `groupby()`, para investigar diferentes aspectos das vendas.

As principais análises foram:

- quantidade de vendas por ano;
- quantidade de vendas por mês;
- comparação das vendas entre 2021 e 2022;
- produtos mais vendidos por classe econômica;
- quantidade de vendas por gênero;
- quantidade de vendas por gênero e classe econômica;
- categorias com maior número de vendas.

---

## 📈 Principais insights

A análise permitiu identificar alguns padrões relevantes na base:

- 📅 O período analisado compreende os anos de **2019 a 2022**.
- 🏆 **2021** foi o ano com o maior número de vendas.
- 📉 **2022** apresentou o menor número de vendas.
- 👩 Considerando os valores gerais, **as mulheres realizaram mais compras que os homens**.
- 👔 Ao segmentar por classe econômica, entretanto, **os homens realizaram mais compras na classe A**.
- 💰 A **classe econômica B** apresentou o maior número de vendas.
- 🥩 O produto **"PRESUNTO COZIDO"** foi o mais vendido em todas as classes econômicas.
- 🛒 A categoria com o maior número de vendas foi **"ALIMENTOS"**.
- ⚠️ O produto de código **107** apresenta ausência de identificação de nome e categoria.
- 🧹 Foram removidas **96.553 linhas duplicadas** durante a limpeza da base.

---

## 📊 Visualizações

Foram desenvolvidos gráficos para auxiliar na interpretação dos resultados, incluindo:

- quantidade de vendas por ano;
- quantidade de vendas por mês;
- comparação mensal entre 2021 e 2022;
- produtos mais vendidos por classe econômica;
- quantidade de vendas por gênero;
- quantidade de vendas por gênero e classe econômica;
- Top 5 categorias com maior número de vendas.

---

## 📂 Estrutura do projeto

```text
miniprojeto/
│
├── dataset/
│   └── Base Varejo.csv
│
├── miniprojeto_lais.ipynb
│
└── README.md
```

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

No terminal do VS Code, execute:

```bash
git clone https://github.com/laisalegri/miniprojeto.git
```

### 2. Acesse a pasta do projeto

```bash
cd miniprojeto
```

### 3. Abra o notebook

Abra o arquivo:

```text
miniprojeto_lais.ipynb
```

e execute as células na ordem.

### Google Colab

Caso o notebook seja aberto no **Google Colab**, será necessário fazer o upload manual do arquivo:

```text
Base Varejo.csv
```

quando solicitado na etapa de carregamento do dataset.

---

## 📚 Aprendizados

Este projeto permitiu colocar em prática conceitos fundamentais de análise de dados utilizando Python, principalmente:

- leitura e manipulação de arquivos CSV;
- exploração de DataFrames;
- identificação e tratamento de dados inconsistentes;
- tratamento de valores ausentes;
- remoção de duplicatas;
- conversão de tipos de dados;
- estatística descritiva;
- agrupamento de dados com `groupby()`;
- utilização de `NumPy` em análises;
- criação de visualizações com Matplotlib e Seaborn;
- interpretação de resultados e geração de insights.

---

## 👩‍💻 Autora

**Laís Kugik Varela Alegri**

Projeto desenvolvido para fins acadêmicos durante o curso **Carreira Tech — Trilha Análise de Dados — Manipulação de Dados com Python e SQL — SCTEC**.
