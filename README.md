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
2. Instale as dependências:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter-lab
   ```
3. Inicie o Jupyter lab
   ```bash
   jupyter lab
   ```
