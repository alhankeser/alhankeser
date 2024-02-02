## Analytics / Data Engineer with deep product experience

Current projects: 

### 🚴 ANTREN: personal training analysis dashboard
_airflow_, _python_, _docker_, _google-cloud-run_, _bigquery_, _dbt_, _hex_
|service|role|deployment|description|
|--|--|--|--|
|[app](https://github.com/alhankeser/antren-app)| extract | Dockerized python app running as Google Cloud Run Job | connects to Garmin API to get latest bike rides/runs, converts tcx to tabular parquet|
|[airflow](https://github.com/alhankeser/antren-orchestration)| orchestrate + load | Airflow webserver + scheduler (local) | orchestrates the various steps of data pipeline, including triggering writing to BigQuery using training parquet files in Google Bucket |
|[dbt](https://github.com/alhankeser/antren-dbt)| transform |Dockerized dbt-core running as Google Cloud Run Job, transforming in BigQuery | transforms raw training data in a way that is useful for me!|
|[hex](https://app.hex.tech/9b032bbe-faf6-4719-b6ca-02275f682e4a/app/e100d6f5-7720-4cc1-942c-b3127bb15588/latest)| visualize | Hex.tech | visualizes training progress over time with ability to filter and customize layout|

