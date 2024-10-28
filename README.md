# HDB Resale Calculator for PR First-Time Buyers

A web-based calculator tool to help Permanent Residents (PRs) in Singapore calculate various costs and loan eligibility when purchasing their first HDB resale flat.

## Features

### 1. Price Calculator
- Calculate bank loan amount (75% of purchase price)
- Calculate required down payment (25%)
  * Minimum cash requirement (5%)
  * CPF/Cash portion (20%)
- Calculate ABSD (Additional Buyer's Stamp Duty - 5% for PR first-time buyers)
- Calculate agent fee (customizable percentage)
- Show total upfront cash/CPF needed

### 2. TDSR Calculator (Total Debt Servicing Ratio)
- Input monthly income (single or combined household income)
- Input other monthly debt obligations
- Calculate maximum monthly debt payments (55% limit)
- Show available amount for housing loan

### 3. MSR Calculator (Mortgage Servicing Ratio)
- Input monthly income (single or combined household income)
- Calculate maximum monthly mortgage payment (30% limit)

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Bootstrap 5.3.0
- No backend required - all calculations done client-side

## Installation

1. Clone the repository
```bash
git clone [your-repository-url]
```

2. No additional installation required - just open `index.html` in a web browser

## Usage

1. Enter the property price in the main calculator
2. (Optional) Adjust agent fee percentage
3. Click "Calculate" to see breakdown of costs
4. Use TDSR calculator to check debt servicing limits
5. Use MSR calculator to check mortgage servicing limits

## Important Notes

### For PR First-Time Buyers
- Bank loan maximum: 75% of property value
- Minimum cash down payment: 5% of property value
- CPF/Cash down payment: 20% of property value
- ABSD: 5% of property value
- Must be a PR for at least 3 years before purchasing

### Loan Limits
- TDSR: Maximum 55% of monthly income
- MSR: Maximum 30% of monthly income
- Both TDSR and MSR can use combined household income if applying as a family

## Limitations
- Calculations are estimates only
- Actual loan approval depends on bank assessment
- Property valuation may affect final loan amount
- Rules and regulations may change
- Please verify current rates and policies with relevant authorities

## Disclaimer
This calculator is for estimation purposes only. Actual costs, loan eligibility, and requirements may vary. Please consult with banks, HDB, and relevant authorities for the most current information and regulations.

## Updates and Maintenance
Last updated: April 2024
Rules and regulations reflected are accurate as of April 2024. Please check official HDB website for any recent changes.

## License

MIT License

Copyright (c) 2024 Jacky Kiu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.