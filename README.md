# Cléber Casagrande

Profissional de tecnologia com foco em Dados, construindo soluções de ponta a ponta para coleta, transformação e disponibilização de informações com qualidade.

Atuo na construção de pipelines (ETL/ELT), modelagem de dados, padronização e integração, com preocupação em confiabilidade, reprodutibilidade e observabilidade do fluxo. Interesse forte em Analytics e em habilitar Data Science com dados bem estruturados e consistentes.

**LinkedIn:** https://www.linkedin.com/in/cleber-vicenzo-b11204253/

## Stack (foco atual)
- Python, Pandas
- SQL (PostgreSQL, MySQL)
- SQLite
- Docker, Docker Compose
- Git, GitHub Actions
- AWS (S3, Athena)
- dbt
- Spark (PySpark)
- FastAPI
- Linux
- Data Modeling (Star Schema, Medallion)
- Data Quality (Great Expectations)
- Observability/Monitoring (logs, métricas)
- Formatos: CSV, JSON, Parquet

  ## O que eu faço bem
- Construção de pipelines locais e containerizados (**Python + Pandas + Docker**)
- Extração de dados via **web scraping** e **APIs**, com paginação e persistência
- Transformações e padronizações para dados mais confiáveis (tipos, nulos, chaves, deduplicação)
- Modelagem e consultas em **SQL (PostgreSQL)** com foco analítico

## Projetos em destaque
- **Web Scraper — Resident Evil Database (Personagens)**  
  Coleta links de personagens, extrai informações básicas e aparições e exporta em **CSV** e **Parquet**.  
  Repo: https://github.com/cleber2010/data-collect

- **TabNews API Collector (Contents)**  
  Coletor de dados via API pública do TabNews (`/api/v1/contents`) com paginação. Salva os resultados em **JSON** (e opcionalmente **Parquet**) com timestamp.  
  Repo: https://github.com/cleber2010/TabNews

- **Medallion Architecture (Bronze → Silver → Gold)**  
  Pipeline com ingestão, normalização em Parquet e carga/consulta em PostgreSQL.  
  Repo: https://github.com/cleber2010/MEDALLION_ARCHITECTURE

- **ETL & Feature Store — Loyalty System (SQLite + SQL)**  
  Pipeline analítico em **SQLite** para construção de uma **feature store por cliente**, incluindo janelas temporais, comportamento transacional, produto mais recorrente e padrões de uso. Orquestrado em **Python (Pandas + SQLAlchemy)**.  
  Repo: https://github.com/cleber2010/curso-sql
