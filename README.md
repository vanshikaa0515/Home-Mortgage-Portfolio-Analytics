# Home Mortgage Portfolio Analytics

Excel-based analysis of a hypothetical mortgage portfolio (500 borrowers) covering CSR targeting, cross-sell segmentation and risk-based pricing.

## Business questions
- **CSR targeting:** where should the bank invest its community outreach budget?
- **Cross-sell segmentation:** which existing customers should be targeted with new products?
- **Risk-based pricing:** which borrower characteristics drive the interest rate?

## Files
- `Home_Mortgage_Dataset.xlsx`: data, formulas, PivotTables, dashboards, regression models and residual plots
- `Home_Mortgage_Dataset_Analysis.pdf`: presentation with the full approach, findings and recommendations

## Key findings
- **CSR:** 85 borrowers (17%) live in areas above 50% minority, and 45 of them are in Location Code 6, so outreach should be concentrated there.
- **Cross-sell:** 76 Silver pool and 41 Golden pool borrowers qualify (109 unique, since 8 overlap).
- **Pricing:** DTI, LTV and first-time buyer status all raise the interest rate. The model explains about 20% of the variation (adjusted R² = 0.20).

## Tools and methods
Excel (nested IF, IF + AND, COUNTIF, COUNTIFS, PERCENTILE), PivotTables and charts, multiple linear regression with forward selection, residual plot checks.

## Limitations
Credit score and loan type etc are not in the data, so the model explains 20% of variation in the interest rate. 
