# E-commerce Conversion & User Behavior Analysis

## :red_circle: Project Overview
This project analyzes user behavior and conversion performance in an e-commerce dataset using SQL, Python, and statistical methods. The goal is to identify key drivers of conversion and evaluate whether factors such as user status, device, traffic source, and geography impact purchasing behavior.

---

## :red_circle: Tools & Technologies
- SQL (BigQuery) – data extraction and joins  
- Python (Pandas, NumPy) – data cleaning and analysis  
- Matplotlib / Seaborn – data visualization  
- SciPy – statistical testing (Chi-square)  

---

## :red_circle: Dataset
- ~350,000 session-level records  
- Time period: November 2020 – January 2021  
- Data includes:
  - User sessions  
  - Traffic sources  
  - Devices  
  - Geographic data  
  - Product and purchase information  

---

## :red_circle: Project Steps

### 1. Data Extraction
- Combined multiple tables using SQL joins in BigQuery  
- Loaded data into Python environment (Google Colab)

### 2. Data Cleaning & Preparation
- Converted data types (e.g., date formatting)  
- Analyzed missing values (up to 90% in some columns)  
- Decided to retain missing data to avoid losing behavioral information  

### 3. Exploratory Data Analysis
- Analyzed traffic trends and session behavior  
- Identified weekly seasonality in user activity  
- Evaluated user distribution (subscribed vs anonymous users)

### 4. Conversion Analysis
- Calculated conversion rate (~9.6%)  
- Compared conversion across:
  - User authorization status  
  - Traffic channels  
  - Devices  
  - Countries  

### 5. Statistical Analysis
- Applied Bayesian smoothing to correct bias in country-level conversion rates  
- Performed Chi-square test to evaluate statistical significance  

---

## :red_circle: Key Findings
- Clear weekly seasonality in website traffic  
- Only ~8% of users are subscribed (majority are anonymous)  
- Authorization status has minimal impact on conversion  
- Conversion rates are stable across channels and devices  
- No statistically significant differences across countries  
- Tablet shows slightly lower performance  

---

## :red_circle: Recommendations
- Align marketing campaigns with peak traffic periods  
- Focus on converting anonymous users into subscribers  
- Improve value proposition of subscription model  
- Optimize overall conversion funnel rather than specific channels/devices  
- Maintain unified strategy across regions  
- Investigate potential UX issues on tablet devices  

---

## 📊 Business Impact
Provided data-driven insights to improve conversion strategy, optimize marketing efforts, and support decision-making across user segments and channels.

---

## 🔗 Links
- GitHub Notebook: *(add your link here)*  
- Tableau Dashboard: *(add your link here)*  

- Conversion rate analysis  
- Statistical testing (Chi-square, Bayesian smoothing)  
- Data visualization and storytelling  
