# DiabetaInsight — Data Sources & Authenticity

## ✅ Real Government Data
| Dataset | Source | Year | URL |
|---|---|---|---|
| Diabetes Prevalence (28 states) | ICMR-INDIAB Study | 2023 | Lancet Diabetes Endocrinol, 11(7):474-489 |
| Health Indicators (131 per state) | NFHS-5, MoHFW GoI | 2019-21 | rchiips.org/nfhs |
| Drug Ceiling Prices | NPPA Notifications | 2025 | nppaindia.nic.in |
| Population Projections | Census 2011, RGI | 2021 | censusindia.gov.in |
| Per Capita Income | RBI State Finances | 2023-24 | rbi.org.in |

## ⚠️ Methodology Demonstration Data
| Dataset | Actual Source | Used For |
|---|---|---|
| Pharma Sales Dataset | Serbian pharmacy chain (Kaggle) | Sales trend methodology only |
| Territory Sales | Simulated using population weights | Territory gap analysis framework |

## Why This Approach is Valid
Real pharma commercial data (IQVIA, AIOCD AWACS) costs lakhs/year and
is proprietary. This project uses real epidemiological and pricing data
for market analysis, and a proxy dataset to demonstrate analytical
methodology — standard practice in academic and consulting contexts.
In production, the sales layer would be replaced with IQVIA data.
