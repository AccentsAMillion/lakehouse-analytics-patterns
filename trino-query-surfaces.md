# Trino Query Surfaces in Distributed Analytics Environments

## Purpose

This document explains how query engines act as access layers between analytics users and distributed datasets.

Trino enables flexible querying across heterogeneous storage backends.

---

## Query Engine as Access Layer

Modern analytics environments separate:

storage layer  
metadata layer  
query engine  

Trino operates as the interface between structured datasets and analysts.

---

## Benefits of Query Abstraction

Query engines provide:

schema discovery  
federated querying  
multi-source joins  
interactive analytics  

This allows datasets to remain storage-independent.

---

## Example Query Flow

user query  
→ query planner  
→ metadata lookup  
→ storage scan  
→ result aggregation  

The engine orchestrates access without altering storage structure.

---

## Federated Access

Trino supports querying across:

lakehouse tables  
relational databases  
object storage datasets  
streaming sources  

Federation improves analytics flexibility.

---

## Outcome

Query surfaces enable:

cross-platform dataset access  
interactive analytics workflows  
decoupled compute architectures  
storage-independent querying
