# Where Salesforce Should Grow: Construction SMBs in South East Queensland

## About this project

This is a self-directed portfolio project based on a Macquarie University Business Analytics Project brief (BUSA8031, Session 2 2026). The brief casts Salesforce Australia as the client. Salesforce wants to grow among small and medium businesses (SMBs) and needs a data-driven way to decide **which markets to target and where to focus marketing effort**.

The project combines several ABS datasets into one interactive Tableau dashboard. Users can explore any state and industry, adjust the scoring and revenue assumptions, and see how the recommendations change.

**Tools:** Tableau Public · Excel (data cleaning and preparation)
**Techniques:** data integration across multiple sources · composite index (weighted, min–max normalised) · K-Means clustering · scenario-based revenue estimation · interactive dashboard design

🔗 **Live dashboard:** [Tableau Dashboard Link](https://public.tableau.com/app/profile/reynald.rodriguez/viz/Salesforce_SMB_Market_Targeting/StateandIndustry)


<img width="1591" height="890" alt="image" src="https://github.com/user-attachments/assets/ec2548e1-1d9c-4e2f-889f-601c820ee9bf" />


<img width="1591" height="892" alt="image" src="https://github.com/user-attachments/assets/d0a0c587-a2b2-4972-8454-446232aa4a6c" />


<img width="1587" height="796" alt="image" src="https://github.com/user-attachments/assets/02ae260b-7b58-4b67-b589-d153373324dd" />


## Executive summary

Salesforce's strongest small business opportunity lies with trades and specialist construction businesses in Logan, the Gold Coast and Moreton Bay. Queensland offers the largest growing small business market in Australia. Construction is the only one of Queensland's five highest-sales industries still adding businesses, and while most construction businesses use cloud tools, few report using a CRM. These three neighbouring areas hold a third of Queensland's construction opportunity, worth an estimated $1 million a year at a cautious 5% take-up.

This analysis set out to identify:
- the state with the best mix of market size and growth
- the industry with the strongest need for Salesforce
- how ready that industry is to adopt it
- which businesses within the industry fit best
- where to start, and what the opportunity is worth

## Key findings

### 1. Queensland: the largest small business market that's still growing

Australia's two biggest small business markets are shrinking. **New South Wales and Victoria both lost businesses** between 2023 and 2025. Western Australia and the Northern Territory grew fastest (about +2.7%), but from much smaller bases: about 92,000 businesses in WA and only 6,000 in the NT.

**Queensland sits between the two.** With about **197,000 small businesses**, twice WA's number, it still added about **1,900** over the period. WA is growing faster, but Queensland gives Salesforce twice the number of potential customers in a market that's still expanding.


<img width="1591" height="477" alt="image" src="https://github.com/user-attachments/assets/1e5e4ffd-81a9-4739-aec7-66b7a965e7e0" />


The state also has a history of supporting small businesses to go digital. Past programs offered matched funding of up to $10,000 for hardware, software and digital services (Small Business Digital Grants), and grants of up to $15,000 for business planning, specialised software and IT support (Business Boost). No program covering CRM software was open at the time of analysis, but future rounds could help small businesses afford Salesforce.

### 2. Construction: the only major industry still expanding

Among the five industries selected for comparison, Construction has the largest employing SMB population in Queensland, with approximately 38,000 businesses in June 2025. It was also the only industry within this comparison to record positive net business growth between June 2023 and June 2025, increasing by approximately 1.6%.

Construction is also the **most people-heavy** of the five: **wages make up 16.5% of its sales**, compared with 6–13% for the others, whose costs go mostly on stock, materials and equipment. That matters because Salesforce's value lies in saving staff time on tracking customers, preparing quotes, scheduling jobs and following up. The more an industry spends on its people, the more that saved time is worth.

Health Care and Professional Services grew faster, but they generate far lower sales. **Construction offers the strongest combination of market size, sales, growth and need for Salesforce.**


<img width="1587" height="787" alt="image" src="https://github.com/user-attachments/assets/e19ef032-c263-4e3f-9dcb-338002866994" />


### 3. Digitally ready, but largely without a CRM

ABS data shows that approximately 74% of construction businesses use cloud technology, while only 10% report using CRM systems. This suggests that CRM adoption is considerably less widespread than general cloud technology adoption within the industry. However, the data does not identify how businesses without CRM systems currently manage customer relationships. The adoption gap therefore presents an opportunity for further investigation rather than confirmed unmet demand.

For these businesses, moving to Salesforce is a small step, not a leap. Very few use more advanced tools such as AI (6%) or data analytics (3%), so the industry is early in its digital journey. **The natural entry point is Salesforce's basic Starter plan**, with advanced features introduced later.


<img width="1582" height="375" alt="image" src="https://github.com/user-attachments/assets/a62653cc-cc33-46fd-b96e-9d78f552fef9" />


### 4. Trades and specialist contractors: the best-fit businesses

Within construction, trades and specialist contractors (electricians, plumbers, carpenters and similar) are grouped by the ABS as "Construction Services".

Construction Services stands out among the three construction subdivisions, recording the highest aggregate sales, wages expenditure and profit margin in the selected ABS data. These indicators suggest that the subdivision warrants further investigation as a potential Salesforce customer segment. However, industry-level financial performance does not directly establish individual businesses' willingness or ability to pay for CRM solutions.


<img width="1591" height="405" alt="image" src="https://github.com/user-attachments/assets/f72dcff9-6de4-4e47-b116-de805eb7b94c" />


### 5. Logan, Gold Coast and Moreton Bay: where to start

Each eligible Queensland Local Government Area (LGA) was assigned a Market Opportunity Index score out of 100, based on three factors: the number of employing construction SMBs, their net change between 2023 and 2025, and construction's share of the LGA's total employing SMB population. Areas with fewer than 100 employing construction SMBs were excluded to reduce the influence of very small markets.

LGA Market Opportunity Index for Queensland construction, with the score weights panel open SMB Insights page with QLD and Construction selected. The "What matters most?" panel on the right controls the score weights.


<img width="1597" height="467" alt="image" src="https://github.com/user-attachments/assets/a73361cc-0e4c-483c-807a-c9c10188f8b6" />


*SMB Insights page with QLD and Construction selected. The "What matters most?" panel on the right controls the score weights.*

The three top-ranked areas each lead for a different reason:

* Logan (74.9): a net increase of 178 employing construction businesses between June 2023 and June 2025, the largest absolute net growth among the LGAs compared
* Gold Coast (59.2): the second-largest market (6,165 businesses), and still growing
* Moreton Bay (55.7): a strong balance of size (3,638 businesses) and growth

**Adjustable weights.** By default, the three factors count equally. The "What matters most?" panel lets users change how much each one counts, from 1 (least important) to 5 (most important). Raising Market Size favours large established markets; raising Business Growth favours fast-growing ones. Salesforce can match the ranking to its own priorities and see whether the recommended areas still hold.

K-Means clustering provides an additional perspective on the geographic distribution of Queensland's construction SMBs. The analysis identifies five larger markets—Brisbane, Gold Coast, Moreton Bay, Sunshine Coast and Logan—distinguishing them from 28 smaller LGAs. Three of these larger markets also rank highly under the Market Opportunity Index, providing supporting context for their prioritisation. However, clustering does not independently establish which LGAs offer the strongest potential for Salesforce customer acquisition.


<img width="787" height="310" alt="image" src="https://github.com/user-attachments/assets/a0667c85-a3f8-4779-8023-f6d1c509d7b2" />


**Brisbane is the notable exception.** It has the most construction businesses in Queensland (6,904), but their number fell over the period, so it ranks outside the top 10. New construction businesses are forming in the suburbs and regions around Brisbane, not in the city. Being big doesn't automatically make a market an opportunity.

Livingstone, near Rockhampton, ranks fourth despite having only 435 construction businesses. It's a fast-rising regional market worth watching.


<img width="790" height="312" alt="image" src="https://github.com/user-attachments/assets/bc442adc-99c4-4d10-a395-8393a811257a" />


### 6. A third of the opportunity in three neighbouring areas

Under an illustrative 5% customer adoption scenario, Queensland's approximately 38,000 employing construction SMBs would represent around 1,900 paying customers. Based on the assumed Salesforce product mix and number of licences per business, this produces approximately AU$3.15 million in annualised subscription revenue.

This estimate is scenario-based rather than a sales forecast. The 5% adoption rate and licence allocations are modelling assumptions, and the calculation excludes customer acquisition costs, churn and other factors that would affect realised revenue and profitability.

Selecting only Logan, the Gold Coast and Moreton Bay on the dashboard shows that these three LGAs hold 12,750 employing construction SMBs, giving about 640 customers and AU$1.03 million a year under the same assumptions, roughly a third of the Queensland total.


<img width="1592" height="687" alt="image" src="https://github.com/user-attachments/assets/f2af4c97-9b15-481d-abef-c1b2bd7c19ca" />


Because the three areas sit side by side in South East Queensland, one regional team or campaign can reach a third of the state's opportunity.

The estimate assumes the Starter plan (AU$35 per user per month) for businesses with 1–19 staff and the Pro plan (AU$140) for businesses with 20–199, with 2, 4 or 10 users depending on size. These are list prices, and every assumption can be adjusted on the dashboard.
## Recommendations

1. **Focus on trades and specialist contractors**, the construction businesses with the most to gain and the means to pay.
2. **Launch in Logan, the Gold Coast and Moreton Bay**, then expand to the Sunshine Coast and regional centres such as Townsville and Livingstone.
3. **Lead with the Starter plan** for customer tracking, quotes and follow-ups, and introduce the Pro plan (quoting and forecasting) to larger firms.
4. **Use online campaigns**, since most of these businesses already work with cloud tools.
5. **Monitor Queensland's small business digital grants** and position Salesforce as an eligible purchase when new rounds open.

## Dashboard overview

The Tableau workbook has three pages, linked by shared State and Industry filters:

| Page | What it shows |
|---|---|
| **State and Industry** | SMB growth map, state scale-vs-growth scatter, industry SMB growth, industry sales, wages-to-sales ratio |
| **Technology Adoption** | Industry adoption of cloud, CRM, AI and data analytics (national); sub-industry sales, wages-to-sales ratio and profit margin |
| **SMB Insights** | Revenue KPIs, LGA Market Opportunity Index (ranked chart and map), K-Means LGA clusters, SMB counts by LGA |

**Interactive features**
- State, Industry and LGA filters (works for any state and industry, not just the one recommended here)
- **Score weight sliders**: change how much market size, business growth and industry share count in the Market Opportunity Index
- **Revenue assumption sliders**: adoption rate, users per business by size band, and plan prices
- Minimum-business threshold and Top N controls
- Click-to-highlight between the ranked chart, map and cluster scatter

## Methodology

**Target population.** SMBs are defined as **employing businesses with 1–199 employees**. Non-employing businesses (sole traders and passive entities) and businesses with 200+ employees (enterprise accounts) are excluded.

**Market Opportunity Index**
1. Three indicators per LGA: market size (SMB count, 2025), net business growth (change in employing SMB count between June 2023 and June 2025) and industry share (industry SMBs ÷ all SMBs in the LGA).
2. Each indicator is rescaled to 0–1 using min–max normalisation within the current selection.
3. The final score is a weighted average × 100, with user-adjustable weights (equal by default).
4. LGAs below a minimum business threshold (default 100) are excluded to avoid small-base distortion.

Growth % was deliberately left out of the index, because it double-counts growth and inflates very small LGAs.

**K-Means clustering (Tableau)**
- Variables: SMB 2025, SMB Growth, SMB Growth % (normalised), at LGA level
- Result for QLD construction: 2 clusters, 33 LGAs, between-group sum of squares = 40.7% of the total
- Used to **confirm market tiers**, not to rank LGAs

**Revenue estimate**

```
Revenue = Adoption rate × 12 × [ (1–4 staff SMBs × users × Starter price)
                               + (5–19 staff SMBs × users × Starter price)
                               + (20–199 staff SMBs × users × Pro price) ]
```

**Data preparation (Excel)**
- Unit conversions ($m → $, '000 employees → people) applied in derived columns, with the raw values kept
- Industry names aligned across datasets (e.g. "Health care and social assistance (private)" → "Health Care and Social Assistance")
- Catch-all areas excluded ("Unincorporated…", "No usual address", external territories)

## Data sources

### Australian Bureau of Statistics (ABS)

| Dataset | Reference period used | Used for |
|---|---|---|
| [Counts of Australian Businesses, including Entries and Exits (CABEE)](https://www.abs.gov.au/statistics/economy/business-indicators/counts-australian-businesses-including-entries-and-exits/latest-release) | June 2023 and June 2025 | SMB counts and growth by state, industry, LGA and employment size band |
| [Australian Industry](https://www.abs.gov.au/AUSSTATS/abs@.nsf/MF/8155.0) | June 2023 - June 2025 | Sales and service income, wages, employment and profit margin by industry and sub-industry |
| [Characteristics of Australian Business](https://www.abs.gov.au/statistics/industry/technology-and-innovation/characteristics-australian-business/latest-release) | 2024–25 financial year | Technology adoption (cloud, CRM, AI, data analytics) by industry |

*Source: Australian Bureau of Statistics. ABS data is used under the [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/). Figures have been filtered, combined and transformed for this analysis (see Methodology); any errors in interpretation are the author's own.*

### Other sources

| Source | Used for |
|---|---|
| [Salesforce Australia: Small Business pricing](https://salesforce.com/au/small-business/pricing) | Starter (AU$35) and Pro (AU$140) list prices per user per month, accessed October 2026 |
| [Business Queensland: Business Growth Fund](https://www.business.qld.gov.au/running-business/support-services/financial/grants/growth-fund) and [Business Boost](https://www.business.qld.gov.au/businessboost) | Queensland small business grant context |


## Limitations

- Technology adoption and sub-industry figures are **national**; Queensland's construction businesses are assumed to be similar.
- Sub-industry sales are **totals across 2023–25**, not a single year.
- Market Opportunity Index scores **compare areas** within the current selection; they don't predict sales.
- Revenue figures are **estimates** based on adjustable assumptions and list prices (no discounts or add-ons).
- K-Means with two clusters mainly separates **large markets from small ones**; the Market Opportunity Index decides which large markets to prioritise.
- **No CRM-eligible grant was open** in Queensland at the time of analysis.
- All figures come from **public, aggregated ABS data**; no individual business is identified.

## Author

**Reynald Rodriguez**, Master of Business Analytics, Macquarie University

[LinkedIn](https://www.linkedin.com/in/reynald-rodriguez-8b1574126/)
