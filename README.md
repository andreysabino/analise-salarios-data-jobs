# Análise de Salários em Data Jobs

## Descrição do Projeto

Este projeto tem como objetivo analisar um conjunto de dados contendo informações sobre salários em diferentes cargos na área de dados. Através da exploração, limpeza e visualização dos dados, buscamos entender as tendências salariais, a distribuição por senioridade, tipo de contrato e localização, entre outros fatores relevantes.

## Fonte de Dados

Os dados utilizados neste projeto foram obtidos do seguinte link:
[https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv](https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv)

## Análise Realizada

As principais etapas da análise incluíram:

1.  **Carregamento e Exploração Inicial:** Carregamento dos dados em um DataFrame pandas e visualização das primeiras linhas, informações gerais e estatísticas descritivas.
2.  **Limpeza e Preparação dos Dados:**
    *   Identificação e tratamento de valores nulos na coluna 'ano'.
    *   Renomeação das colunas para melhor compreensão.
    *   Padronização dos valores em colunas categóricas como 'senioridade', 'contrato', 'remoto' e 'tamanho\_empresa'.
3.  **Visualização de Dados:**
    *   Distribuição da senioridade.
    *   Salário médio por senioridade (barra e boxplot).
    *   Distribuição dos salários anuais (histograma e boxplot).
    *   Proporção dos tipos de trabalho (gráfico de pizza).
    *   Salário médio para Cientistas de Dados por país (gráfico de barras e mapa coroplético).

## Visualizações Chave

*   **Distribuição de Senioridade:** Mostra a contagem de profissionais por nível de senioridade.
*   **Salário Médio por Senioridade:** Compara o salário médio entre os diferentes níveis de senioridade, destacando a diferença salarial entre Junior, Pleno, Senior e Executivo.
*   **Distribuição dos Salários Anuais:** Apresenta a frequência dos salários, mostrando a concentração e a dispersão dos valores.
*   **Proporção dos Tipos de Trabalho:** Exibe a distribuição dos tipos de contrato (Tempo Integral, Contrato, Tempo Parcial, Freelancer) e o regime de trabalho (Presencial, Remoto, Híbrido).
*   **Salário Médio de Cientista de Dados por País:** Visualiza a média salarial para o cargo de Cientista de Dados em diferentes países.

## Contribuições

Contribuições são bem-vindas! Sinta-se a vontade para abrir issues ou pull requests.

