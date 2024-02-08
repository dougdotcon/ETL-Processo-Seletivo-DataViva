# Análise de Dados RAIS Região Norte

Este repositório contém todos os recursos e documentações utilizados no processo seletivo para uma vaga de estágio em Engenharia de Dados. O projeto consiste em um exercício de ETL (Extração, Tratamento e Carregamento) de dados da RAIS (Relação Anual de Informações Sociais) para a Região Norte do Brasil para o ano de 2021.

## Estrutura do Diretório

- **Consultas/**
  - *Arquivos com resultados das consultas SQL*
  
- **CSV/**
  - *Dados coletados do IBGE Cidades em formato CSV*
  
- **SQL/**
  - *Scripts SQL para criação do banco e tabelas*
  
- **ProcessoSeletivoDataViva/**
  - **PrimeiraTentativa/**
    - *Notebooks Jupyter com a primeira tentativa de análise e tratamento*
  - **SegundaTentativa/**
    - *Notebooks Jupyter com a segunda tentativa de análise e tratamento*
  - **TerceiraTentativa/**
    - *Notebooks Jupyter com a terceira tentativa de análise e tratamento*
  - **TentativaBemSucedida/**
    - *Notebook Jupyter com a tentativa bem-sucedida de análise e tratamento*
    
- **Checklist/**
  - *Documentos de planejamento e verificação*

## Instruções de Uso

Para replicar o processo de ETL realizado neste projeto, siga os passos abaixo:

1. Clone o repositório para a sua máquina local utilizando o comando `git clone [[URL do repositório](https://github.com/dougdotcon/ETL-Processo-Seletivo-DataViva)]`.
2. Navegue até a pasta SQL/ e execute os scripts SQL para criar o banco de dados e as tabelas necessárias.
3. Importe os dados CSV localizados na pasta CSV/ para o banco de dados criado.
4. Utilize os notebooks Jupyter na pasta ProcessoSeletivoDataViva/TentativaBemSucedida/ para realizar a análise e tratamento dos dados.
5. Consulte os resultados obtidos nas consultas SQL dentro da pasta Consultas/.

## Análises Realizadas

- Identificação das 5 principais atividades econômicas que mais empregam na Região Norte, com base na variável DIV CNAE 20.
- Identificação dos 5 municípios que mais empregam pessoas na Região Norte do Brasil.

## Ferramentas e Tecnologias Utilizadas

- Python para análise e tratamento de dados, pandas, numpy
- Jupyter Notebooks e Google Colab para documentação e compartilhamento do processo de análise.
-  SQL, MySQL
