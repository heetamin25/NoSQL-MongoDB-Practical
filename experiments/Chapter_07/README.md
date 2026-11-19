# Practical 07 — MongoDB Architecture, Working Sets and Cache

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Evaluate document size, working-set size and their effect on MongoDB storage and reads.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Inspect the example schema for large or growing fields. Run the working-set analysis and compare a frequently accessed subset with the full data size.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 7.1 | Analyze a Production Schema | [`lab_01_production_schema.py`](lab_01_production_schema.py) | `python experiments/Chapter_07/lab_01_production_schema.py` |
| 7.2 | Working Set Analysis | [`lab_02_working_set_analysis.py`](lab_02_working_set_analysis.py) | `python experiments/Chapter_07/lab_02_working_set_analysis.py` |

## Expected result

Explain which data needs to remain hot and how a schema change could reduce the bytes read by common queries.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-07) · [All practicals](../README.md)
