# Marketing Analytics Project – End-to-End Analysis

**Tools used:** SQL | Python | Power BI

---

## 1. Project Objective

The objective of this project was to understand why marketing performance was not improving even after running multiple campaigns and increasing marketing spend.

The analysis focused on identifying issues related to:
- Conversion performance  
- Customer engagement  
- Customer feedback and satisfaction  

The goal was to turn raw marketing and customer data into insights that could support better marketing decisions.

---

## 2. Data Sources & Flow

The project followed a structured data flow instead of directly creating dashboards.

**Overall flow:**
SQL → Python → Power BI


Each tool was used for a specific purpose in the analysis process.

---

## 3. SQL Work – Data Preparation

SQL was used to prepare and organize the data before analysis.

### Data Tables Used
- Customer information  
- Product details  
- Customer journey data  
- Marketing engagement data  
- Customer review data  

### Work Done in SQL
- Loaded raw data into SQL tables  
- Organized the data into fact and dimension style tables  
- Used joins to combine customer, product, engagement, and journey data  
- Verified data consistency before using it for analysis  

SQL ensured the data was structured and reliable before moving to Python and Power BI.

---

## 4. Python Work – Customer Review Enrichment

Customer reviews included text data that required additional processing.

### Work Done in Python
- Exported customer review data from SQL  
- Processed review text  
- Classified reviews into sentiment categories (positive, negative, mixed, neutral)  
- Combined sentiment results with customer ratings  
- Saved enriched review data as CSV files  

Python helped add context to customer feedback beyond numeric ratings.

---

## 5. Power BI – Data Modeling & Measures

### Data Loaded
- SQL tables (customers, products, engagement, journey data)  
- Python-generated CSV files with sentiment data  

### Data Modeling
- Created relationships between datasets  
- Added a calendar table using DAX for time-based analysis  
- Ensured correct granularity across tables  

### Measures Created
- Conversion rate  
- Engagement metrics  
- Average customer rating  
- Sentiment counts and trends  

---

## 6. Analysis Performed

### Conversion Analysis
- Analyzed monthly conversion trends  
- Identified high and low performing months  
- Compared conversion performance across products  
- Observed seasonal patterns  

### Engagement Analysis
- Analyzed views, clicks, and likes over time  
- Noted a decline in engagement during later months  
- Compared engagement across content types  

### Customer Feedback Analysis
- Reviewed customer rating distribution  
- Compared sentiment with numeric ratings  
- Identified gaps between current satisfaction and targets  

---

## 7. Key Insights
- Conversion performance varied significantly by month  
- Certain products consistently converted better  
- Engagement declined even though content was active  
- Customer sentiment was mostly positive but below the desired level  

---

## 8. Recommendations
- Focus marketing efforts on high-converting products  
- Improve campaigns during low-performing months  
- Enhance content messaging and calls-to-action  
- Address recurring issues in negative and mixed reviews  

---

## 9. Final Outcome

This project provided a clear view of marketing performance using a structured analytics approach.

It demonstrates how:
- SQL was used for data preparation  
- Python was used for text enrichment  
- Power BI was used for analysis and reporting  

The final dashboard supports data-driven marketing decisions.

---

## 10. Skills Applied
- SQL  
- Python  
- Power BI  
- Marketing performance analysis  
- Data cleaning and validation  
