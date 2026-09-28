# Ecommerce-Revenue-Intelligence-Agentic-Ai
Agentic AI-powered e-commerce revenue intelligence dashboard built with Power BI, DAX, Python, Ollama, and APIs to analyze revenue, customers, products, markets, and detect revenue anomalies for data-driven business decisions.
# 🚀 E-Commerce Revenue Intelligence | Agentic AI + Power BI

An end-to-end **E-Commerce Revenue Intelligence project** designed to transform raw transaction data into actionable business insights using **Power BI, DAX, Python, Agentic AI, Ollama and APIs**.

The project focuses on identifying revenue drivers, customer and product performance, market concentration and unusual revenue patterns.

---

## 🎯 Business Problems

The project was developed to address five key business problems:

### 1. Revenue Visibility
- Sales performance was difficult to monitor consistently.
- Revenue trends across different periods were not clearly visible.
- Important revenue KPIs required consolidated reporting.
- Identifying changes in performance required manual analysis.
- Revenue drivers were difficult to compare.
- This limited fast, data-driven decision-making.

### 2. Market Dependency
- Revenue was highly concentrated in a particular market.
- Heavy dependency on one market creates concentration risk.
- Country-level performance was not immediately visible.
- Underperforming markets could be overlooked.
- Market contribution required deeper analysis.
- Better visibility was needed for diversification decisions.

### 3. Product Performance
- Products contributed differently to overall revenue.
- Top revenue-generating products were difficult to identify.
- Low-performing products could remain hidden.
- Product-level revenue contribution required deeper analysis.
- Product performance needed to be compared systematically.
- This supports better product and sales prioritization.

### 4. Customer Concentration
- A small group of customers contributed significantly to revenue.
- High-value customer contribution required better visibility.
- Customer purchasing patterns needed deeper analysis.
- Dependence on key customers can create concentration risk.
- Repeat customer behaviour needed monitoring.
- Identifying valuable customers supports retention strategies.

### 5. Revenue Anomalies
- Unusual revenue movements could be difficult to identify manually.
- Large revenue spikes or drops could remain hidden.
- Traditional reporting does not always highlight abnormal behaviour.
- Potential business events required automated detection.
- Anomaly severity needed to be quantified.
- Z-score based analysis was used to identify unusual revenue patterns.

---

## 💡 Project Objective

The objective was to build a centralized revenue intelligence solution that helps answer:

- What is driving revenue?
- Which markets contribute the most?
- Which products generate the highest revenue?
- Which customers are most valuable?
- Are there unusual revenue movements?
- Where should the business investigate further?

---

## 📊 Key Metrics

| Metric | Value |
|---|---:|
| Total Revenue | 9.75M |
| Total Orders | 26K |
| Total Customers | 4.3K |
| Repeat Customer Rate | 69.97% |
| Top Customer Revenue | 1.69M |
| Top Product Revenue | 241.31K |
| Anomaly Revenue | 3.21M |
| Highest Anomaly Z-Score | 7.86 |

> Note: Metrics are based on the cleaned dataset and Power BI model used in this project.

---

## 🌍 Key Business Insights

### Market Performance
The United Kingdom was identified as the dominant revenue-contributing market, highlighting significant market concentration.

### Product Performance
Product-level analysis helped identify the products contributing most significantly to overall revenue.

### Customer Intelligence
Customer analysis revealed the contribution of high-value customers and the importance of repeat purchasing behaviour.

### Revenue Anomaly
Z-score analysis identified a significant unusual revenue event with a **Z-score of 7.86**, representing approximately **3.21M in anomaly revenue**.

---

## 🚨 Anomaly Detection

Revenue anomalies were identified using statistical analysis.

### Method

Daily revenue was calculated and standardized using a Z-score:

**Z = (Observed Revenue − Mean Revenue) / Standard Deviation**

A high absolute Z-score indicates that a revenue observation significantly differs from the normal revenue pattern.

This allows the business to investigate:

- Unexpected revenue spikes
- Unusual revenue drops
- Potential operational issues
- Exceptional sales events
- Data quality issues

---

## 🤖 Agentic AI Component

The project incorporates **Agentic AI** to move beyond traditional dashboard reporting.

The AI workflow can assist with:

1. Understanding business questions
2. Accessing analytical data
3. Performing calculations
4. Identifying important patterns
5. Detecting anomalies
6. Generating business-oriented insights
7. Supporting further investigation

### Technologies Used

- **Ollama** — Local LLM execution
- **Python** — Data processing and analysis
- **APIs** — Connecting analytical components
- **Jupyter Notebook** — Agentic AI workflow
- **Power BI** — Visualization and business intelligence

---

## 🛠️ Technology Stack

### Data Analysis
- Python
- Pandas
- NumPy
- Jupyter Notebook

### Business Intelligence
- Power BI
- DAX
- Data Modeling
- Interactive Dashboarding

### AI
- Agentic AI
- Ollama
- LLM-based analysis
- API integration

### Statistical Analysis
- Z-score
- Revenue anomaly detection
- Trend analysis

---

## 📈 Dashboard Features

The Power BI dashboard provides:

- Revenue KPIs
- Order analysis
- Customer analysis
- Product performance
- Country/market analysis
- Revenue trends
- Customer contribution
- Product contribution
- Repeat customer analysis
- Revenue anomaly detection
- Z-score analysis
- Interactive filtering and navigation

---

## 💼 Business Impact

The solution transforms raw e-commerce transactions into a **decision-ready revenue intelligence layer**.

It helps decision-makers:

- Identify major revenue drivers
- Monitor market concentration
- Understand product performance
- Identify high-value customers
- Detect unusual revenue movements
- Prioritize areas for investigation
- Make faster data-driven decisions

Rather than claiming an unsupported percentage increase in revenue, the measurable impact of this project is **improved revenue visibility, faster anomaly identification and better prioritization of business opportunities and risks**.

--

 
