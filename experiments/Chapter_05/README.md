# Practical 05 — Aggregation Pipelines and Collection Joins

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Summarise sales data with an aggregation pipeline and join related records using MongoDB.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Trace how filtering and grouping change the sales result. Follow a sample product key through the lookup stage and inspect the joined array.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 5.1 | Build a Sales Analytics Pipeline | [`lab_01_sales_analytics.py`](lab_01_sales_analytics.py) | `python experiments/Chapter_05/lab_01_sales_analytics.py` |
| 5.2 | Join Data with `$lookup` | [`lab_02_lookup_joins.py`](lab_02_lookup_joins.py) | `python experiments/Chapter_05/lab_02_lookup_joins.py` |

## Expected result

Record a group total and verify it from sample input rows. Confirm that a joined document has the expected key.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-05) · [All practicals](../README.md)
