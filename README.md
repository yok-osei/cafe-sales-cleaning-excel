# C1 project
Project C1: cleaning Ghana macro data in Excel
# Cafe Sales: Repairing a Dirty Sales File (Excel)

A cafe's sales export (about 10,000 transactions) is full of errors: ERROR and
UNKNOWN typed into number and date columns, blank cells, and numbers stored as text.
This project finds every problem, repairs what can be repaired with business logic,
and documents each change.

## The problems I found

| Column | Should hold | Problems found |
|---|---|---|
| Transaction ID | Unique code | ... No Missing Values|
| Item | Menu item name | ... ERROR, ... UNKNOWN, ... blank |
| Quantity | Whole number | ... |
| Price Per Unit | Number | ... |
| Total Spent | Quantity × Price | ... |
| Payment Method | Cash / Credit Card / Digital Wallet | ... |
| Location | In-store / Takeaway | ... |
| Transaction Date | Real date | ... |

Data: see sources.txt. Status: in progress.