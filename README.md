# NBFI Loan Portfolio Analysis · Customer Segmentation · NPL Classification · Geographic Targeting

**Company:** Omnicapital NBFI, Mongolia · B2B and B2C traditional lending  
**Products:** Car loans · vehicle collateralized · real estate · business loans · express loans · consumer loans

---

## Executive Summary

As part of the same company-wide rebranding initiative triggered by the UX and product observations presented at a senior leadership review, Omnicapital's loan portfolio was analyzed to understand customer profiles, loan quality, and geographic distribution. Unlike Moni, Omnicapital serves both individual and business clients — so the rebranding direction maintained a corporate, professional identity.

| | |
|---|---|
| **Data** | ~3,900 loan records · total portfolio 69.5B MNT |
| **Scope** | Customer segmentation · NPL classification · geographic analysis |
| **Key finding** | Bayanzürkh district (BZD) — 25.5% of portfolio, lowest NPL rate (6%), only 0.8% penetration of the 31–40 age group — identified as primary campaign target |
| **Website contribution** | Identified missing CSR section · proposed structure and copy · adopted in live site |

---

## The Data

**Dataset: ~3,900 loan records · total portfolio 69.5B MNT**
Variables: age · gender · marital status · monthly income · profession · location · loan type · loan amount · loan classification · overdue days

**Loan Portfolio Breakdown**

| Loan Type | Amount |
|---|---|
| Car loan (leasing) | 44.4B MNT (64%) |
| Business loan | 14.7B MNT (21%) |
| Vehicle collateralized | 4.5B MNT |
| Real estate collateralized | 2.3B MNT |
| Consumer loan | 1.5B MNT |
| Express loan | 1.2B MNT |

**Who the Customers Are**

| | |
|---|---|
| Gender | 60% male · 40% female |
| Largest age group | 31–40 (41% of male customers) |
| Top professions | Service (16%) · trade (12%) · transportation (8%) · construction (8%) |

---

## Key Findings

**NPL by Gender**
Men account for 58% of non-performing loans, consistent with their 60% customer share. Women's NPL share rises to 42% — higher than their 37–39% share of performing loans — indicating slightly elevated default risk relative to their proportion.

**NPL by Age**
Age had little effect on default likelihood. Repayment behaviour was broadly consistent across all age groups.

**NPL by Profession**
Trade sector borrowers had the highest NPL rate at 20%, followed by the service sector at 15%.

<img width="648" height="364" alt="Screenshot 2026-06-26 at 4 14 38 PM" src="https://github.com/user-attachments/assets/b0ff68f8-3474-4fa8-847b-115d65a9fd4d" />

> *Loan classification by customer gender, age and profession — original internal report*

**Geographic Analysis**
Nationally, Dundgov and Tuv province had the worst NPL rates. Within Ulaanbaatar, Baganuur and Bagakhangai had the smallest portfolio shares (1% and 0.1%) but the highest NPL rates — caused by a small number of high-value defaulted loans in those districts.

The opposite was true for Bayanzürkh (BZD) and Khan-Uul — the two largest district portfolios at 25.5% and 17.4% — with the lowest NPL rates in the city.

<img width="648" height="364" alt="Screenshot 2026-06-26 at 4 14 42 PM" src="https://github.com/user-attachments/assets/91538924-1416-41ba-83e2-72fe4f22246d" />

> *Loan portfolio distribution and NPL rates by location — original internal report*

---

## Methodology

**Data Cleaning and Analysis**
Cleaned and analyzed ~3,900 loan records in Excel across demographics, profession, location, and loan classification using pivot tables and VLOOKUP. Segmented the portfolio by performing, special mention, and non-performing status to identify default patterns.

<img width="1064" height="802" alt="Screenshot 2026-06-26 at 4 13 23 PM" src="https://github.com/user-attachments/assets/f4c8102a-7c79-48dd-852a-3ad9441ee8dc" />

> *Full portfolio dashboard built in Excel — loan info, customer features, NPL classification, geographic distribution · total portfolio: 69.5B MNT · Date: 2024*

**NPL Calculation Methodology**
NPL rate was calculated as each district's non-performing loan amount divided by that district's total loan amount — not as a share of the overall portfolio. This normalization was necessary to compare loan quality fairly across districts of very different sizes. On a raw amount basis, Songinohairhan would appear the highest NPL district and BZD the third — but this reflects portfolio size, not loan quality. Normalizing by district gives a more accurate picture of where lending risk actually concentrates.

**Geographic Targeting**
Mapped NPL rates across all Ulaanbaatar districts and national provinces. Cross-referenced portfolio share, NPL rate, and district population data to identify BZD as the strongest acquisition target. Population penetration was calculated manually using the 31–40 age group figure from the National Statistics Office of Mongolia — the core demographic for Omnicapital's lending products.

**Website Content Contribution**
Identified that the existing Omnicapital website was missing a CSR (Corporate Social Responsibility) section entirely. Proposed the page structure, wrote all copy, and built a layout reference to hand off to the design and development team. The work was submitted to the CEO as a view-only file.

---

## Results

The geographic analysis identified BZD as the primary acquisition target, supported by four converging data points:

- Largest portfolio share in Ulaanbaatar at **25.5%**
- Lowest NPL rate in the city at **6%**
- Only **0.8%** of the 31–40 age population were clients (600 customers out of 77,854 people)
- **41,481 registered business entities** — the highest concentration of any district in Ulaanbaatar (Source: [National Statistics Office of Mongolia, 2023](https://downloads.1212.mn/M6IyqwFjAQbTJ-yY-TfywuPdYcul7LNPUX7xX5f8.pdf))

The combination of low default risk, low market penetration, and the highest concentration of businesses in the city made BZD the strongest candidate for a targeted campaign covering both individual and business lending.

On the website side, the CSR section proposal was submitted to the CEO and has since been adopted in the live Omnicapital website. The structural approach and content positioning from the layout reference were reflected in the final design.

<img width="1710" height="1107" alt="Screenshot 2026-06-26 at 4 51 11 PM" src="https://github.com/user-attachments/assets/902c331f-9b5d-41dc-afe6-acb92367ca5e" />
> *Left: Layout reference submitted to the design team · Right: Live omnicapital.mn — structural approach and content positioning adopted*

> 🌐 [View Omnicapital website](https://www.omnicapital.mn)

---

## Tools

| Tool | |
|---|---|
| Microsoft Excel | Data cleaning · pivot tables · VLOOKUP · NPL segmentation · geographic analysis |
| PowerPoint | Findings report submitted to CEO |
| Figma | Website content structure and layout reference for design team |

---

## If I Did This Today

The analysis was done in Excel. With the tools I have now, the work would be faster, more precise, and reproducible.

SQL to query and join ~3,900 records across loan type, geography, and customer demographics instead of managing everything in spreadsheets. Power BI to build an interactive dashboard where anyone on the team could filter by district, loan classification, profession, or customer profile. Python with pandas to run proper statistical correlation between customer attributes and NPL rates. And automated reporting to monitor portfolio health and NPL trends over time rather than delivering a one-time snapshot.

---

## Related Project

**Moni Fintech App Analysis** — the consumer-facing side of the same engagement: UX audit, 380,000 customer records, acquisition funnel analysis, and customer segmentation that triggered the company-wide rebrand.

→ [View Moni project](../moni-fintech-app-analysis)

---

**Bulgan Damdindorj** · Vancouver, BC · MBA, University Canada West (2026)  
[LinkedIn](https://www.linkedin.com/in/bulgan-damdindorj-915451289/) · [GitHub](https://github.com/bulgandamdindorj)
