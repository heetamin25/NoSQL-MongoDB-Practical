# Practical 06 — Indexing and Query Performance

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Select indexes for a query workload and compare their effect on query plans.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Run the same filters before and after creating indexes. Compare scanned documents, examined keys and whether MongoDB performs an in-memory sort.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 6.1 | Index Design for a Query Workload | [`lab_01_index_design.py`](lab_01_index_design.py) | `python experiments/Chapter_06/lab_01_index_design.py` |
| 6.2 | Compare Index Strategies | [`lab_02_index_strategies.py`](lab_02_index_strategies.py) | `python experiments/Chapter_06/lab_02_index_strategies.py` |

## Expected result

Record the winning plan and examination counts. Explain the write overhead of maintaining the selected indexes.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-06) · [All practicals](../README.md)
