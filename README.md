#  Análise de Salários em Data Jobs

##  Acesso à Aplicação
A aplicação interativa desenvolvida com **Streamlit** pode ser acessada através do link:  
🔗 [jobsdata.streamlit.app](https://jobsdata.streamlit.app/)

---

##  Descrição do Projeto
Este projeto tem como objetivo **analisar um conjunto de dados sobre salários** em diferentes cargos na área de dados.  
Através da **exploração, limpeza e visualização dos dados**, buscamos identificar tendências salariais, distribuição por **senioridade**, **tipo de contrato**, **localização**, entre outros fatores relevantes.

---

##  Fonte de Dados
Os dados utilizados neste projeto foram obtidos em:  
🔗 [salaries.csv](https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv)

---

##  Análise Realizada

###  Carregamento e Exploração Inicial
- Leitura dos dados em um **DataFrame Pandas**.
- Visualização das **primeiras linhas**, informações gerais e estatísticas descritivas.

###  Limpeza e Preparação dos Dados
- Tratamento de valores nulos na coluna `ano`.
- Renomeação das colunas para facilitar a compreensão.
- Padronização de valores em colunas categóricas:
  - `senioridade`
  - `contrato`
  - `remoto`
  - `tamanho_empresa`

###  Visualização dos Dados
- **Distribuição da senioridade**.
- **Salário médio por senioridade** (gráficos de barra e boxplot).
- **Distribuição dos salários anuais** (histograma e boxplot).
- **Proporção dos tipos de trabalho** (gráfico de pizza).
- **Salário médio de Cientistas de Dados por país** (gráfico de barras e mapa coroplético).

---

##  Visualizações Chave

- **Distribuição de Senioridade**  
  Mostra a quantidade de profissionais por nível (Junior, Pleno, Senior, Executivo).

- **Salário Médio por Senioridade**  
  Compara o salário médio entre níveis, evidenciando diferenças salariais.

- **Distribuição dos Salários Anuais**  
  Apresenta a frequência e dispersão dos valores.

- **Proporção dos Tipos de Trabalho**  
  Mostra a divisão entre contrato integral, contrato temporário, parcial e freelancer, além de regimes presencial, remoto e híbrido.

- **Salário Médio por País (Cientistas de Dados)**  
  Visualiza a média salarial por país em gráficos e mapas.

---

##  Contribuições
Contribuições são bem-vindas!  
Sinta-se a vontade para **abrir issues** ou **enviar pull requests** para melhorias no projeto.
