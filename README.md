# dbt Knowledge Graph

A proof of concept exploring how metadata from dbt projects can be represented as knowledge graphs to support data lineage, impact analysis, and metadata discovery.

## Project Objectives

- Extract model, source, test, and dependency metadata from dbt artifacts.
- Explore model-level and column-level data lineage.
- Identify downstream dependencies for impact analysis.
- Compare property graph and RDF approaches to representing data metadata.

## Proofs of Concept

### POC 1: dbt to Neo4j Property Graph 

Explore representing dbt models, columns, tests, and lineage as nodes and relationships in Neo4j, queried using Cypher.

### POC 2: dbt to RDF Knowledge Graph 

Explore representing dbt metadata as RDF triples, with semantic relationships and queries using SPARQL.

## Technology Stack

- Python
- dbt Core
- PostgreSQL
- Neo4j and Cypher
- RDF and SPARQL

## Project Status

This project is under development. Features and implementation details will be updated as the proofs of concept progress.

## Getting Started

Setup instructions will be added as the implementation and dependency versions are verified.

## License

See the LICENSE file.
