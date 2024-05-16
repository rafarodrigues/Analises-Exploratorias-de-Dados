# 📈 Análise Exploratória dos Dados - Perfil do Eleitorado Brasileiro 2022

> Este repositório contém a análise exploratória dos dados do perfil do eleitorado brasileiro nas eleições de 2022. Utilizando diversas bibliotecas de Python e dados geoespaciais, exploramos e visualizamos o comportamento do eleitorado brasileiro.

<div align="center"> <img src="https://github.com/rafarodrigues/Analises-Exploratorias-de-Dados/blob/main/02.%20Perfil%20do%20Eleitorado%20Brasileiro/img/image.jpg?raw=true" width="900"> </div>


## Introdução

O perfil do eleitorado é uma variável fundamental para entender o comportamento eleitoral e suas tendências. Este projeto visa analisar os dados do eleitorado brasileiro nas eleições de 2022, utilizando técnicas de visualização de dados e geoprocessamento para identificar padrões e insights.

## Sobre os Dados

Os dados utilizados foram extraídos de fontes oficiais, garantindo a confiabilidade e precisão das informações. Foram utilizados dois principais datasets:

- **Perfil do Eleitorado 2022**: Contém informações detalhadas sobre o eleitorado por município.
    - [Link para o dataset](https://dadosabertos.tse.jus.br/dataset/eleitorado-2022/resource/8a6ff7bd-5a22-4d1a-9353-cce06f9f5e35)
- **Base Cartográfica Contínua do IBGE**: Dados geoespaciais dos municípios brasileiros.
    - [Link para o dataset](https://www.ibge.gov.br/geociencias/cartas-e-mapas/bases-cartograficas-continuas/)

## Objetivos e Metodologia

### Objetivos

- **Analisar o perfil do eleitorado**: Entender a distribuição do eleitorado por faixa etária, gênero, escolaridade, e outros fatores.
- **Visualizar os dados geograficamente**: Utilizar mapas para identificar regiões com maior concentração de eleitores.
- **Identificar tendências e padrões**: Analisar o comportamento do eleitorado ao longo dos anos e entre diferentes regiões.

### Metodologia

1. **Importação e Limpeza de Dados**: Carregamento dos datasets e preparação dos dados para análise.
2. **Análise Exploratória de Dados (AED)**: Estatísticas descritivas e visualizações iniciais.
3. **Geoprocessamento**: Utilização de dados geoespaciais para visualização em mapas.
4. **Visualização e Interpretação**: Criação de gráficos e mapas para melhor interpretação dos dados.

## Dependências

- Python 3.8+
- Pandas
- Seaborn
- Matplotlib
- Geopandas
- NumPy
- Shapely