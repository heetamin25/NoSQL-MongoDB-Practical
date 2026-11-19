# Practical 13 — Container and Kubernetes Deployment

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Compare a container-based replica set with a Kubernetes StatefulSet deployment.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Review the Compose services and volumes. Generate the Kubernetes manifests and inspect the headless service, stable pod names and volume claims.
4. Save your actual output and record your observations below.

Run the Compose activity with Docker. Inspect the generated StatefulSet locally before optionally applying it to a disposable Kubernetes cluster.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 13.1 | Deploy a Production Replica Set with Docker Compose | [`lab_01_deploy_prod.sh`](lab_01_deploy_prod.sh) | `bash experiments/Chapter_13/lab_01_deploy_prod.sh` |
| 13.2 | Kubernetes StatefulSet for MongoDB | [`lab_02_k8s_statefulset.py`](lab_02_k8s_statefulset.py) | `python experiments/Chapter_13/lab_02_k8s_statefulset.py` |

## Expected result

Record container or pod state and explain where data persists across a restart. Manifest inspection can be recorded separately from a live deployment.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-13) · [All practicals](../README.md)
