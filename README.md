# The Fireside Model

A polls-free forecasting model for U.S. midterm House elections.

## Overview

The Fireside Model predicts House seat changes for the president's party using five publicly available economic indicators. No polls, no approval ratings, no expert ratings.

**R-squared = 0.83 | Mean Absolute Error = 6.5 seats | Based on 12 midterm elections (1978-2022)**

## The Equation

House Seat Change = -13.83 + (2.28 x CPI-Food%) + (-1.68 x CPI-Energy%) + (-1.29 x Consumer Sentiment) + (-5.43 x GDP%) + (-0.04 x Initial Jobless Claims Change in 000s)

## Variables

| Variable | Source | Frequency |
|----------|--------|-----------|
| CPI-Food % Change | BLS | Monthly |
| CPI-Energy % Change | BLS | Monthly |
| Consumer Sentiment Pt Change | Univ. of Michigan | Monthly |
| GDP Growth Rate % | BEA | Quarterly |
| Initial Jobless Claims Change | DOL | Weekly |

All data measured from February of inauguration year through October of midterm year.

## Files

- `index.html` — Interactive website with calculator and historical data
- `FiresideModelV17.xlsx` — Complete dataset with Consumer and Institutional worksheets
- `Manuscript.docx` — Research paper. Link to paper: TBD

## Data Source

All data from [FRED](https://fred.stlouisfed.org) (Federal Reserve Economic Data), freely available.

---

© Dr. Harish Gupta, DPA
Helms School of Government, Liberty University (Alumni)

Dedicated in Honor of 32nd President Franklin Delano Roosevelt.
