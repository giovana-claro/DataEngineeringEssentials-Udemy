# Getting Started with SQL

**Purpose built databases:** For a given purpose we'll use a specific type of database technology.
  - **RDBMS:** Oracle, Mysql, Postgres, MS SQL Server, Sybase
  - **Data Warehouse:** Databricks, Teradata, GCP BigQuery, AWS Redshift, Azure Synapse
    - MPP Technologies (massively parallel processing)
      - Databases which serva the reports and dashboards for the users within and outside the organization,
it usually contains massive data.
  - **NoSQL:** MongoDB, Cassandra
  - **Search:** Elastic Search, SolR
  - **Graph:** Neo4j

### Data WareHouse

Used to solve different kind of problems. It can be used for tracking the progress of orders, cancelling
order and get refund or buying a product from retail company.

It will answer questions about performance in a period of time to help understanding the progress of the company,
product or department tp get insights.

#### RDBMS vs Data Warehouse or MPP

| RDBMS  | Data Warehouse |
| :-------------: | :-------------: |
| Tables, Columns, Data Types, Rows or Records | Tables, Columns, Data Types, Rows or Records  |
| Online Transactional Processing (OLTP)  | Online Analytical Processing Applications (OLAP) or Decision Support Systems (DSS)  |
| Mobile or Web | Reports or Dashboards |
| SQL | SQL |
