# Practical 12 — MongoDB Authentication, RBAC and TLS

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Demonstrate least-privilege roles, encrypted transport and field redaction in a disposable database.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Compare a reader account with a writer, test a TLS-required connection with the lab CA, and compare raw documents with the redacted view.
4. Save your actual output and record your observations below.

Use a disposable local instance with no production data. The course scripts contain demonstration passwords. Use lab-only credentials and keep TLS keys out of Git.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 12.1 | Configure Authentication and RBAC | [`lab_01_rbac_setup.sh`](lab_01_rbac_setup.sh) | `bash experiments/Chapter_12/lab_01_rbac_setup.sh` |
| 12.2 | TLS / Encryption-in-Transit Setup | [`lab_02_tls_setup.sh`](lab_02_tls_setup.sh) | `bash experiments/Chapter_12/lab_02_tls_setup.sh` |
| 12.3 | Field-Level Redaction via Views | [`rbac_field_redaction.py`](rbac_field_redaction.py) | `python experiments/Chapter_12/rbac_field_redaction.py` |

## Expected result

Record which actions were permitted, which connection passed, and which fields remained visible through the view.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-12) · [All practicals](../README.md)
