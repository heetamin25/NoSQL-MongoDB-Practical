# Practical 08 — Replica Sets and Automatic Failover

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Deploy a local replica set and observe primary election and data replication.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Use an isolated Docker lab. Record the initial member roles. Follow the failover observer and capture member states before and after the election.
4. Save your actual output and record your observations below.

On Windows, use WSL with Docker Desktop integration and install mongosh in the shell that runs the script. The supplied topology uses host.docker.internal. Check that your Docker environment resolves it before starting.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 8.1 | Deploy a Local Replica Set | [`lab_01_deploy_replicaset.sh`](lab_01_deploy_replicaset.sh) | `bash experiments/Chapter_08/lab_01_deploy_replicaset.sh` |
| 8.2 | Observe Failover and Election | [`lab_02_failover_observer.py`](lab_02_failover_observer.py) | `python experiments/Chapter_08/lab_02_failover_observer.py` |

## Expected result

A healthy majority should elect a primary after a failure. Record the observed election delay and the recovery state.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-08) · [All practicals](../README.md)
