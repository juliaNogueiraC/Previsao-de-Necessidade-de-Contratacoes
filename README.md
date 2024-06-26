# Projeto de Previsão de Necessidade de Contratações

## Descrição do Projeto

Este projeto visa prever a necessidade de novas contratações em diferentes departamentos de uma empresa, com base em dados históricos de demissões, aposentadorias, desligamentos, novas posições e contratações anteriores. Utilizando técnicas de análise de dados e aprendizado de máquina, buscamos fornecer insights sobre quando e onde a empresa precisará contratar novos funcionários.

## Objetivos

- Analisar dados históricos de rotatividade de funcionários.
- Identificar padrões e tendências nas demissões, aposentadorias e novas contratações.
- Construir e avaliar um modelo preditivo para estimar a necessidade de contratações futuras.
- Visualizar os resultados de forma clara e informativa para ajudar na tomada de decisões estratégicas de RH.

## Estrutura dos Dados

Para este projeto, utilizaremos um dataset fictício chamado `hiring_data_summary.csv` com as seguintes colunas:

- **Year:** Ano da observação.
- **Department:** Departamento da empresa (Sales, Engineering, HR, Finance, Marketing).
- **Retirements:** Número de aposentadorias no ano.
- **Resignations:** Número de demissões voluntárias no ano.
- **Layoffs:** Número de desligamentos no ano.
- **NewPositions:** Número de novas posições criadas no ano.
- **Hires:** Número de contratações realizadas no ano.

## Passos para Execução

1. **Coleta e Carregamento dos Dados:**
   - Gerar um dataset fictício representando as demissões, aposentadorias, desligamentos, novas posições e contratações por departamento e ano.
   - Carregar os dados utilizando a biblioteca Pandas.

2. **Exploração e Limpeza dos Dados:**
   - Verificar a integridade dos dados e tratar valores faltantes ou inconsistentes.
   - Analisar estatísticas descritivas para entender a distribuição dos dados.

3. **Análise Exploratória dos Dados (EDA):**
   - Utilizar visualizações (gráficos de linha, histogramas, heatmaps) para identificar tendências e padrões.
   - Analisar a correlação entre as variáveis para identificar relações importantes.

4. **Engenharia de Características:**
   - Criar novas variáveis que possam melhorar a performance do modelo preditivo.
   - Normalizar ou padronizar os dados, se necessário.

5. **Construção e Avaliação do Modelo Preditivo:**
   - Dividir os dados em conjuntos de treinamento e teste.
   - Construir um modelo de regressão para prever a necessidade de contratações.
   - Avaliar a performance do modelo utilizando métricas como RMSE e R².

6. **Visualização dos Resultados:**
   - Criar gráficos para visualizar a previsão de necessidade de contratações por departamento e ano.
   - Comparar as previsões com os dados reais para verificar a acurácia do modelo.

