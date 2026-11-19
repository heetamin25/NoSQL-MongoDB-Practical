# Practical 15 — Multi-Tenant APIs and Tenant Migration

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Scope application queries to a tenant and evaluate migration between isolation strategies.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Create test records belonging to different tenants. Run the tenant-scoped functions and capture the cross-tenant update result. Review the migration dry-run before trying a migration on disposable data.
4. Save your actual output and record your observations below.

Run the Python API demonstration before trying the migration. Use --dry-run for migration first. The migration script can create and remove lab databases.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 15.1 | Design a Multi-Tenant API | [`lab_01_multitenant_api.py`](lab_01_multitenant_api.py) | `python experiments/Chapter_15/lab_01_multitenant_api.py` |
| 15.2 | Data Migration Between Tenant Isolation Strategies | [`lab_02_tenant_migration.py`](lab_02_tenant_migration.py) | `python experiments/Chapter_15/lab_02_tenant_migration.py --dry-run` |

## Expected result

Each tenant should see only its own test records. Compare source and destination counts and document the rollback conditions.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-15) · [All practicals](../README.md)
