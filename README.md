# Modulo 38 - Credit Score

## Resumo

### O projeto tem como objetivo criar um modelo de machine learning para o score de crédito, abrangendo todo o pipeline de processamento dos dados. O processo envolve as seguintes etapas:
  1- Dados do projeto: Trata-se de um problema de credit scoring para cartão de crédito, utilizando uma amostra de 15 safras coletadas entre janeiro de 2015 e março de 2016. O objetivo é 
    prever se um cliente entrará em inadimplência ou não pagará suas dívidas. Os clientes inadimplentes são marcados como "maus" no conjunto de dados.

  2 - Exploração de dados: Os dados coletados são explorados para entender sua estrutura, distribuição, correlações e possíveis padrões. Isso envolve a análise estatística dos dados, a visualização de gráficos e a identificação de insights relevantes.

  3- Limpeza e pré-processamento dos dados: Nesta fase, os dados são submetidos a um processo de tratamento que envolve lidar com valores faltantes, codificar variáveis categóricas, normalizar ou padronizar variáveis numéricas, identificar e tratar outliers, e outras transformações necessárias.

  4 - O modelo: Após o tratamento adequado dos dados, utilizou-se a ferramenta pycaret para o treinamento do modelo e ajuste de hiperparâmetros. O algoritmo de machine learning escolhido foi o Light Gradient Boosting Machine devido ao seu bom desempenho e baixo custo computacional.

  5 - Deploy do modelo: Após o treinamento, ajuste e validação do modelo, procedeu-se à implementação no Streamlit. Foi desenvolvida uma aplicação que recebe novos dados e realiza as previsões do modelo, retornando ao usuário um arquivo Excel

  6 - Ao longo de todo o processo, é crucial monitorar as métricas de desempenho do modelo. O objetivo final é desenvolver um modelo de score de crédito confiável e preciso, capaz de tomar decisões embasadas nos dados disponíveis.
