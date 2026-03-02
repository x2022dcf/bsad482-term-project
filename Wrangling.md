# Data Wrangling – Milestone 2

## Overview

This document outlines the cleaning and preparation steps performed on the Statistics Canada datasets used in this analysis.

The goal is to ensure consistency across datasets when comparing employment and income outcomes by field of study (CIP) in Ontario.

---

## Dataset 1: Labour Force Status by Field of Study (CIP)

Cleaning Steps:
- Removed metadata rows at the top of the CSV (title rows from StatsCan export)
- Verified correct header row
- Filtered geography to Ontario
- Removed unnecessary columns (e.g., flags, symbols if present)
- Ensured employment rate and unemployment rate values are numeric

---

## Dataset 2: Earnings by Field of Study (Income)

Cleaning Steps:
- Removed metadata rows
- Filtered geography to Ontario
- Selected total population or relevant education category
- Converted income column to numeric
- Checked for missing values

---

## Dataset 3: Median Earnings of Postsecondary Graduates (Post-Grad Outcomes)

Cleaning Steps:
- Removed metadata rows
- Filtered to Ontario
- Selected relevant field-of-study groupings
- Verified median income values are numeric
- Checked year consistency across datasets

---

## Notes

- All datasets were prepared for analysis in Tableau.
- Ontario was selected as the geographic focus.
- CIP groupings were kept consistent where possible.
