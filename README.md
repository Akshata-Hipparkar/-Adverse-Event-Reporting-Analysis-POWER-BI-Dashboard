## 📊 Power BI Project: CFSAN Adverse Event Reporting System (CAERS) Analysis  

### 🧩 Overview  
This Power BI project explores the CFSAN Adverse Event Reporting System (CAERS) — a database maintained by the U.S. FDA to record adverse events and product complaints related to:  
- 🧴 Cosmetics  
- 💊 Dietary Supplements  
- 🍔 Foods  

The analysis spans 2004 to mid-2017, uncovering trends, demographic patterns, and potential product safety signals, enabling data-driven decisions in public health and product safety.  

 <img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/f6feae0f-70eb-4e44-8880-4d46139cbf04" />


---

### 📂 Data Source  
**Dataset:** CAERS Adverse Event Reports (2004–2017)  
**Provider:** U.S. FDA  

**Key Fields:**  
- 📑 Report numbers & product details  
- 🏷️ Industry codes & brand info  
- 👥 Patient demographics (age, gender)  
- ⚠️ Adverse outcomes & standardized MedDRA-coded symptoms  

---

### 🎯 Objectives  
- Identify patterns and trends in adverse events across products and demographics.  
- Reveal distributions by product role, industry, and outcome severity.  
- Support regulatory and public health decisions with actionable insights.  

---

### ⚙️ Power BI Workflow  

#### 1. 🧹 Data Import & Cleaning  
- Handled missing values and standardized data formats.  
- Converted date fields to consistent formats.  
- Categorized age, gender, and outcomes for uniform analysis.  

#### 2. 🔍 Preliminary Analysis  
- Validated record consistency and uniqueness.  
- Classified product roles (Suspect vs. Concomitant).  
- Implemented foundational filters for key attributes.  

#### 3. 🧠 Feature Engineering  
- Grouped records by product, outcome, age, gender, and time.  
- Created new fields:  
  - Age Groups  
  - Outcome Categories  
- Built DAX measures for deeper and predictive insights.  

---

### 🖥️ Dashboard Highlights  

- **📈 Industry-wise Risk Analysis:**  
  Displays which FDA-regulated product categories report the most adverse events.  

- **👩‍🦳 Demographic Trends:**  
  Visualizes severity and frequency of outcomes by age and gender.  

- **⚕️ Outcome & Symptom Analysis:**  
  Highlights top-reported symptoms and maps serious outcomes with severity scores.  

- **🤖 Predictive Analytics:**  
  Built with DAX-based models estimating risk per product, demographic, and symptom type.  

- **📉 Time Series:**  
  Captures spikes, trends, and potential seasonality in report volumes.  

- **🔗 Correlation Insights:**  
  Reveals connections among symptoms, age, industry, and serious outcomes for better regulatory focus.  

---

### 💡 Key Insights  

| Insight Area | Findings |
|---------------|-----------|
| Top Reporting Categories | Dietary supplements and cosmetics lead in adverse event reports. |
| Age & Severity | Older adults show higher severity and frequency of adverse events. |
| Common Symptoms | GI symptoms dominate report frequency; cardiovascular and neurological events are linked to severe outcomes. |
| Predictive Results | Identified top-risk products, helping agencies anticipate and act proactively. |

---

### 🚀 How to Use  
1. Import the CAERS dataset into Power BI Desktop.  
2. Explore interactive dashboards using filters for:  
   - Age  
   - Gender  
   - Product  
   - Industry  
   - Symptom  
3. Review embedded documentation and DAX formulas for customization and exploration.  

---

### 🧾 License  
**Usage:** Academic and non-commercial purposes only.  
**Source:** [FDA CAERS Database](https://www.fda.gov/food/compliance-enforcement-food/cfsan-adverse-event-reporting-system-caers)  

---

### 🌟 Project Snapshot  
🚧 Built with: Power BI Desktop  
📅 Data Range: 2004 – mid-2017  
📊 Goal: Enhance public health surveillance through data-driven visualization  
