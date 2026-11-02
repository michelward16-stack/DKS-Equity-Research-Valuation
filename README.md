# Dick's Sporting Goods (NYSE: DKS) Equity Research & Valuation

Solo project for Corporate Finance at Hult International Business School (December 2025), built to CFA Research Challenge standards.

## Result

| Case | Value per share |
|---|---|
| Price (Dec 3, 2025) | $228.08 |
| Base case target | **$229.00** |
| Bull case | $240.09 |
| Bear case | $102.89 |

## Method

* Five year forecast of the income statement, balance sheet and cash flow statement (FY2026 to FY2030)
* Holt Winters seasonal model for the FY2026 revenue baseline, then 4% normalized growth
* DCF on unlevered free cash flow: WACC 8.46% (regression beta 1.225, risk free rate 4.0%, equity risk premium 4.5%), terminal growth 2.5%
* Bull, base and bear scenario analysis on growth, gross margin, SG&A and capex
* Trading multiples (EV/Sales, EV/EBIT, EV/EBITDA, P/E) against sporting goods and specialty retail peers

**Tools:** Excel

## Screenshots

![DCF valuation](images/dcf.png)
*DCF valuation output*

![Scenario analysis](images/scenarios.png)
*Bull, base and bear scenarios*

![Trading multiples](images/multiples.png)
*Relative valuation against peers*

![WACC sensitivity](images/wacc.png)
*Cost of capital and sensitivity analysis*

## Files

* [Equity research report (PDF)](DKS_Equity_Research_Report.pdf)
* [Valuation model (Excel)](DKS_Valuation_Model.xlsx), click "Download raw file" to open it in Excel

## What I'd do differently

The report rated DKS a BUY. With only 0.4% upside in the base case and a bear case of $103, I would rate it HOLD today. The project taught me to match the rating to the full risk and reward, not just the base case.
