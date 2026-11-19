# NoSQL Database using MongoDB — Practical 01 to 18

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

Each practical has its own folder with a Markdown report, the course activity scripts and a guide. The reports contain the aim, procedure, expected result and fields for recording the results of your own run.

[Download all 18 practicals as a ZIP](NoSQL-MongoDB-Practicals.zip)

## Experiment index

| Practical | Topic |
| --- | --- |
| [01](experiments/Chapter_01/README.md) | NoSQL Database Models and Application Mapping |
| [02](experiments/Chapter_02/README.md) | Environment Setup and Bookstore CRUD |
| [03](experiments/Chapter_03/README.md) | Document Modelling and Schema Validation |
| [04](experiments/Chapter_04/README.md) | Product Queries, Upserts and Bulk Operations |
| [05](experiments/Chapter_05/README.md) | Aggregation Pipelines and Collection Joins |
| [06](experiments/Chapter_06/README.md) | Indexing and Query Performance |
| [07](experiments/Chapter_07/README.md) | MongoDB Architecture, Working Sets and Cache |
| [08](experiments/Chapter_08/README.md) | Replica Sets and Automatic Failover |
| [09](experiments/Chapter_09/README.md) | CAP, Write Concern and Network Partitions |
| [10](experiments/Chapter_10/README.md) | Transactions, Concurrency and Durability |
| [11](experiments/Chapter_11/README.md) | Sharding and Horizontal Scalability |
| [12](experiments/Chapter_12/README.md) | MongoDB Authentication, RBAC and TLS |
| [13](experiments/Chapter_13/README.md) | Container and Kubernetes Deployment |
| [14](experiments/Chapter_14/README.md) | Monitoring, Backup and Restore |
| [15](experiments/Chapter_15/README.md) | Multi-Tenant APIs and Tenant Migration |
| [16](experiments/Chapter_16/README.md) | Cassandra, Neo4j and Hybrid Queries |
| [17](experiments/Chapter_17/README.md) | Vector Search and RAG Foundations |
| [18](experiments/Chapter_18/README.md) | Comparative NoSQL Capstone |

## Local setup

Open this folder in VS Code and use the PowerShell terminal. Start Docker Desktop and wait for the engine to become available. The commands below use a separate MongoDB container bound to localhost for the standalone labs.

```powershell
docker info
py -m venv .venv
.\.venv\Scripts\python.exe -m pip install pymongo python-dotenv rich
docker run -d --name heet-mongo-lab -p 127.0.0.1:27017:27017 mongo:7
docker exec heet-mongo-lab mongosh --quiet --eval "db.adminCommand({ping: 1})"
.\.venv\Scripts\python.exe experiments/Chapter_02/lab_01_setup_environment.py
```

Use `.\.venv\Scripts\python.exe` in place of `python` in the activity tables, or activate the virtual environment first. Install additional dependencies as required by the chapter guide. The [course setup guide](setup/README.md) covers WSL, MongoDB Database Tools and additional services.

Before running a chapter that uses its own stack on port 27017, run `docker stop heet-mongo-lab`. Restart the standalone container with `docker start heet-mongo-lab` once that stack has stopped. The labs can reset collections or databases, so run them against disposable lab data. Keep credentials, backups and keys out of Git.

## Source credit

The lab scripts and course guides are adapted from [Sujeet Jagtap's NoSQL Databases using MongoDB](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4) under [GPL-3.0](LICENSE). Changes include relocated chapter paths, explicit database selection in mongosh scripts, localhost binding for standalone and Chapter 13 lab ports, PyMongo write concern compatibility, and removal of connection strings from the shared connection log. The folder layout follows the [example submission](https://github.com/SOLANKYYY/No_Sql_Mongodb_work).
