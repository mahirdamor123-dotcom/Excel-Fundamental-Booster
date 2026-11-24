# PR. 1 Fundamental Booster — README

## Purpose

This workbook is a completed Excel practice project based on the supplied screenshots. It includes the source datasets, formula examples, calculated results, and a dynamic student list for practicing core Excel functions.

## Workbook tabs

- **Start** — overview and editable grade and discount practice assumptions.
- **Students** — the 20 student records, with calculated average scores, letter grades, score checks, and first names.
- **Sales** — the 20 sales records, with month and lookup keys, discount eligibility, discount rates, discount amounts, and net amounts.
- **Employees** — the 20 employee records, including salary and joining date.
- **Product Lookup** — product-level average sales amounts and counts for lookup practice.
- **Exercises** — examples covering relative and absolute references, IF and nested IF, AND/OR, COUNTIF/COUNTIFS, SUMIFS, AVERAGEIFS, VLOOKUP, INDEX/MATCH, text functions, XLOOKUP, XMATCH, INDIRECT, OFFSET, date and time, rounding, and FILTER.

## How to use it

1. Start on **Exercises** and review the formula results and notes.
2. Change the amber cells in the Practice input area to try different criteria, IDs, dates, ranges, or filter cutoffs.
3. Review the linked formulas and results on the source tabs. On **Students**, the grade and helper columns are calculated from the source scores. On **Sales**, discount calculations use the rules described below.
4. Change the average-score cutoff in **Exercises!E21** to update the filtered student list below the exercise table.

## Practice assumptions and data limits

- Grade bands use the average of Math, Science, and English: A at 90+, B at 80+, C at 70+, D at 60+, and F below 60. The cutoffs are editable on **Start**.
- Sales discount practice uses 10% at amounts of 30,000 or more, 5% at amounts of 15,000–29,999.99, and 0% below 15,000. The separate IF/OR eligibility example is true for South region sales or amounts of 30,000 or more. These are practice rules, not rules supplied by a business.
- The screenshots do not provide dates of birth. The age formula uses a sample DOB and as-of date on **Exercises**; replace those values to try a different case.
- The screenshots do not provide product unit prices. **Product Lookup** uses average transaction Amount by product as a proxy for VLOOKUP practice. It should not be interpreted as an actual unit price.
- All displayed source data was transcribed from the screenshots. Verify against the original workbook if exact source fidelity is important.

## Formula notes

The Exercises sheet shows a sample formula result for each concept. Some formula examples use modern Excel functions such as XLOOKUP and FILTER, which require a compatible Excel version. The FILTER output is a dynamic array and spills into the rows below its formula.
