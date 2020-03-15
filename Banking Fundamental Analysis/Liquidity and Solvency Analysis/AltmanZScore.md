# Altman Z Score Compilation and Analysis

## 1.	Altman Z Score requirements:
- Working Capital (Current Assets - Current Liabilities)
    - Current Assets: `assets_curr` `AssetsCurrent`
    - Current Liabilities: `liabs_curr`
- Total Assets: `assets`
- Retained Earnings: `com_eq_retain_earn`
- Earnings Before Interest and Tax (EBIT): `ebit`
- Market Value: `mkt_val`
- Total Liabilities: `liabs`
- Sales (Net Interest Income + Non Interest Income)
    - Net Interest Income: `int_inc_net_af`
    - Non Interest Income: `non_int_inc_af`

___

| Current Assets      | `assets_curr`        | `AssetsCurrent`                |
|---------------------|----------------------|--------------------------------|
| Current Liabilities | `liabs_curr`         | `LiabilitiesCurrent`           |
| Total Assets        | `assets`             | `Assets`                       |
| Retained Earnings   | `com_eq_retain_earn` | `RetainedEarningsAppropriated` |
| EBIT                | `ebit`               |                                |
| Market Value        | `mkt_val`            |                                |
| Total Liabilities   | `liabs`              |                                |
| Sales               |                      |                                |
| Net Interest Income | `int_inc_net_af`     |                                |
| Non Interest Income | `non_int_inc_af`     |                                |


___
- Working Capital/Total Assets
- Retained Earnings/Total Assets
- Earnings Before Interest and Tax/Total Assets
- Market Value of Equity/Total Liabilities
- Sales/Total Assets
## 2.	Weights:
-	1.2, 1.4, 3.3, 0.6, 1.0
## 3.	Benchmarks
- < 1.81 = Distress
- 1.81 – 2.99 = Grey zone
- \> 2.99 Safe zone
## 4.	Are banks calculating their own Altman Z Score to keep it under certain thresholds?

