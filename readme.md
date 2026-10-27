# Loan Default Analysis | Power BI

An end-to-end Business Intelligence project focused on analysing loan defaults, borrower demographics, and financial risk patterns using Power BI and SQL Server.

## Project Overview

This project analyses loan-level data to explore default patterns, compare borrower segments, and understand how lending exposure varies across different groups.

The interactive Power BI dashboard presents key metrics and trends to support data-driven portfolio monitoring and business analysis.

## Business Problem

Loan defaults can affect a lender's financial performance and risk exposure. This project explores questions such as:

- How does the default rate vary across borrower groups?
- What patterns appear across age, income, employment type, and credit score?
- How have loan amounts and defaults changed over time?
- How does the loan amount associated with defaults compare with the overall number of defaults?

## Tools and Technologies

- **Power BI Desktop** — dashboard development and data visualisation
- **DAX** — measures and calculations
- **SQL Server** — data storage and querying
- **Power BI Dataflows** — data preparation and reuse
- **On-premises Data Gateway** — connectivity between the local data source and Power BI services

## Data Pipeline

SQL Server → On-premises Data Gateway → Power BI Dataflow → Power BI Dataset/Semantic Model → Interactive Dashboard

## Dashboard Pages

### 1. Loan Default & Overview
- Loan defaults by purpose
- Average income by employment type
- Default rate by employment type
- Average loan amount across age groups
- Default rate over time

### 2. Applicant Demographics and Financial Profile
- Median loan amount by credit score bands
- Average loan amount by age group and marital status
- Loan amounts across credit score bands
- Loan patterns by mortgage and dependents
- Loan amount by education type

### 3. Financial Risk Metrics
- Year-over-year loan amount change
- Year-over-year change in defaulted loans
- Year-to-date loan amount by credit score band and marital status
- Loan amount by income bracket and employment type

## Key Findings

The accompanying analysis reported the following findings:

- **Overall default rate:** 11.6%, with 29,653 defaults among 255,347 records.
- **Yearly trend:** Annual default rates remained within approximately 11.5%–11.7% from 2013 to 2018.
- **Age groups:** Reported default rates ranged from 22.1% for ages 18–19 to 5.1% for ages 60–69.
- **Income groups:** The reported default rate ranged from 22.0% in the lowest income bracket to 9.5% in the highest.
- **Employment type:** The reported default rate was 13.6% for unemployed borrowers and 9.5% for full-time employees.
- **Default exposure:** Loans associated with defaults represented 13.2% of total loan amount, compared with 11.6% of loans by count.

These are descriptive findings from the documented analysis. They do not establish that any borrower characteristic causes a default.

## Business Value

This dashboard can help users:

- Monitor loan portfolio performance.
- Compare default patterns across borrower segments.
- Explore changes in lending activity over time.
- Identify areas that may require further investigation.

The findings should support further analysis rather than be used alone to make lending decisions.

## Technical Highlights

- Developed a multi-page interactive Power BI dashboard.
- Created DAX calculations for default rates, loan amounts, and time-based comparisons.
- Analysed borrower segments using calculated categories and grouped metrics.
- Worked with SQL Server, Power BI Dataflows, and gateway connectivity.

## Limitations

- The dataset's original source and redistribution permissions should be confirmed separately.
- Observed relationships do not prove causation.
- The analysis is descriptive and does not constitute a validated predictive model.
- A defaulted loan amount is not necessarily equivalent to the lender's actual financial loss.
- Data refresh depends on the configured data source, gateway, and Power BI service settings.

## Repository Contents

- `Loan_Default_Analysis.pbix` — Power BI report
- `Loan_Default_Analysis_Documentation.pdf` — detailed project documentation
- `Screenshots/` — dashboard page previews

## Future Improvements

- Add deeper analysis of potential default risk factors.
- Investigate relationships between borrower characteristics and defaults.
- Explore validated statistical methods or predictive modelling.
- Improve refresh monitoring and recurring risk reporting.

## Conclusion

This project demonstrates how Power BI, DAX, and SQL Server can be used to turn loan-level data into an interactive view of default patterns, borrower characteristics, and financial exposure.
