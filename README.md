# Marketing & Retail Analytics – MRA

RFM Segmentation and Market Basket Analysis using Python, KNIME, and Tableau  
Project from the PGP-DSBA Program (Great Lakes & Texas McCombs)

---

## 1. Project Overview

This project analyzes customer purchasing behavior for a retail business using:

- **RFM Segmentation**
- **Market Basket Analysis (Association Rules)**
- **Exploratory Data Analysis (EDA)** using Python
- **KNIME workflows** for automation
- **Tableau dashboards** for visualization

The objectives of the project are to understand:

- Who the most valuable customers are  
- Which products are frequently purchased together  
- Which customer segments contribute the highest revenue  
- What marketing strategies can increase sales and retention  

---

## 2. Repository Structure


---

## 3. Part A — RFM Segmentation

### **Techniques Used**

- RFM metric calculation (Recency, Frequency, Monetary)
- Customer segmentation using RFM scoring
- Distribution and boxplot analysis
- Customer value analysis
- Visual EDA using Python
- KNIME workflow automation

### **Key Insights (Part A)**

- High-value VIP customers were identified using RFM scores  
- High-frequency & high-monetary customers contribute the majority of total revenue  
- Low-frequency and low-monetary customers require retention strategies  
- Product-level patterns show clear opportunities for targeted marketing  

---

## 4. Part B — Market Basket Analysis (Association Rules)

### **Techniques Used**

- Transaction grouping  
- Bit Vector creation  
- Apriori algorithm  
- Association Rule Learning  
- Rule filtering (Support ≥ 0.01, Confidence ≥ 0.20)  
- Visual analysis of product combinations  

### **Key Insights (Part B)**

- Frequently bought-together product pairs identified  
- High-confidence rules show strong cross-selling opportunities  
- Product bundling can increase average order value  

---

## 5. Tools & Technologies

### **Python**
- Pandas  
- Matplotlib  
- Seaborn  
- MLxtend  

### **KNIME**
- GroupBy  
- Column Aggregator  
- BitVector  
- Association Rule Learner  

### **Visualization**
- Tableau  

### **Datasets**
- Excel/CSV sales and POS transaction files  

---

## 6. How to Run the Workflows

### **RFM Workflow (KNIME)**

1. Open `RFM-1.knwf` in KNIME  
2. Run all nodes sequentially  
3. View the final RFM segments in the output table  

### **Market Basket Workflow (KNIME)**

1. Open `Market_Basket_Analysis_B1.knwf`  
2. Run nodes in sequence  
3. Review association rules in the Table View  

### **Python Notebooks (Google Colab)**

1. Upload the `.ipynb` files to Google Colab  
2. Run all cells in order  
3. Review the generated plots, tables, and insights  

---

## 7. Business Outcomes

This project helps retail businesses:

- Identify loyal and high-spending customers  
- Improve marketing targeting and retention  
- Optimize product bundling & cross-selling  
- Increase sales through data-driven insights  
- Understand buying patterns for better inventory planning  

---

## 8. Author

**Priyanka Mane**  
Aspiring Data Scientist | PGP-DSBA (Great Lakes & Texas McCombs)  
GitHub: https://github.com/pcm-ds19  
LinkedIn: https://www.linkedin.com/in/priyanka-mane-361774316/

---

