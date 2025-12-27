# Projeto ETL: Análise de Dados RAIS (Região Norte, Brasil)

Este repositório contém os recursos e documentação desenvolvidos para um pipeline **ETL (Extração, Transformação e Carregamento)** aplicado aos dados da **RAIS (Relação Anual de Informações Sociais)** para a Região Norte do Brasil no ano de 2021. Este projeto foi elaborado como parte de um exercício prático para um processo seletivo de Engenharia de Dados.

---

## Estrutura do Diretório

A estrutura do repositório está organizada da seguinte forma:

- **`Consultas/`**: Resultados das consultas SQL realizadas.
- **`CSV/`**: Dados brutos coletados do IBGE em formato CSV.
- **`SQL/`**: Scripts para criação do banco de dados e tabelas.
- **`ProcessoSeletivoDataViva/`**: Notebooks Jupyter documentando o processo iterativo de análise e tratamento de dados.
  - **`PrimeiraTentativa/`** a **`TerceiraTentativa/`**: Tentativas iniciais e análises exploratórias.
  - **`TentativaBemSucedida/`**: O notebook final com a lógica de ETL refinada e bem-sucedida.
- **`Checklist/`**: Documentos de planejamento e listas de verificação utilizadas durante o processo.

---

## Instruções de Uso

Para replicar o processo de ETL e análise de dados, siga os passos abaixo:

1. **Clone o Repositório**
   bash
   git clone https://github.com/dougdotcon/ETL-Processo-Seletivo-DataViva.git
   

2. **Configuração do Banco de Dados**
   - Navegue até a pasta `SQL/` e execute os scripts SQL para criar o banco de dados e suas tabelas.

3. **Importação dos Dados**
   - Importe os arquivos CSV disponíveis na pasta `CSV/` para o banco de dados configurado.

4. **Análise e Tratamento**
   - Utilize o notebook Jupyter disponível em `ProcessoSeletivoDataViva/TentativaBemSucedida/` para realizar a análise e o tratamento dos dados.

5. **Consultas SQL**
   - Consulte os resultados gerados na pasta `Consultas/` ou utilize os scripts para gerar novas análises.

---

## Análises Realizadas

- **Atividades Econômicas:** Identificação das 5 principais atividades econômicas que mais empregam na Região Norte, com base na variável **DIV CNAE 20**.
- **Municípios com Mais Empregos:** Determinação dos 5 municípios que mais empregam na Região Norte do Brasil.

---

## Ferramentas e Tecnologias Utilizadas

- **Python:** Utilizado para o tratamento e análise dos dados (bibliotecas: pandas, numpy).
- **Jupyter Notebooks e Google Colab:** Documentação e execução do processo de análise.
- **SQL/MySQL:** Criação de banco de dados, manipulação e consultas.
- **Fontes de Dados:** RAIS e IBGE.