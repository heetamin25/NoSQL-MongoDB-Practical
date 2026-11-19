# Practical 17 — Vector Search and RAG Foundations

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Retrieve related text passages with embeddings and compare vector index trade-offs.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Use the retrieval pipeline to compare the top passages for example questions. Inspect the HNSW and IVF comparison and note the source of each result.
4. Save your actual output and record your observations below.

Read the guide before using paid embedding or chat APIs. Record which retrieval and embedding path you used.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 17.1 | Build a Simple RAG Pipeline | [`lab_01_rag_pipeline.py`](lab_01_rag_pipeline.py) | `python experiments/Chapter_17/lab_01_rag_pipeline.py` |
| 17.2 | Compare HNSW and IVF Vector Index Types | [`lab_02_hnsw_vs_ivf.py`](lab_02_hnsw_vs_ivf.py) | `python experiments/Chapter_17/lab_02_hnsw_vs_ivf.py` |

## Expected result

Record passage ranks or scores and explain the speed and recall trade-off. Label any simulated figures.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-17) · [All practicals](../README.md)
