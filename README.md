# Codectechnologies-Project
# 📊 Walmart Sales Forecasting
A complete sales analysis & forecasting project using a cleaned Walmart dataset. This repo contains an interactive Excel dashboard (KPIs, Pivot charts, slicers), with EDA and time-series forecasting using Prophet, LSTM, and SARIMAX. Visual outputs from the notebook are included as screenshots to provide actionable business insights.

##  The project includes:
* **Exploratory Data Analysis(EDA)**: For understanding sales patterns and correlations. 
* **Time-Series Forecasting Models**: Prophet, SARIMAX, and LSTM for future sales prediction.
* **Excel Dashboard**: With KPIs, charts, and slicers for interactive analysis.
Visual Documentation with screenshots of analysis and results.

##  Dataset Used 
**Dataset used from [Kaggle]** : Walmart dataset (train.csv, stores.csv, features.csv) — *(cleaned and combined).*     
[**View Walmart Dataset**](https://docs.google.com/spreadsheets/d/1Kbrbc9CQBTZNV220YzsPlV9dwtfEG6Kb/edit?usp=sharing&ouid=116900853174133008630&rtpof=true&sd=true)

##  Dataset Details
The dataset contains the following fields:
* Store – Store number
* Dept – Department number
* Date – Sales date
* Weekly_Sales – Sales revenue for the week
* IsHoliday – Indicates whether the week includes a holiday
* Temperature – Average temperature 
* Fuel_Price – Fuel cost 
* CPI – Consumer Price Index
* Unemployment – Unemployment rate
* MarkDown1–5 – Promotional markdown data
* Type – Store type (A, B, or C)
* Size – Store size
* Week, Month, Year – Time features extracted for trend analysis

##  Tools & Technologies
* **Python**: Pandas, Matplotlib, Seaborn, NumPy, TensorFlow, Prophet etc.
* **Excel**: Data analysis and Dashboard design  
* **Data Visualization** – Interactive charts, cards, and slicers.

##  Exploratory Data Analysis (EDA): 
**For understanding sales patterns and correlations.**

<img width="1506" height="910" alt="Screenshot (158)" src="https://github.com/user-attachments/assets/c7aac446-4dea-4a9b-917e-94e9f33ac256" />

##  Time-Series Forecasting Models for future sales prediction:
### 1. Prophet:

   <img width="1508" height="914" alt="Screenshot (162)" src="https://github.com/user-attachments/assets/a7f04252-b1f0-455b-992b-216907765524" />

### 2. SARIMAX:

   <img width="1506" height="911" alt="Screenshot (161)" src="https://github.com/user-attachments/assets/c7b04c52-2cbb-41e8-8bdd-6b7cd9ef2343" />

### 3. LSTM:

   <img width="1503" height="731" alt="Screenshot (163)" src="https://github.com/user-attachments/assets/c63c19f2-411e-4154-8e12-4da100f43a3a" />

## Seasonality by month:
<img width="1500" height="907" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/145da0a5-db05-4476-9fe0-7806adf34410" />

## Holiday vs Non-Holiday sales:
<img width="1504" height="815" alt="Screenshot (160)" src="https://github.com/user-attachments/assets/c7444660-6a0d-4b8e-a5fe-d5f60fafb2d5" />

## 📊 Time-series forecasting Insights:
- Long-term trend shows decrease in sales.
- Monthly seasonality: Sales peak around Nov-Dec (holiday season).
- Holiday weeks show clear uplift in average sales.
- Promotions positively correlate with higher weekly sales.
- SARIMAX captured seasonality well; 
- Prophet is interpretable
- LSTM captured complex patterns.

## Interactive Excel dashboard contains:
* Pivot tables & Pivot charts
* **KPI cards** ( Key Performance Indicators)-
1.	Total Sales: ₹6,73,72,18,987.00 – Represents the cumulative sales generated across all stores and departments.
2.	Average Weekly Sales: ₹15,981.26 – Gives an idea of the overall sales consistency per week.
3.	Best Week Sales: ₹6,93,099.36 – The maximum revenue recorded in the best-performing week.
4.	Worst Week Sales: ₹4,988.94 – The lowest revenue recorded in the least-performing week.
5.	Holiday Avg. Sales: ₹17,035.82 – Shows higher average sales during holiday weeks, highlighting holiday demand surges.
6.	Non-Holiday Avg. Sales: ₹15,901.45 – Indicates baseline weekly sales outside holidays.
7.	Top Store by Sales: Store 20 with ₹30,13,97,792.5 – The store contributing the highest sales.
8.	Top Department by Sales: Department 92 – The leading department in terms of revenue contribution.
* **Interactive Filters** (Slicers)
The dashboard is fully interactive with slicers for:
1.	Department – Enables drilling down into department-level sales.
2.	Store – Allows selection of specific store(s) for deeper analysis.
3.	Year (2010, 2011, 2012) – Helps in comparing performance trends year-over-year.
4.	Holiday (True/False) – Filters sales based on holiday vs. non-holiday weeks.

## Dashboard Interaction 
**VIEW DASHBOARD**
<img width="1920" height="1024" alt="Screenshot (156)" src="https://github.com/user-attachments/assets/86e78d41-5fdc-4243-b4a7-400c10a60b83" />

## Business Insights:
* Holiday weeks drive higher sales, confirming festive seasons as critical for revenue.
* Promotional markdowns effectively boost sales, proving their importance in strategy.
* Store Type A contributes the majority of revenue (64%), making large-format stores the key sales drivers.
* Store 20 and Department 92 lead in sales, highlighting top-performing segments.
* Seasonal patterns indicate the need for accurate forecasting and inventory planning.

## 📝 Conclusion
* The Walmart Sales Forecasting project successfully demonstrated how time-series models can predict future sales based on historical data, By applying SARIMAX, Prophet, and LSTM models, by capturing trends, seasonality, and holiday effects.
* The forecasts provide actionable insights for inventory planning, promotions, and business decision-making.
* The analysis revealed that holiday periods and promotions significantly boost sales.
* The forecasts indicate a positive sales growth in upcoming holiday seasons, highlighting the need for strategic inventory planning, targeted promotions, and optimized staffing to meet customer demand.

📌 Internship Project at [codec technologies] (https://codectechnologies.in/)
