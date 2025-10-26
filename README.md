# -Adverse-Event-Reporting-Analysis-POWER-BI-Dashboard
**Project Overview**
This Power BI project analyzes the CFSAN Adverse Event Reporting System (CAERS) database, a critical tool used by the FDA to track adverse event and product complaint reports across foods, dietary supplements, and cosmetics from 2004 to mid-2017. The goal is to discover trends, demographic impacts, product safety signals, and risk factors, empowering stakeholders with actionable public health insights.​

**Data Source**
Dataset: CAERS Adverse Event Reports (2004–2017)

Fields: Report numbers, product and brand info, industry codes, patient demographics, adverse outcomes, and standardized MedDRA-coded symptoms.​

**Objectives**
Identify patterns and trends in adverse events across products and demographics.

Reveal distribution by product role, industry, and outcome severity.

Inform safety surveillance, regulatory decision-making, and public health responses.​

**Power BI Workflow**
Data Import & Cleaning: Handled missing values, standardized text and numerical fields, converted date formats, and categorized age/gender and outcomes.

Preliminary Analysis: Assessed record consistency/uniqueness, role categorization (Suspect vs. Concomitant products), and foundational filtering.​

Feature Engineering: Grouped by product, outcome, age, gender, and time. Created new fields (age groups, outcome categories) and DAX measures for advanced insights.​

**Dashboard Features**
Industry-wise Risk: Visualizes which FDA-regulated product categories (cosmetics, dietary supplements, foods) have the most reported adverse events.

Age & Gender Trends: Analyzes outcome severity and frequency by demographic groups.

Outcome & Symptom Analysis: Maps serious outcomes and highlights top-reported symptoms, with severity metrics.

Predictive Analytics: DAX-based models estimate risk per product, demographic, and symptom category.

Time Series: Investigates trends, spikes, and seasonality in report volumes.

Correlations & Insights: Reveals links between symptoms, age, industry, and severe outcomes for targeted regulatory focus.​

**Key Insights**
Most reports are linked to dietary supplements and cosmetic products.

Higher adverse event risk and greater severity are seen in older adults and certain product categories.

GI symptoms are most frequent; cardiovascular and neurological events drive severe outcomes.

Predictive metrics highlight top-risk products, aiding proactive FDA/regulatory monitoring.​


**How to Use**
Import the dataset into Power BI Desktop.

Access interactive dashboards: Apply slicers for age, gender, product, industry, and symptom to explore risk factors and outcomes.

Review documentation and DAX formulas embedded in the report for further customization.

**License**
For academic and non-commercial use only. Source: FDA CAERS Database.
