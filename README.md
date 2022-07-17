## NEO4J DataModel implementation

This repository contains implementation of a data model for 
* [Banking - Customer & Transaction Data](https://gist.github.com/maruthiprithivi/f11bf40b558879aca0c30ce76e7dec98)

## Data Model development
I used [arrows.app](http://arrows.app/) to develop a visual data model for the dataset. It was very intuitive to develop & easy to explain to someone not familiar with the details of the dataset

## Data Ingestion
I used Cypher to ingest data into neo4J. Ingestion script can be viewed at [ingest_script](ingest_script.txt)

## Sample queries
Used Cypher to get some quick insights into the dataset. Sample queries can be seen at [query_script](query_script.txt)

Following insights were taken from the dataset
* Top 10 merchants by number of payments received
* Top 10 customer pairs by number of payments(directional)
* Top 10 customer pairs by amount of transaction(non-directional)
* Top 10 countries in the dataset
* Top 10 countries merchants get paid from
* Top 10 customers being transferred amounts from other customers by count of transactions
* Top 10 countries by average amount of transactions
