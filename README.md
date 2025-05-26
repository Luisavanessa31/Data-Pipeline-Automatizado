# Data-Pipeline-Automatizado
Construção de um pipeline completo de ingestão, processamento e visualização de dados, utilizando Apache Airflow para orquestração, SQL para transformação e Power BI para dashboarding. Inclui integração com AWS S3 para armazenamento e deploy em Docker.

🛠️ Tecnologias

SQL
Power BI
Docker

📂 Estrutura

data-pipeline-airflow/
 ├── dags/
 │   └── data_pipeline.py
 ├── docker-compose.yml
 ├── sql/
 │   └── transformations.sql
 ├── powerbi/
 │   └── dashboard.pbix
 ├── logs/
 └── README.md

🚀 Como executar

docker-compose up

✅ Resultado

Automação de relatórios via Power BI atualizados periodicamente, com orquestração Airflow + SQL.


