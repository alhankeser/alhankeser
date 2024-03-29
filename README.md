## Analytics / Data Engineer

### Actively working on: 
___
#### 💰 [borsa](https://github.com/alhankeser/borsa): dbt and DuckDB transformations for day trading bot
_dbt_, _DuckDB_, python

- A complete rewrite of my previous bot, created in 2019
- Implementing a new API (switching from TD Ameritrade to TradeStation)
- Exploring using sql (dbt + DuckDB) for transformations instead of purely pandas
- Looking for ways to improve performance/concurrence of backtesting strategy ideas

### Recent: 
___
#### 🦎 [tcx-extract](https://github.com/alhankeser/tcx-extract): fast, simple data extraction
_zig_, _python_

- A speed-optimized extractor for .tcx (XML) files from Garmin.
- Example implementation [here](https://alhan.co/g/faster-python-tcx-xml-extraction-zig).

#### 🚴 [antren](https://alhan.co/g/cycling-training-data-pipeline): personal training analysis dashboard
_airflow_, _python_, _docker_, _google-cloud-run_, _bigquery_, _dbt_, _hex_
|repo|role|deployment|description|
|--|--|--|--|
|[antren-app](https://github.com/alhankeser/antren-app)| extract | Dockerized python app running as Google Cloud Run Job | connects to Garmin API to get latest bike rides/runs, converts tcx to tabular parquet [learn more](https://alhan.co/g/extract-workouts-from-garmin)|
|[antren-orchestration](https://github.com/alhankeser/antren-orchestration)| orchestrate + load | Airflow webserver + scheduler (local) | orchestrates the various steps of data pipeline, including triggering writing to BigQuery using training parquet files in Google Bucket [learn more](https://alhan.co/g/load-parquet-bigquery)|
|[antren-dbt](https://github.com/alhankeser/antren-dbt)| transform |Dockerized dbt-core running as Google Cloud Run Job | transforms raw training data in BigQuery to make it useful for me! [learn more](https://alhan.co/g/transform-activity-data)|
|[hex app](https://app.hex.tech/9b032bbe-faf6-4719-b6ca-02275f682e4a/app/e100d6f5-7720-4cc1-942c-b3127bb15588/latest)| visualize | Hex app (aka a dashboard) | visualizes training progress over time with ability to filter and customize layout|

