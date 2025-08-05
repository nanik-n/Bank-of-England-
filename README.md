# Bank-of-England-
About In this project, I supported the Bank of England in analysing sentiment across policy speeches from 2019–2022 using text analytics. By applying FinBERT and exploring tone shifts by speaker and event, I translated central bank communication trends into insights that inform economic narrative and policy direction.
📊 LSE Data Analytics Employer Project – Bank of England - 90% Grade
🧾 Executive Summary
This employer project was completed as part of the LSE Data Analytics Diploma, in collaboration with the Bank of England.

Our five-member team analysed 240 BoE speeches from 2019–2022 to understand how speech sentiment reflected and responded to economic events, interest rate changes, and macroeconomic indicators.


🛠 Tools Used
Python: data cleaning, NLP, statistical testing
FinBERT: sentiment analysis for financial text
Matplotlib / Seaborn: data visualisation
Pandas / NumPy / SciPy: data manipulation, statistical functions
Selenium + BeautifulSoup: web scraping report dates
Excel: initial data exploration
📌 Business Problem
The Bank of England uses public speeches to shape market expectations and communicate monetary policy. They wanted to understand:
How speech tone shifts across macroeconomic shocks
Whether sentiment diverges by speaker role (Governor vs Staff)
If speech tone influences market behaviour (e.g. GBP-EUR, gilt yields)
How sentiment aligns with indicators like inflation and GDP

🧪 Analytical Approach
Data filtering: 240 UK speeches from 2019–2022
Model testing: Compared FinBERT, VADER, TextBlob, and LM
Topic labelling: Categorised speeches into Growth, Inflation, Labour, Financial Markets
Event overlays: Annotated timeline with COVID-19, Brexit, Ukraine war
Statistical analysis: Chi-square tests, paired t-tests, cross-correlation, Granger causality
Sentiment trend visualisation: Line charts, heatmaps, boxplots

📈 Key Insights
BoE speeches maintained a neutral tone—even during global crises
Governor speeches were more volatile and market-aligned than staff
Growth sentiment had the strongest alignment with overall tone
Weak to no correlation between speech sentiment and inflation or internal BoE events
Granger causality found between staff sentiment and GBP-EUR movement
Staff sentiment lagged behind GDP changes by 5 months

🧭 Recommendations
Recommendation	Description	Priority
Track sentiment over time	Integrate FinBERT scores into internal dashboards to monitor tone shifts	High
Contextualise by role/topic	Build reference tone profiles for Governor and Staff by topic to flag outliers	Medium
Scenario-based planning	Use historical tone patterns to guide future crisis communication	Low

