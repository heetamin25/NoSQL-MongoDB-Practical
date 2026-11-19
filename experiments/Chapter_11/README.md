# Practical 11 — Sharding and Horizontal Scalability

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Evaluate shard key candidates and identify uneven distribution.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Compare candidate keys by cardinality, frequency, monotonicity and query targeting. Inspect distribution or simulated hotspot output for skew.
4. Save your actual output and record your observations below.

Check the course guide for which activities use a live sharded cluster and which output is simulated or analytical.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 11.1 | Evaluate Shard Key Choices | [`lab_01_shard_key_eval.py`](lab_01_shard_key_eval.py) | `python experiments/Chapter_11/lab_01_shard_key_eval.py` |
| 11.2 | Shard Key Hotspot Detection | [`lab_02_shard_key_hotspot.py`](lab_02_shard_key_hotspot.py) | `python experiments/Chapter_11/lab_02_shard_key_hotspot.py` |

## Expected result

Recommend a shard key for the example access pattern and explain how it affects targeted queries and write distribution.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-11) · [All practicals](../README.md)
