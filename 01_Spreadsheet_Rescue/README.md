# 01 — Spreadsheet Rescue

## Project status
Demonstration workbook created. All records are fictional and synthetic.

## Scenario
A fictional skincare retailer has inconsistent order records across 55 source rows.

## What the workbook demonstrates
- Standardising order IDs, dates, customer names, product labels, payment statuses and city formatting.
- Removing one exact duplicate row while retaining a documented note.
- Separating incomplete, invalid or conflicting records into a review queue rather than guessing.
- Maintaining a change log so the cleaning process is transparent.

## Workbook sheets
1. **Read Me** — scenario, scope and summary.
2. **Raw Data** — original messy source records.
3. **Cleaned Data** — records that passed the defined checks.
4. **Review Queue** — records needing clarification.
5. **Change Log** — documented standardisations and exceptions.

## Demonstration results
- 55 source rows
- 46 records in Cleaned Data
- 8 records in Review Queue
- 1 exact duplicate row excluded (retained once and documented)

These counts are specific to this synthetic demonstration, not client results.

## Important decisions
- Conflicting duplicate order IDs are not automatically resolved.
- Missing customer/product/price/quantity values are not invented.
- Invalid dates and non-positive quantities are flagged for review.
- Payment statuses are preserved; this workbook does not calculate revenue.

## File
Upload **Spreadsheet_Rescue_Demo.xlsx** to this folder in the repository.

*This is a skills demonstration, not paid client work.*
