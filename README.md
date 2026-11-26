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
| Transaction ID | Unique code | ... None Found|
| Item | Menu item name | 292 ERROR, 344 UNKNOWN, 333 blank |
| Quantity | Whole number | 170 ERROR, 171 UNKNOWN, 138 blank |
| Price Per Unit | Number | 190 ERROR, 164 UNKNOWN, 179 blank |
| Total Spent | Quantity × Price | 164 ERROR, 165 UNKNOWN, 173 blank |
| Payment Method | Cash / Credit Card / Digital Wallet | 306 ERROR, 293 UNKNOWN, 2579 blank |
| Location | In-store / Takeaway | 358 ERROR, 338 UNKNOWN, 3265 blank |
| Transaction Date | Real date | 142 ERROR, 159 UNKNOWN, 159 blank |

Data: see sources.txt. Status: in progress.

 Progress: see issue #1