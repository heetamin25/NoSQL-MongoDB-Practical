# Practical 02 — Environment Setup and Bookstore CRUD

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Verify the local MongoDB environment and perform create, read, update and delete operations in a bookstore collection.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Check the Docker engine and MongoDB connection. Record one inserted title, its value before and after an update, and the result of a query after deletion.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 2.1 | Environment Setup Verification | [`lab_01_setup_environment.py`](lab_01_setup_environment.py) | `python experiments/Chapter_02/lab_01_setup_environment.py` |
| 2.2 | Bookstore CRUD Operations | [`lab_02_bookstore_crud.py`](lab_02_bookstore_crud.py) | `python experiments/Chapter_02/lab_02_bookstore_crud.py` |

## Expected result

The connection check should succeed and the deleted book should no longer appear in the query results.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-02) · [All practicals](../README.md)
