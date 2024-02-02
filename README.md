## Analytics / Data Engineer with deep product experience

Current projects: 

### 🚴 ANTREN: personal training analysis dashboard
_airflow_, _python_, _docker_, _google-cloud-run_, _bigquery_, _dbt_, _hex_
|service|deployment|description|
|--|--|--|
|[orchestration](https://github.com/alhankeser/antren-orchestration)| Airflow webserver + scheduler (local) | orchestrates the various steps of data pipeline |
|[app](https://github.com/alhankeser/antren-app)| Dockerized python app running as Google Cloud Run Job, storing in Google Bucket and writing to BigQuery | connects to Garmin API to get latest bike rides/runs, converts tcx to tabular parquet|
|[dbt](https://github.com/alhankeser/antren-dbt)| Dockerized dbt-core running as Google Cloud Run Job, transforming in BigQuery | transforms raw training data in a way that is useful for me!|
|[visualization](https://app.hex.tech/9b032bbe-faf6-4719-b6ca-02275f682e4a/app/e100d6f5-7720-4cc1-942c-b3127bb15588/latest)| Hex for visualization | visualizes training progress over time with ability to filter and customize layout|

