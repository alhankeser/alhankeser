## Analytics / Data Engineer

### Actively working on: 
___
#### 🧹 [looker-janitor](https://github.com/alhankeser/looker-janitor): Utility script to keep your Looker project tidy
_looker_, _lookml_, _python_
- When trying to keep large Looker projects organized, Looker Janitor helps keep consistency and order across LookML files.

### Recent: 
___
#### 👓 [looker-label-viewer](https://github.com/alhankeser/looker-label-viewer): VS Code extension to see localized lookml label values
_looker_, _localization_
- When working on big Looker projects with a lot of localization, it's helpful to be able to quickly see the label associated to a dimension or measure.

#### 💰 [borsa](https://github.com/alhankeser/borsa): dbt and DuckDB transformations for day trading bot
_dbt_, _DuckDB_, _python_

- A complete rewrite of my previous bot, created in 2019
- Implementing a new API (switching from TD Ameritrade to TradeStation)
- Exploring using sql (dbt + DuckDB) for transformations instead of purely pandas
- Looking for ways to improve performance/concurrence of backtesting strategy ideas

[Learn more](https://alhan.co/g/trading-bot-dbt-duckdb)

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

