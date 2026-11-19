# Practical 16 — Cassandra, Neo4j and Hybrid Queries

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Match MongoDB, Cassandra and Neo4j to different access patterns in a shared application.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Compare document lookup, partition-key retrieval and relationship traversal. Observe the hybrid query results and record whether the graph path uses live Neo4j or the local fallback.
4. Save your actual output and record your observations below.

See the guide for optional live Cassandra and Neo4j services and the local demonstration path.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 16.1 | Model Data in Three Databases | [`lab_01_polyglot_modeling.py`](lab_01_polyglot_modeling.py) | `python experiments/Chapter_16/lab_01_polyglot_modeling.py` |
| 16.2 | Build a Hybrid Query Service | [`lab_02_hybrid_query_service.py`](lab_02_hybrid_query_service.py) | `python experiments/Chapter_16/lab_02_hybrid_query_service.py` |

## Expected result

Identify the database model suited to each request and explain how the databases share common identifiers.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-16) · [All practicals](../README.md)
