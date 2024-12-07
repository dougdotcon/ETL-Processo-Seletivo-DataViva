# Análise de Dados RAIS - Região Norte (2021)

Este repositório contém os recursos e documentação desenvolvidos durante um exercício de ETL (Extração, Transformação e Carregamento) aplicado aos dados da **RAIS (Relação Anual de Informações Sociais)** para a Região Norte do Brasil no ano de 2021. Este projeto foi elaborado como parte de um processo seletivo para uma vaga de estágio em Engenharia de Dados.

---

## Estrutura do Diretório

A estrutura do repositório está organizada da seguinte forma:

- **`Consultas/`**
  - Resultados das consultas SQL realizadas.

- **`CSV/`**
  - Dados brutos coletados do IBGE em formato CSV.

- **`SQL/`**
  - Scripts para criação do banco de dados e tabelas.

- **`ProcessoSeletivoDataViva/`**
  - **`PrimeiraTentativa/`**
    - Notebooks Jupyter da primeira tentativa de análise e tratamento de dados.
  - **`SegundaTentativa/`**
    - Notebooks Jupyter da segunda tentativa de análise e tratamento de dados.
  - **`TerceiraTentativa/`**
    - Notebooks Jupyter da terceira tentativa de análise e tratamento de dados.
  - **`TentativaBemSucedida/`**
    - Notebook Jupyter com o processo final de análise e tratamento bem-sucedido.

- **`Checklist/`**
  - Documentos de planejamento e verificação utilizados no processo.

---

## Instruções de Uso

Para replicar o processo de ETL e análise de dados, siga os passos abaixo:

1. **Clone o Repositório**
   ```bash
   git clone https://github.com/dougdotcon/ETL-Processo-Seletivo-DataViva.git
   ```

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
- **RAIS e IBGE:** Fontes dos dados utilizados.

---

## Contribuições

Contribuições são bem-vindas para melhorar este projeto. Para colaborar:

1. Faça um **fork** deste repositório.
2. Crie uma **branch** para suas alterações:
   ```bash
   git checkout -b feature/sua-feature
   ```
3. Faça o **commit** das alterações:
   ```bash
   git commit -m "Adiciona nova análise"
   ```
4. Envie suas alterações:
   ```bash
   git push origin feature/sua-feature
   ```
5. Abra um **Pull Request** para revisão.

---

## Contato

- **Autor:** Douglas H. Machado
- **Email:** [dougdotcon@gmail.om](mailto:dougdotcon@gmail.om)
- **LinkedIn:** [dougdoton](https://www.linkedin.com/in/dougdoton/)
- **GitHub:** [dougdotcon](https://github.com/dougdotcon)

---

*Este projeto busca promover uma análise eficiente e clara dos dados da RAIS para apoiar decisões baseadas em informações regionais da Região Norte do Brasil.*
