Shark Tank India – Startup Investment Analysis
Project Overview
This project analyzes Shark Tank India startup and investment data to identify investment trends, investor behavior, deal outcomes, and founder/startup success patterns.
The dataset covers Shark Tank India Seasons 1–5 and contains startup, founder/pitch, financial, deal, and shark-specific investment information.
Objective
The main objectives of this project are to:
- Analyze startup investment trends.
- Identify industries receiving higher investment.
- Compare investment behavior among sharks.
- Analyze received and accepted offers.
- Study deal amounts, equity, and debt.
- Identify patterns associated with successful pitches.
- Build visual insights that can support business decisions.
Tools Used
- Python – data cleaning, exploratory analysis, calculations, and visualizations.
- Jupyter Notebook – documentation and execution of the Python analysis.
- Tableau – interactive dashboard and visual storytelling.
- Excel – optional supporting data inspection/analysis.
Dataset
The dataset contains information from Shark Tank India Seasons 1–5.
Important fields include:
- Season Number
- Startup Name
- Industry
- Business Description
- Started in
- Number of Presenters
- Pitchers Average Age
- Pitchers City / State
- Yearly Revenue
- Monthly Sales
- Gross Margin
- Net Margin
- EBITDA
- Cash Burn
- SKUs
- Has Patents
- Bootstrapped
- Original Ask Amount
- Original Offered Equity
- Valuation Requested
- Received Offer
- Accepted Offer
- Total Deal Amount
- Total Deal Equity
- Total Deal Debt
- Deal Valuation
- Number of sharks in deal
- Individual shark investment amounts, equity, and debt
Analysis Performed
1. Deal and Offer Analysis
The Python notebook analyzes:
- Startups receiving investment offers.
- Accepted and rejected offers.
- Deal amounts.
- Deal equity.
- Deal debt.
- Deal valuation.
- Other deal characteristics.
2. Investment Analysis
The project analyzes:
- Highest investment amounts.
- Total investment amounts.
- Investment equity.
- Debt-based investment.
- Royalty and advisory-share deals where applicable.
3. Shark-wise Investment Analysis
The analysis compares shark investment activity using the available investment fields for:
- Namita
- Vineeta
- Anupam
- Aman
- Peyush
- Ritesh
- Amit
- Guest investors
The comparison considers investment amount, equity, debt, and number of companies invested in where supported by the dataset.
4. Industry-wise Investment Trends
The project studies investment across startup industries to identify:
- Industries attracting higher investment.
- Industries receiving more deals.
- Differences in investor participation across industries.
5. Founder / Startup Success Patterns
The analysis considers variables such as:
- Original ask amount.
- Original offered equity.
- Received offer.
- Accepted offer.
- Revenue.
- Sales.
- Profitability-related fields.
- Cash burn.
- Patents.
- Bootstrapping.
- Founder/presenter characteristics.
The goal is to identify patterns associated with successful pitches rather than treating any single variable as a guaranteed cause of success.
Tableau Dashboard
The Tableau dashboard is designed to provide an interactive view of:
- Total pitches.
- Deals received.
- Total investment.
- Average deal amount.
- Investment by industry.
- Investment by shark.
- Deal success.
- Season-wise investment trends.
- Founder ask amount vs. offered equity.
Suggested Filters
- Season
- Industry
- Shark / Investor
- Deal status
Project Deliverables
The completed project contains / is intended to contain:
Task-15-Shark-Tank-Investment-Analysis/
│
├── README.md
│
├── data/
│   └── shark_tank_india.csv
│
├── python/
│   └── Shark Tank India Analysis.ipynb
│
├── tableau/
│   └── Shark_Tank_India_Dashboard.twbx
│
├── reports/
│   ├── Shark_Tank_Industry_Investor_Trends.pdf
│   └── Founder_Success_Pattern.pdf
│
└── screenshots/
    ├── python_analysis.png
    ├── shark_investment_analysis.png
    ├── investment_analysis.png
    ├── tableau_dashboard.png
    ├── industry_investment.png
    ├── shark_investment.png
    ├── founder_success_pattern.png
    └── season_investment_trend.png
Key Insights
The final insights should be taken directly from the executed Python analysis and Tableau dashboard. Important areas to report include:
1. Which industries attracted the most investment.
2. Which sharks invested the most overall.
3. Which sharks invested in the highest number of startups.
4. How investment changed across seasons.
5. The proportion of startups receiving offers.
6. The proportion of offers that were accepted.
7. Whether ask amount and offered equity show visible patterns in deal success.
8. Whether financial and startup characteristics appear associated with receiving an offer.
How to Run the Python Analysis
1. Install Python and Jupyter Notebook/JupyterLab.
2. Place the Shark Tank India dataset in the project directory.
3. Open Shark Tank India Analysis.ipynb.
4. Make sure the dataset path used in the notebook points to the correct CSV file.
5. Run the notebook from top to bottom.
6. Review the generated tables and visualizations.
Tableau Workflow
1. Open Tableau.
2. Connect to the Shark Tank India CSV dataset.
3. Create the required calculated fields/measures if necessary.
4. Build the individual worksheets.
5. Combine the worksheets into an interactive dashboard.
6. Add filters for Season, Industry, Shark, and Deal Status.
7. Save the workbook as a .twbx file.
Conclusion
This project provides a structured analysis of Shark Tank India startup pitches and investment activity. It combines Python-based exploratory analysis with Tableau-based interactive visualization to understand investment trends, investor behavior, industry patterns, and founder/startup success indicators.
