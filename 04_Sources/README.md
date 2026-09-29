# Sources

This folder contains the primary source documents used for the financial analysis and valuation model.

## Primary Company Sources

The following Games Workshop Group plc annual reports were used as the main source material for historical financial data:

- `2020-21-accounts-full-report-cover.pdf` — Games Workshop Group plc FY2020/21 accounts
- `2021-22-accounts-Final-NoM.pdf` — Games Workshop Group plc FY2021/22 accounts
- `2022-23_accounts_-_final.pdf` — Games Workshop Group plc FY2022/23 accounts
- `2023-24_accounts_-_final.pdf` — Games Workshop Group plc FY2023/24 accounts
- `Accounts_2024-25_FINAL.pdf` — Games Workshop Group plc FY2024/25 Annual Report

These reports were used to obtain historical financial information including revenue, operating profit, profit before tax, net profit, operating cash flow, capital expenditure, cash, lease liabilities and other financial statement information used in the Excel model.

## Valuation Methodology

The DCF valuation methodology was informed by:

- Aswath Damodaran — Discounted Cash Flow Valuation methodology

The valuation uses a five-year explicit forecast period followed by a terminal value approach.

## Market Data

Trading comparable data used in the analysis represents the market-data snapshot incorporated into the portfolio model.

The comparable-company analysis includes:

- Games Workshop Group plc
- Hasbro
- Mattel
- Funko
- Character Group

Games Workshop is excluded from the peer median calculation because it is the subject company being valued.

Market-data inputs may not align perfectly with the 1 June 2025 valuation date and are presented as the market-data snapshot used in the portfolio model.

## Data Usage

The historical financial data in the Excel model was compiled from the company reports contained in this folder.

The Excel model is the primary valuation model, while the Python notebook provides a separate analytical implementation using pandas, NumPy and Matplotlib.

## Note

This project is an educational portfolio exercise. The analysis reflects the author's modelling assumptions and methodology and is not investment advice.
