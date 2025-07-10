# Data Load Tool (dlt)

### 1. What is dlt: 

**Main Idea:** We take the data and move it somewhere else. 

Every data job is a data engineering job when you go through the ETL/ELT process. 

1. **dlt (data load tool):** is an open-source Python Library that lets you build modern ELT pipelines using just Python code. 

2. It helps you: 
        a. **Extract** data from APIs, databases, files, or custom sources.
        b. **Transform** and normalize data.
        c. **Load** data into destinations like BigQuery, DuckDB, RedShift, etc. 
        d. **Manage** schemas, state, and incremental loading automatically. 


### How we'll be using dlt: 

1. Taxi dataset: 
    a. Ingesting a dataset into a local DuckDB destination. 
    b. Access local data as a Dataframe. 

2. REST API source dataset: 
    a. Ingesting data to a local filesystem.


# Cognee

1. Cognee turns your data into a queryable `memory` and `knowledge graph`.

2. It lets you:     

    a. Add structured or unstructured data (DataFrames, documents, tables). 
    b. Automatically build a knowledge graph from it. 
    c. Ask natural language questions and get grounded, context-rich answers. 