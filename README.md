# Nigerian Banks SEO Analysis 🏦📊  
**Type:** Competitive Intelligence

## Overview  
This project evaluates the online visibility and search engine performance of selected Nigerian banks. It analyzes keyword competition, search demand, and SERP rankings to assess relative SEO strength and opportunity gaps.

**Banks covered:**  
Access Bank, Wema Bank (ALAT), Fidelity Bank, First Bank, GTBank, Union Bank, Sterling Bank, Zenith Bank, Stanbic IBTC.

---

## Problem Statement  
Nigerian banks compete aggressively for digital visibility, yet SEO performance varies widely. This analysis quantifies visibility quality, ranking depth, and missed keyword opportunities to identify which banks convert search demand into visibility most efficiently.

---

## Data Sources  
- **Keyword discovery:** Ubersuggest  
- **SERP rankings:** SerpAPI (queried via Python)  
- **Search volume:** Google Key Finder  
- **Click estimates:** Ubersuggest-derived CTR assumptions  
- **Financial data:** Nairametrics  

---

## Methodology  
1. Collected keyword-level SERP rankings and URLs per bank.  
2. Cleaned data by:
   - Removing duplicates  
   - Normalizing bank name variants  
   - Trimming whitespace  
   - Standardizing keyword categories  
3. Categorized keywords into:
   - Digital Banking  
   - Cards  
   - Loans & Credit  
   - Transfers & Payments  
   - Accounts & Deposits  
   - Other  
4. Engineered ranking tiers:
   - Page 1 (Top 3)  
   - Page 1 (Positions 4–10)  
   - Page 2  
   - Page 3  
5. Computed visibility and performance metrics (see Appendix).  
6. Final aggregation and visualization in Power BI.

**Note:** Some derived metrics used in Power BI are not included in the CSV export.

---

## Repository Structure
