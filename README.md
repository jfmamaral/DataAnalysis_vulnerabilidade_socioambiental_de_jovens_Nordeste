# DataAnalysis_vulnerabilidade_socioambiental_de_jovens_Nordeste
Projeto de coleta, limpeza e organização de dados públicos realizado para uma ONG que trabalha com iniciativas de proteção a crianças e adolescentes. 
Foram coletados dados demográficos, econômicos, sociais, de educação, de acesso a infraestrutura urbana e sobre domicílios em áreas de risco para produzir um banco de dados sobre 18 municípios localizados nos estados de Alagoas, Bahia e Salvador.
Os dados tratados subsidiaram a produção de um relatório de vulnerabilidade socioambiental de crianças e adolescentes nos 18 municípios comparados e relatórios aprofundados sobre 3 municípios alagoanos.

O repositório contém o projeto de tratamento dos datasets coletados em bases públicas (alguns previamente organizados no próprio excel) e de construção de gráficos para análise e produção dos relatórios.
O código utilizdo está disponível na íntegra no notebook main.ipynb e também em notebooks separados que se referem a etapas específicas do projeto, permitindo melhor visualização, controle e posterior alteração.

## 0 - main
Notebook que contém todo o código do projeto, organizado em um outline em markup.
## 1 - setup
Requisitos e imports para o tratamento dos datasets.
## 2 - dfs and files organization
Definição de dicionários para o armazenamento de arquivos e versões de dataframes criados durante o processo de tratamento dos dados. Criação de um dicionário índice que contém os dicionários do projeto.
## 3 - IBGE standard notation dicts
Processo de padronização da notação de códigos e nomes dos municípios, UF e regiões aplicado em todos os datasets, para permitir cruzamento de dados.
## 4 - functions
Funções produzidas no projeto com suas documentações.
## 5 - ingestão de dados
Processo de ingestão automatizada de datasets, criação de dataframes e armazenamento de arquivos e dataframes nos dicionários do projeto.
## 6 - tratamento de datasets
Processo de limpeza, tratamento e filtragem dos dados dos dataframes.
## 7 - exportando DFs
Processo de exportação dos DFs tratados e filtrados em formato .xlsx para pastas no disco local.
## graph models
Código modelo para plotagem de tipos de gráficos aplicados aos dados do projeto.
## plotting setup
Imports e configurações padrão de visualização dos gráficos a serem aplicadas em todas as plotagens.
## plots educação
Plotagem dos gráficos referentes ao tema
## plots infaestrutura urbana e aglomerados subnormais
Plotagem dos gráficos referentes ao tema
## plots população
Plotagem dos gráficos referentes ao tema
## plots renda e ocupação
Plotagem dos gráficos referentes ao tema
## plots áreas de risco
Plotagem dos gráficos referentes ao tema
