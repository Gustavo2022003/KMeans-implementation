# Country Clustering Based on Quality of Life

This repository contains a data analysis and machine learning project to cluster countries based on various quality of life indicators. Using clustering techniques like K-Means, we aim to identify patterns and similarities among countries.

## Objective

The goal of this project is to group countries according to their levels of quality of life using a dataset that includes indicators such as infant mortality, life expectancy, GDP per capita, among others. Through these groupings, we can gain insights into which countries have similar living conditions.

## Data Description

The dataset used contains the following columns:

- `country`: Country name
- `child_mort`: Infant mortality (per 1000 births)
- `exports`: Exports (% of GDP)
- `health`: Health spending (% of GDP)
- `imports`: Imports (% of GDP)
- `income`: Income per capita (in USD)
- `inflation`: Annual inflation rate (%)
- `life_expec`: Life expectancy (years)
- `total_fer`: Total fertility rate (children per woman)
- `gdpp`: GDP per capita (in USD)

## Project Steps

1. **Data Loading**: Read the CSV file containing country data.
2. **Data Preprocessing**: Normalize the data to ensure all variables contribute equally to clustering.
3. **Exploratory Analysis**: Visualize data distribution and correlations between variables.
4. **Clustering**: Apply the K-Means algorithm to group countries into clusters.
5. **Cluster Evaluation**: Use metrics like Silhouette Score and Davies-Bouldin Index to assess cluster quality.
6. **Results Visualization**: Scatter plots to visualize the formed clusters.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter-lab

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env-name
   ```

   Activate the virtual environment:

   - On Windows:
     ```bash
     env-name\Scripts\activate
     ```

   - On macOS/Linux:
     ```bash
     source env-name/bin/activate
     ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Lab:
   ```bash
   jupyter lab
   ```

Now you are ready to explore and run the country clustering project based on quality of life indicators.

For further assistance, refer to the documentation or open an issue in the repository.

---

# Português-Brasil

# Clusterização de Países com Base na Qualidade de Vida 

Este repositório contém um projeto de análise de dados e machine learning para agrupar países com base em diversos indicadores de qualidade de vida. Utilizando técnicas de clustering, como o K-Means, buscamos identificar padrões e similaridades entre países.

## Objetivo

O objetivo deste projeto é agrupar países de acordo com seus níveis de qualidade de vida utilizando um conjunto de dados que inclui indicadores como mortalidade infantil, expectativa de vida, PIB per capita, entre outros. Através desses agrupamentos, podemos obter insights sobre quais países possuem condições de vida semelhantes.

## Descrição dos Dados

O conjunto de dados utilizado contém as seguintes colunas:

- `country`: Nome do país
- `child_mort`: Mortalidade infantil (por 1000 nascimentos)
- `exports`: Exportações (% do PIB)
- `health`: Gastos com saúde (% do PIB)
- `imports`: Importações (% do PIB)
- `income`: Renda per capita (em USD)
- `inflation`: Taxa de inflação anual (%)
- `life_expec`: Expectativa de vida (anos)
- `total_fer`: Taxa de fertilidade total (filhos por mulher)
- `gdpp`: PIB per capita (em USD)

## Etapas do Projeto

1. **Carregamento dos Dados**: Leitura do arquivo CSV contendo os dados dos países.
2. **Pré-processamento dos Dados**: Normalização dos dados para garantir que todas as variáveis contribuam igualmente para o clustering.
3. **Análise Exploratória**: Visualização da distribuição dos dados e correlações entre as variáveis.
4. **Clusterização**: Aplicação do algoritmo K-Means para agrupar os países em clusters.
5. **Avaliação dos Clusters**: Utilização de métricas como Silhouette Score e Davies-Bouldin Index para avaliar a qualidade dos clusters.
6. **Visualização dos Resultados**: Gráficos de dispersão para visualizar os clusters formados.

## Requisitos

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter-lab

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv nome-do-ambiente
   ```
   
   Ative o ambiente virtual:

   - No Windows:
     ```bash
     nome-do-ambiente\Scripts\activate
     ```
   
   - No macOS/Linux:
     ```bash
     source nome-do-ambiente/bin/activate
     ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Inicie o Jupyter Lab:
   ```bash
   jupyter lab
   ```

Agora você está pronto para explorar e executar o projeto de clusterização de países com base na qualidade de vida.

Se precisar de ajuda adicional, consulte a documentação ou abra uma issue no repositório.
