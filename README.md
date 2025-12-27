# ETL Project: RAIS Data Analysis (North Region, Brazil)

This repository contains the resources and documentation developed for an **ETL (Extract, Transform, Load)** pipeline applied to **RAIS (Relação Anual de Informações Sociais)** data for the North Region of Brazil for the year 2021. This project was designed as part of a practical assessment for a Data Engineering internship position.

---

## Project Structure

The repository is organized as follows:

- **`Consultas/`**: Results of the SQL queries performed.
- **`CSV/`**: Raw data collected from the IBGE (Brazilian Institute of Geography and Statistics) in CSV format.
- **`SQL/`**: Scripts for database and table creation.
- **`ProcessoSeletivoDataViva/`**: Jupyter Notebooks documenting the iterative data analysis and treatment process.
  - **`PrimeiraTentativa/`** to **`TerceiraTentativa/`**: Initial attempts and exploratory data analysis.
  - **`TentativaBemSucedida/`**: The final, successful notebook containing the refined ETL logic.
- **`Checklist/`**: Planning documents and verification checklists used during the process.

---

## Getting Started

To replicate the ETL process and data analysis, follow these steps:

1. **Clone the Repository**
   bash
   git clone https://github.com/dougdotcon/ETL-Processo-Seletivo-DataViva.git
   

2. **Database Setup**
   - Navigate to the `SQL/` folder and execute the SQL scripts to create the database schema and tables.

3. **Data Import**
   - Import the CSV files located in the `CSV/` folder into your configured database.

4. **Analysis and Processing**
   - Use the Jupyter notebook located in `ProcessoSeletivoDataViva/TentativaBemSucedida/` to perform the data analysis and transformations.

5. **SQL Queries**
   - Review the results generated in the `Consultas/` folder or run the scripts to generate new analyses.

---

## Analysis Performed

*   **Economic Activities:** Identification of the top 5 economic activities providing the most employment in the North Region, based on the **DIV CNAE 20** variable.
*   **Municipalities:** Determination of the 5 municipalities with the highest employment rates in the North Region.

---

## Technologies Used

*   **Python:** Used for data manipulation and analysis (libraries: pandas, numpy).
*   **Jupyter Notebooks / Google Colab:** Used for documenting and executing the analysis process.
*   **SQL/MySQL:** Used for database creation, manipulation, and querying.
*   **Data Sources:** RAIS and IBGE.