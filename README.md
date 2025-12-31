# Personal Finance & Investment Tracker (Spreadsheet-Based System)

# Overview 
This project is a modular, spreadsheet-based personal finance system designed for a university student or early-stage investor. 

The system prioritises correct financial logic, data integrity, and long-term maintainability, intentionally avoiding over-automation or fragile integrations that can obscure errors.

# Motivation 

I built this tracker to practice applying financial logic (cash flow, net worth, portfolio valuation) in a structured system, while designing formulas and sheet interactions that are scalable, auditable, and resistant to user error. 

# Key Features

- **Transactions Log** | Centralised log for all cash movements (income, expenses, investments, transfers, receivables), ensuring consistency across all summaries.
- **Expenses Summary** | Automatically aggregates transactions to produce monthly income, expenses, and savings rate. Supports historical analysis via year selection dropdown.
- **Settings Sheet** | Customisable categories, accounts, and transaction types, enabling extensibility without modifying core formulas.
- **Investments Tracker** | Tracks holdings, unrealised P/L, currency conversion, and portfolio value with conditional formatting to surface gains and losses clearly.
- **Net Worth Sheet** | Tracks assets, liabilities, and monthly net worth progression. Manual updates are intentional to preserve transparency and reduce hidden errors. 
- **Data Validation & Sheet Protection** | Constrained input types and protected output cells to minimise accidental edits and logic corruption.
- **Consistent Formatting & UX** | Clear separation between input, calculation, and output zones for ease of use and safety.

# Limitations

The following limitations are intentional design choices to preserve accuracy, transparency, and user trust:

- Investments, net worth, and account balances must be updated manually (design choice for reliability)
- Performance benchmarking (e.g., CAGR vs indices) is intentionally excluded to avoid over-interpretation of short-term returns for beginner investors.
- No dividend tracking or realised P/L calculations.
- Users must manually add formulas for new assets to track live prices and currency conversions.

# Future Extensions 

These extensions intentionally move the system from financial state tracking toward performance analytics and automation.

1. Realised P/L & trade history engine
2. Benchmarking (CAGR vs indices)
3. Automated price feeds (API-based)
4. Web/app version

# How to Use 

1. Add transactions in the Transactions sheet.
2. View summaries in the Expenses, Investments, and Net Worth sheets.
3. Customise categories, accounts, and types in the Settings sheet.
4. Use the year dropdown to view historical summaries.
   
Tip: Only the Transactions sheet requires regular input; all summaries are automatically derived from it.

# Skills Demonstrated

- Spreadsheet engineering: SUMIFS, cross-sheet references, validation rules, conditional formatting
- System design: single source of truth, modular architecture, configuration vs logic separation
- Financial modeling: cash flow, savings rate, net worth tracking, portfolio valuation
- Reliability & UX: constrained inputs, protected outputs, auditability, user-safe layouts

# Sample Data
All data included in this repository is sample data for demonstration purposes. No real personal financial information is used. 
