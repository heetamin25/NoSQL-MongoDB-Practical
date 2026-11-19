# Practical 04 — Product Queries, Upserts and Bulk Operations

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Build product filters and use upsert and bulk operations to update a catalogue.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Compare filtered and paginated results. Identify the natural key used during an upsert and compare inserted, matched and modified counts across runs.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 4.1 | Build a Product Query API | [`lab_01_product_query_api.py`](lab_01_product_query_api.py) | `python experiments/Chapter_04/lab_01_product_query_api.py` |
| 4.2 | Implement Upsert and Bulk Operations | [`lab_02_upsert_bulk.py`](lab_02_upsert_bulk.py) | `python experiments/Chapter_04/lab_02_upsert_bulk.py` |

## Expected result

Filters should return only matching products. Repeating the same upsert should preserve one document per key.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-04) · [All practicals](../README.md)
