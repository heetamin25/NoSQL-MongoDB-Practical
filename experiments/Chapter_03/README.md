# Practical 03 — Document Modelling and Schema Validation

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Compare embedded and referenced designs and apply document validation.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Inspect the nested course data, try a document that violates a validator, and compare document structure and size after embedding related records.
4. Save your actual output and record your observations below.

Use the local lab MongoDB from the repository setup unless the course guide specifies a different backend.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 3.1 | Design an Embedded Document Schema | [`lab_01_embedded_schema.py`](lab_01_embedded_schema.py) | `python experiments/Chapter_03/lab_01_embedded_schema.py` |
| 3.2 | Migrate from Referenced to Embedded Design | [`lab_02_embed_vs_reference.py`](lab_02_embed_vs_reference.py) | `python experiments/Chapter_03/lab_02_embed_vs_reference.py` |

## Expected result

Record the rejected field and compare the read path and duplication in the two models.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-03) · [All practicals](../README.md)
