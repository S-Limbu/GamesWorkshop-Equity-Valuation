\# Games Workshop Group plc — Equity Valuation



\## Project Overview



This project presents a financial analysis and valuation of Games Workshop Group plc (LSE: GAW).



The project combines historical financial analysis, forecast modelling, discounted cash flow (DCF) valuation, trading comparables, sensitivity analysis and Python-based financial analysis.



The valuation is anchored to a valuation date of 1 June 2025.



\---



\## Project Objective



The objective of this project is to demonstrate the application of equity research and valuation techniques to a publicly listed company.



The analysis covers:



\- Historical financial performance

\- Revenue and operating profit forecasting

\- Unlevered free cash flow (UFCF)

\- Weighted average cost of capital (WACC)

\- Discounted cash flow valuation

\- Terminal value using the Gordon Growth Method

\- Enterprise value and equity value

\- Implied share price

\- Trading comparables

\- DCF sensitivity analysis

\- Python-based financial analysis and visualisation



\---



\## Key Valuation Results



| Metric | Result |

|---|---:|

| Valuation Date | 1 June 2025 |

| WACC | 8.9% |

| Terminal Growth Rate | 2.0% |

| Enterprise Value | £2,980.2m |

| Equity Value | £3,067.6m |

| Implied Share Price | £93.04 |



The DCF valuation is based on a five-year explicit forecast period from FY2026 to FY2030.



\---



\## Historical Financial Performance



Games Workshop's reported revenue increased from approximately £369.5m in FY2021 to £617.5m in FY2025.



Operating profit increased from approximately £151.7m to £261.3m over the same period.



The historical analysis examines revenue growth, profitability, cash generation and other key financial indicators.



\---



\## Valuation Methodology



\### Discounted Cash Flow



The DCF model forecasts unlevered free cash flow over FY2026–FY2030.



The projected cash flows are discounted using an 8.9% WACC.



A 2.0% perpetual growth rate is used to calculate terminal value.



The resulting enterprise value is then adjusted for cash and lease liabilities to derive equity value.



\### Trading Comparables



The trading comparables analysis considers:



\- Hasbro

\- Mattel

\- Funko

\- Character Group



Games Workshop is excluded from the peer median calculation.



Peer median valuation multiples are calculated for:



\- EV / Revenue

\- EV / EBITDA

\- P / E



\---



\## Sensitivity Analysis



The DCF valuation is tested across a range of WACC and terminal growth assumptions.



The sensitivity analysis demonstrates how changes in these assumptions affect the implied equity value per share.



The model uses:



\- WACC range: 7.9%–9.9%

\- Terminal growth range: 1.0%–3.0%



\---



\## Python Analysis



The Python analysis provides an independent implementation of the valuation analysis using:



\- Python

\- pandas

\- NumPy

\- Matplotlib



The notebook includes:



\- Historical financial analysis

\- Forecast calculations

\- DCF calculations

\- Sensitivity analysis

\- Financial charts

\- DCF sensitivity heatmap



The Python implementation is intended as an independent analytical exercise and does not exactly reconcile to every assumption used in the Excel model.



\---



\## Repository Structure



```text

GamesWorkshop-Equity-Valuation/

│

├── 01\_Excel\_Model/

│   └── GamesWorkshop\_Historicals.xlsx

│

├── 02\_Python\_Analysis/

│   └── GamesWorkshop\_DCF\_Portfolio\_Final\_With\_Graphs.ipynb

│

├── 03\_Equity\_Research\_Report/

│   └── GamesWorkshop\_Equity\_Research\_Report.pdf

│

├── 04\_Sources/

│   ├── Annual report PDFs

│   └── README.md

│

├── README.md

└── .gitignore



Data Sources



The analysis primarily uses Games Workshop Group plc annual reports and company financial disclosures.



The original annual report documents used in the analysis are retained in the 04\_Sources folder.



The sources folder contains the historical annual reports used to construct the financial dataset.



Important Modelling Note



The Excel model contains a small FY2028 assumption inconsistency: the Forecast Assumptions sheet shows a 6.85% capex-to-revenue assumption, while the Cash Flow sheet uses 6.9%.



The Cash Flow assumption is used for the UFCF calculation and therefore drives the DCF valuation.



FY2028 and FY2030 working-capital changes are also hardcoded in the Cash Flow sheet.



These points are disclosed for transparency.



Disclaimer



This project is for educational and portfolio purposes only.



It does not constitute investment advice, a recommendation, or an offer to buy or sell securities.



The valuation reflects assumptions and market data used for the stated valuation date and should not be interpreted as a current investment view.





