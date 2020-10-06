# nosql-apache-cassandra
Data modeling in Apache Cassandra

## Files

- images
- etl.ipnyb: Contains all elt code
- event_data/: contains csv files that will be used to populate our database

## Databa Schema

![DatabaseSchema](images/Schema.png)

## Usage
Setting cassandra instance with docker:

```
docker run --name cassandra-db -p 9042:9042 -d cassandra:latest;
```

Run the script `elt.ipynb` in order to populate the database.
