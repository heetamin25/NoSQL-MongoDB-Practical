# Practical 10 — Transactions, Concurrency and Durability

**Name:** Heet Deepakkumar Amin  
**USN:** 24BTLCL002

## Aim

Use MongoDB transactions to preserve banking and inventory invariants.

## Procedure

1. Complete [repository setup](../../README.md#local-setup) and check the [course guide](COURSE_GUIDE.md) for this chapter's prerequisites.
2. Run the appropriate activities from the repository root. Use Bash or WSL for shell scripts.
3. Run on a replica set. Compare account balances before and after a transfer. Check the inventory and order state following successful and rejected reservations.
4. Save your actual output and record your observations below.

Use the replica set from Practical 08 or another disposable transaction-capable replica set. Set MONGO_URI to its connection string.

| Activity | Task | Source | Run from repository root |
| --- | --- | --- | --- |
| 10.1 | Implement a Bank Transfer Transaction | [`lab_01_bank_transfer.py`](lab_01_bank_transfer.py) | `python experiments/Chapter_10/lab_01_bank_transfer.py` |
| 10.2 | Inventory Reservation with Transactions | [`lab_02_inventory_reservation.py`](lab_02_inventory_reservation.py) | `python experiments/Chapter_10/lab_02_inventory_reservation.py` |

## Expected result

The total balance should be preserved. Failed reservations should leave neither a partial order nor an inventory decrement.

## Run evidence

| Item | Record after running |
| --- | --- |
| Environment and versions | |
| Output, result file or screenshot | |
| Observations and conclusion | |

[Course source for this chapter](https://github.com/sujeetjagtap/NoSQL-Databases-using-MongoDB/tree/7898bc8907937941a0e2af152654e28f5860bcb4/chapter-10) · [All practicals](../README.md)
