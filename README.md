# CloudArchitecture_TTI
High scalable and available infrastructure from AWS

## Planning

### Requirements
* "El mundo de las letras" online bookstore has become the latinamerican book provider of preference. The company constantly participate on book fairs and as part of marketing strategy they offer online discounts, so it needs a high scalable and available architecture for those periods of time with high demand. 
* The webpage shows the books available from a database that is updated backend. The architecture must deploy the relational database 
* The database MUST NOT be public, it cannot be directly accesible from web.

### Architecture
The following image shows the proposed architecture given the previous requirements
![Proposed architecture](img/Infraestructura.png)

## Budget
Selected instance database db.t2.2xlarge, T2 instances are a good choice for a variety of database workloads, such as microservices and staging databases. US0


## Deployment
