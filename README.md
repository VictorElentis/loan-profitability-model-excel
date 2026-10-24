 README for repo: loan-profitability-model-excel

# Loan Profitability and Expected Loss Model (Excel)

A formula-driven Excel model that shows whether a loan creates value for a bank, after funding costs, operating costs, expected credit losses and the cost of the capital held against it.

## What it does
- **Inputs:** loan amount, interest rate, term, origination fee, cost of funds, operating cost, probability of default (PD), loss given default (LGD), capital held, required return and tax rate
- **Schedule:** a monthly amortization schedule with interest, principal, expected loss, profit, tax and capital held
- **Summary:** total interest, net income, return on capital against a hurdle rate, economic profit, and the break-even interest rate
- **Sensitivity:** monthly payment by rate and term, and risk-adjusted margin by rate and PD

## Example result (base case: $250,000 at 7.5% over 5 years)
- Monthly payment about $5,009; borrower pays about $50,569 in interest
- Expected credit loss about $4,551 over the life of the loan
- Return on capital about 14.8% against a 12% hurdle, so the loan creates value
- Break-even rate about 6.3%; the loan earns about 1.2 points above it

All assumptions are illustrative and are not any bank's real figures.

## How to use
Download `loan_profitability_model.xlsx`, open it in Excel and change the yellow cells on the Inputs sheet. Everything else recalculates.

## Skills shown
Excel formulas (PMT, INDEX, IF, SUM), financial modeling conventions, credit risk concepts (PD, LGD, expected loss), sensitivity analysis and conditional formatting.
