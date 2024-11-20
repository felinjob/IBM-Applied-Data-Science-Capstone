# Análise de Dados da SpaceX: Insights sobre o Pouso do Falcon 9

## Introdução

A SpaceX revolucionou a indústria espacial com seus foguetes Falcon 9, oferecendo lançamentos a preços muito competitivos (62 milhões de dólares), enquanto outras empresas cobram mais de 165 milhões de dólares. Essa diferença se deve à capacidade da SpaceX de reutilizar o primeiro estágio do foguete. 

Neste projeto, vamos construir um modelo de Machine Learning para prever o sucesso do pouso do primeiro estágio do Falcon 9. Essa previsão é crucial para empresas que competem com a SpaceX, permitindo que elas estimem os custos de lançamento e façam ofertas mais competitivas.

## Contexto do Projeto

Este projeto final faz parte da especialização IBM Data Science Professional Certificate e aplica os conhecimentos adquiridos ao longo do curso. O objetivo é responder às seguintes perguntas:

* Como variáveis como massa da carga útil, local de lançamento, número de voos e órbitas afetam o sucesso do pouso do primeiro estágio?
* A taxa de pousos bem-sucedidos aumenta ao longo dos anos?
* Qual o melhor algoritmo para classificação binária neste caso?

## Metodologia

1. **Coleta de Dados:**
    * API da SpaceX
    * Web Scraping da Wikipedia

2. **Preparação dos Dados:**
    * Filtragem 
    * Tratamento de valores ausentes
    * Codificação One-Hot para classificação binária

3. **Análise Exploratória de Dados (EDA):**
    * Visualização
    * SQL

4. **Visualização Analítica Interativa:**
    * Folium
    * Plotly Dash

5. **Análise Preditiva:**
    * Construção, ajuste e avaliação de modelos de classificação

## Estrutura do Repositório

* **data/:** Dados e scripts relacionados.
* **notebooks/:** Jupyter notebooks com a documentação do projeto.
* **scripts/:** Scripts em Python para processamento, visualização e modelagem.
* **dash_app/:** Código do aplicativo interativo Plotly Dash.

## Resultados

O projeto construiu um modelo de Machine Learning capaz de prever o sucesso do pouso do primeiro estágio do Falcon 9 com alta precisão. O modelo de Árvore de Decisão obteve o melhor desempenho, com uma acurácia de 94,44%.

## Conclusão

Este projeto demonstra como a Ciência de Dados pode ser aplicada para gerar insights valiosos no setor espacial. As previsões geradas pelo modelo podem auxiliar empresas a tomar decisões estratégicas em relação aos custos de lançamento e à competitividade no mercado.
