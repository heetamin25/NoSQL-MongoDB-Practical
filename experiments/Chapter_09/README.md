# Practical 09 — CAP, Write Concern and Network Partitions

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Compare acknowledgement latency and reason about availability during a replica-set partition.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Measure the supplied write concern configurations on the same test workload. Use a disposable replica set to observe member states during and after network isolation.
4. Save your actual output and record your observations below.

Complete Practical 08 first. The course partition script discovers a MongoDB container. Close other MongoDB labs and verify the selected container is part of the disposable replica set before isolating it.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 9.1 | Measure Write Concern Latency | [`lab_01_write_concern_latency.py`](lab_01_write_concern_latency.py) | `python experiments/Chapter_09/lab_01_write_concern_latency.py` |
| 9.2 | Simulate a Network Partition | [`lab_02_simulate_partition.sh`](lab_02_simulate_partition.sh) | `bash experiments/Chapter_09/lab_02_simulate_partition.sh` |

## Expected result

Record timings and acknowledgements. Explain how losing access to a voting majority affects the primary and write availability.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-09) · [All practicals](../README.md)
