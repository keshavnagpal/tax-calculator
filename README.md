# tax-calculator

Command line script to calculate taxes and in hand salary

## Usage

```
usage: income.py [-h] -s SALARY [--metro | --no-metro] [--pf | --no-pf]

Calculates and compares in-hand income under Old and New Tax Regimes for FY 2025-26.

optional arguments:
  -h, --help            show this help message and exit
  -s SALARY, --salary SALARY
                        Your gross annual salary (CTC). 
  --metro, --no-metro   If you live in a metro city (e.g., Delhi, Mumbai). 
  --pf, --no-pf         If Provident Fund is part of your CTC.
```

## Note:

- Script Assumes Deductions under 80C, 80D, Section 10(13A) in old tax regime
- No deductions are allowed in new tax regime (only employer pf is deducted if it is inclusive in salary)
- To know more about income-tax slabs go to [income-tax-india](https://www.incometaxindia.gov.in/_layouts/15/dit/mobile/viewer.aspx?path=https://www.incometaxindia.gov.in/charts++tables/tax+rates.htm&k&IsDlg=0)


## Sample Report:

<img width="581" height="493" alt="image" src="https://github.com/user-attachments/assets/3bc5e79d-4d94-4805-87e8-64ea0f91a617" />
