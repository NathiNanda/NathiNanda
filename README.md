# Olá, eu sou a Nathiele Fernanda! 👋

Seja bem-vindo ao meu espaço de desenvolvimento e aprofundamento em Engenharia de Dados! 

Sou uma profissional com sólida trajetória na área de Dados (tendo atuado desde a base técnica até a Coordenação de equipes), atualmente focada 100% em especialização técnica e amadurecimento de habilidades em **Engenharia de Dados**.

Minha bagagem prática inclui a implantação e modernização de infraestruturas de dados em diferentes cenários corporativos. Desde ETL, Modelagem de Dados à implantação de Banco de dados local e em Nuvem, bem como criação e otimização de Dashboards em Power BI.

Atuação no projeto de Implantação do Databricks (rodando sobre a infraestrutura Microsoft Azure) para migração de todo o processo de ETL e dos dados do sistema legado Microsoft Access para o Lakehouse. Adaptação de códigos SQL, reorganização, tratativa de erros e otimização de etapas de transformação de dados eliminando redundâncias e aplicando modularização para geração de relatórios eficientes.

---

## 🛠️ Habilidades Técnicas & Fundamentos

### 📈 Engenharia, Processamento & Transformação
*   **Linguagens:** Python, SQL, PySpark
*   **Big Data & Cloud Platforms:** Databricks, Apache Spark
*   **Modern Data Stack (MDS):** dbt Core (Modelagem, testes de qualidade e documentação), DuckDB
*   **Arquitetura:** Data Lakes, Data Warehouses, Arquitetura Medalhão.

### ☁️ Infraestrutura, Orquestração & Bancos de Dados
*   **Orquestração de Pipelines:** Apache Airflow (Criação de DAGs e automação de fluxos)
*   **Nuvem & Data Warehouses:** Snowflake, AWS | Estudos em Azure
*   **Bancos de Dados:** SQL Server, MySQL, SQLite
*   **Ferramentas & DevOps:** Git & GitHub, Docker (Conteinerização de ambientes)

### 📚 Fundamentos
Aplico em meus projetos os conceitos de engenharia e arquitetura consolidados através de leituras técnicas essenciais:
*   *"Fundamentos da Engenharia de Dados"* (Joe Reis & Matt Housley).
*   *"Data Pipelines Pocket Reference"* (James Densmore).
---

## 🚀 Projetos em Destaque

### 🌌 [Modern Data Stack: Snowflake, Airflow, dbt, S3 & Docker](https://github.com/NathiNanda/dbt_snowflake_airflow_docker.git)
Pipeline de dados moderno para ingestão, armazenamento e transformação de taxas de câmbio.
*   **Como funciona:** Coleta dados via Python, armazena os dados brutos no **AWS S3** (Data Lake), carrega no **Snowflake** (Data Warehouse), realiza a modelagem e testes de qualidade de dados com **dbt Core**, tudo orquestrado pelo **Apache Airflow** rodando em **Docker**.
*   **Tecnologias:** Python, AWS S3, Snowflake, dbt, Apache Airflow, Docker.

### 🦆 [Pipeline Local: Python, DuckDB & dbt](https://github.com/NathiNanda/elt-python-duckdb-dbt.git)
Pipeline ELT local focado em performance e qualidade de dados de cotações de moedas da AwesomeAPI.
*   **Como funciona:** Consome a API em Python, salva o payload bruto em arquivos JSON e utiliza o **DuckDB** como motor analítico de alta performance. O **dbt-core** realiza as transformações e aplica os testes de qualidade nas tabelas.
*   **Tecnologias:** Python, DuckDB, dbt Core, JSON.

### 📊 [ETL Automatizado: Python, SQLite & Streamlit](https://github.com/NathiNanda/etl-participants-pix.git)
Pipeline ponta a ponta focado em consumo de APIs públicas e entrega de valor para o negócio.
*   **Como funciona:** Consome dados da API de participantes do PIX (BrasilAPI), realiza a limpeza e transformação com **Python/Pandas**, armazena em um banco relacional **SQLite** e disponibiliza um dashboard analítico interativo via **Streamlit e Altair**.
*   **Tecnologias:** Python, Pandas, SQLite, Streamlit, Altair.
