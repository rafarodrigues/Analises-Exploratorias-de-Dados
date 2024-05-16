
# 📈 AED - Abstenções Eleições 2022 - 1º Turno

> Este repositório contém a análise exploratória dos dados de abstenções das eleições brasileiras de 2022. Utilizando diversas bibliotecas de Python e dados geoespaciais, exploramos e visualizamos o comportamento das abstenções ao longo dos anos e entre diferentes estados.

<div align="center"> <img src="https://github.com/rafarodrigues/Analises-Exploratorias-de-Dados/blob/main/01.%20Absten%C3%A7%C3%B5es%20-%201%C2%BA%20Turno%20Elei%C3%A7%C3%B5es/img/abstencoes.jpg?raw=true" width="800"> </div>

## Introdução

A abstenção eleitoral é um fenômeno que pode indicar diversos fatores socioeconômicos e políticos. Este projeto visa analisar os dados de abstenções das eleições de 2022 no Brasil, utilizando técnicas de visualização de dados e geoprocessamento para identificar padrões e insights.

## Sobre os Dados

Os dados utilizados foram extraídos de fontes oficiais, garantindo a confiabilidade e precisão das informações. Foram utilizados três principais datasets:

- **Perfil de Comparecimento e Abstenção 2022**: Contém informações detalhadas sobre a abstenção por município.
    - [Link para o dataset](https://dadosabertos.tse.jus.br/dataset/comparecimento-e-abstencao-2022.csv)
- **Evolução dos Faltosos nos Últimos Pleitos**: Histórico de abstenções desde 2005.
    - [Link para o dataset](https://www.tse.jus.br/eleitor/estatisticas-de-eleitorado/faltosos.csv)
- **Base Cartográfica Contínua do IBGE**: Dados geoespaciais dos municípios brasileiros.
    - [Link para o dataset](https://www.ibge.gov.br/geociencias/cartas-e-mapas/bases-cartograficas-continuas/15759-brasil.html?=&t=acesso-ao-produto)
    
## Objetivos e Metodologia

### Objetivos

- **Analisar o perfil das abstenções**: Entender a distribuição das abstenções por faixa etária, gênero, e escolaridade.
- **Visualizar os dados geograficamente**: Utilizar mapas para identificar regiões com maior taxa de abstenção.
- **Identificar tendências históricas**: Analisar o comportamento das abstenções ao longo dos anos.

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

## Link para o projeto

<a href="https://github.com/rafarodrigues/Analises-Exploratorias-de-Dados/blob/main/01.%20Absten%C3%A7%C3%B5es%20-%201%C2%BA%20Turno%20Elei%C3%A7%C3%B5es/An%C3%A1lise%20de%20absten%C3%A7%C3%B5es.ipynb" target="_blank">Analises-Exploratorias-de-Dados/01. Abstenções - 1º Turno Eleições
/Análise de abstenções.ipynb</a>

## Licença

Distribuído sob a licença MIT