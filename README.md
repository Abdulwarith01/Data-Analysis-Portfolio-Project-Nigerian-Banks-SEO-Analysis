# Data-Analysis-Portfolio-Project-Nigerian-Banks-SEO-Analysis

## Nigerian Banks SEO Analysis 🏦📊

**Type:** Competitive Intelligence

**Problem statement**  
This project evaluates the online visibility and search engine performance of selected Nigerian banks. The analysis focuses on keyword competition, search volume, and ranking position across Access Bank, Wembley Bank, ALAT by Wema, Fidelity Bank, First Bank, GTBank, Union Bank, Sterling Bank, Zenith Bank, and Stanbic IBTC.

**Data source & analysis process**
1. Keyword discovery: Ubersuggest for initial keyword ideas.  
2. SERP scraping: SerpAPI called from Python to collect ranking positions and URLs.  
3. Volume & click estimates: Google Key Finder (search volume) and Ubersuggest-derived click estimates.  
4. Cleaning: removed duplicates, normalized bank name variants, trimmed whitespace, standardized categories (Digital Banking, Cards, Loans & Credit, Transfers & Payments, Accounts & Deposits, Other).  
5. Transformation: created ranking tiers (Page 1 Top 3, Page 1 Pos 4–10, Page 2, Page 3), computed visibility quality % per bank (weighted by position; higher weight for top positions), estimated monthly clicks by combining visibility share with search volume and measures in Power BI.  
6. Bank financial data was sourced from [Nairametrics.com](http://nairametrics.com/).

Below is a copy of the engineered dataset.

> *PS: Some calculated metrics used in the analysis are not included in the CSV export.*

Files
- SEO_Dataset.csv
- seo_dashboard.pdf
- images/dashboard1.jpg
- images/dashboard2.jpg
- images/dashboard3.jpg

**Tools & technologies**
- Python
- Excel
- Web analytics (SerpAPI)
- Power BI

**Key findings**
1. Top-level metrics: 36 distinct tracked keywords across banks; total monthly searches ~318K; ~16.5k unclaimed keywords (opportunity).  
2. Page 1 leadership: First Bank leads with 24 Page 1 keywords and highest visibility quality (92.31%).  
3. Visibility distribution: Some banks (Access Bank) rank many keywords but with lower Page 1 share and lower visibility quality. GTBank, Zenith, and UBA concentrate rankings into higher quality positions.  
4. Strategic quadrant (Quality vs Quantity): First Bank in high-quality, high-quantity quadrant; GTBank and Zenith are high-quality. Access Bank shows high quantity but lower quality.  
5. SEO efficiency: First Bank highest efficiency score, followed by GTBank, UBA, Zenith. Lower performers: Wema Bank, Union Bank, Stanbic IBTC.  
6. Revenue association: Banks with higher visibility are often among higher-profit banks—correlation, not causation.

**Visualizations**
See the dashboard PDF and images in this repo:
- ./seo_dashboard.pdf  
- ./images/dashboard1.jpg  
- ./images/dashboard2.jpg  
- ./images/dashboard3.jpg

---
