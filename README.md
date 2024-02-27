# Data Modeling with Apache Cassandra

### Project Summary
Ingesting and analysing the songs and user activity on a music streaming app.
Main goal is to understand what songs users are listening to. Theere is no easy way to query
the collected data since the data reside in a directory of CSV files.

As a Data Engineer, our responsibility on this project to create an Apache Cassandra database
which can create song play data on answer the analysis team's questions.

### Project TODOs
- Modeling Data for `Apache Cassandra`
- Built ETL Pipeline using `Python`

### Project Details

#### Datasets

For simplicity of the project, we will be working with one dataset: `event_data`. The file format is `CSV`. The director of the files partitioned by date. Here are examples of file paths in the dataset:
```cmd
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```