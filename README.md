# Tesco PLC — DCF Valuation Model

## Overview
A full Discounted Cash Flow (DCF) valuation model for Tesco PLC (LSE: TSCO), the UK's largest supermarket and one of the world's biggest retailers by revenue. Built independently to apply and demonstrate core investment banking valuation methodology.

The model projects **2026–2030 Unlevered Free Cash Flows**, discounts them at a calculated WACC, applies a Gordon Growth terminal value, and bridges from Enterprise Value to an implied equity value per share — the complete end-to-end DCF process used by investment banking analysts every day.

---

## Key Output

| Metric | Value |
|--------|-------|
| Enterprise Value | £31,273m |
| Less: Net Debt | £7,835m |
| **Equity Value** | **£23,438m** |
| Diluted Shares Outstanding | 500m |
| **Implied Share Price** | **£46.88** |
| Market Price at Valuation Date | £25.00 |
| **Upside / (Downside)** | **+87.5%** |

**Investment Conclusion:** The DCF implies Tesco is significantly undervalued at £25.00 — trading at a 47% discount to intrinsic value. At this price the stock is a clear buy.

---

## Model Architecture

### Revenue & Operating Projections (2023A–2030E)

| Year | Revenue (£m) | EBITDA (£m) | EBITDA Margin | EBIT (£m) |
|------|-------------|-------------|---------------|-----------|
| 2023A | 65,322 | 3,722 | 5.7% | 2,595 |
| 2024A | 68,187 | 3,970 | 5.8% | 2,819 |
| 2025E | 69,916 | 4,224 | 6.0% | 2,999 |
| 2026E | 72,013 | 4,321 | 6.0% | 3,097 |
| 2027E | 74,174 | 4,450 | 6.0% | 3,189 |
| 2028E | 76,399 | 4,584 | 6.0% | 3,285 |
| 2029E | 78,691 | 4,721 | 6.0% | 3,384 |
| 2030E | 81,052 | 4,863 | 6.0% | 3,485 |

Revenue projected at **3% YoY growth** from 2026E onwards, consistent with UK grocery sector long-run nominal growth. EBITDA margins held at 6.0%, in line with Tesco's recent trajectory following its operational efficiency programme.

---

### Free Cash Flow Build

| Item | Basis |
|------|-------|
| EBIT | Projected as above |
| Tax Rate | 25% |
| D&A | 1.8% of revenue |
| CapEx | ~2.0% of revenue |
| Change in Working Capital | Driven by AR, inventory and payables growth at 3% |
| **Unlevered FCF (2026E)** | **£2,315m** |
| **Unlevered FCF (2030E)** | **£2,606m** |

---

### WACC Calculation

| Component | Value |
|-----------|-------|
| Cost of Equity | 15.0% (CAPM: Rf + β × Market Risk Premium) |
| Pre-tax Cost of Debt | 5.2% |
| After-tax Cost of Debt | 3.9% |
| Debt Weighting | 44.8% |
| Equity Weighting | 55.2% |
| **WACC** | **10.02%** |

---

### Terminal Value

| Component | Value |
|-----------|-------|
| Method | Gordon Growth (Perpetuity Growth) |
| Long-term Growth Rate | 2.5% |
| WACC | 10.02% |
| Terminal Year FCF (t+1) | £2,671m |
| **Terminal Value** | **£35,492m** |
| **PV of Terminal Value** | **£22,013m** |
| TV as % of Total EV | 70.4% |

---

### Enterprise Value Bridge

| Component | Value (£m) |
|-----------|-----------|
| PV of FCFs (Stage 1) | 9,260 |
| PV of Terminal Value (Stage 2) | 22,013 |
| **Enterprise Value** | **31,273** |
| Less: Net Debt (Debt - Cash) | (7,835) |
| **Equity Value** | **23,438** |
| Per Share (500m diluted shares) | **£46.88** |

---

## Why Tesco
Tesco was selected as the DCF subject because it is:
- The UK's largest retailer by revenue — a highly visible, well-covered name with rich public data
- A business with relatively stable, predictable cash flows — ideal for a DCF framework
- An active participant in M&A (acquisition of Booker, proposed merger with Sainsbury's blocked by CMA) — commercially interesting from an advisory perspective
- A company with meaningful net debt and working capital complexity — good technical challenge for modelling

---

## Files
- `Tesco_DCF_Model.xlsx` — Full DCF model including FCF projections, WACC build, terminal value and equity bridge

---

## Author
**Asad Mahmood** | Second Year, BSc Accounting & Finance, Keele University (Predicted First Class)

[LinkedIn](https://www.linkedin.com/in/) | [GitHub](https://github.com/Asad-ux2005)
