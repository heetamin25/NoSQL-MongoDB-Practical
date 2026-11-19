# Practical 14 — Monitoring, Backup and Restore

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Monitor a MongoDB lab server and verify a backup by restoring test data.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Inspect server metrics and record a baseline. Back up the disposable dataset, restore it with the database tools, and compare pre- and post-restore data.
4. Save your actual output and record your observations below.

Install the MongoDB Database Tools and ensure mongodump and mongorestore are on PATH. Use a disposable database and verify the restore target before running.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 14.1 | Build a Monitoring Dashboard | [`lab_01_monitoring_dashboard.py`](lab_01_monitoring_dashboard.py) | `python experiments/Chapter_14/lab_01_monitoring_dashboard.py` |
| 14.2 | Automated Backup and Restore Verification | [`lab_02_backup_restore.py`](lab_02_backup_restore.py) | `python experiments/Chapter_14/lab_02_backup_restore.py` |

## Expected result

Record the metrics sampled, the backup location, and verification counts or sample IDs from the restore.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-14) · [All practicals](../README.md)
