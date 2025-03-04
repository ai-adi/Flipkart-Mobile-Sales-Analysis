# Flipkart Mobiles Dashboard  

## **Problem Statement**  
This dashboard helps understand mobile phone trends on Flipkart, providing insights into brand popularity, pricing, ratings, and discounts. It enables users to identify the best deals, compare storage and memory variants, and analyze customer preferences.  

---

## **Steps Followed**  

### **Step 1: Load Data into Power BI Desktop**  
- Dataset: **Flipkart_Mobiles.csv**  
- Data loaded into Power BI.  

### **Step 2: Data Cleaning & Preprocessing**  
- Opened **Power Query Editor** for cleaning.  
- Checked **column distribution, column quality, and column profile**.  
- Removed null/missing values from key columns like **Memory, Storage, Rating, and Prices**.  

### **Step 3: Data Transformations**  
- **New Columns Created:**  
  - **Discount (%)** = `(Original Price - Selling Price) / Original Price * 100`  
  - **Price Category** (Low, Mid, Premium) based on Selling Price.  
  - **Brand Popularity** based on the number of listings per brand.  

### **Step 4: Data Visualization**  
- **Key Insights Visualized:**  
  - **Top 5 Mobile Brands** based on number of listings.  
  - **Average Ratings per Brand** using a bar chart.  
  - **Discount % Distribution** via histogram.  
  - **Storage & RAM Analysis** using a matrix table.  
  - **Price vs Rating Scatter Plot** to find best value-for-money phones.  

### **Step 5: Filters & Slicers Added**  
- **Brand** (Dropdown filter).  
- **Price Range** (Slider).  
- **Ratings** (Star filter).  
- **RAM & Storage Options** (Multi-select).  

### **Step 6: Publishing to Power BI Service**  
- Report published for interactive analysis.  

---

## **Key Insights**  

### **1. Top Mobile Brands on Flipkart**  
- **Samsung, OPPO, Realme, Vivo, and Apple** have the highest listings.  

### **2. Price Segmentation**  
- **50% of mobiles** are in the mid-range (₹10,000 - ₹30,000).  
- **Premium phones (₹30,000+)** make up around 20% of listings.  

### **3. Discounts & Best Deals**  
- Average discount across all models: **18-25%**.  
- **Some brands offer up to 40% discounts** on select models.  

### **4. Ratings & Customer Preferences**  
- **Apple and Samsung have the highest average ratings (4.5+).**  
- **Budget brands (like Infinix & Tecno) have mixed ratings (3.5-4.2).**  
- Higher **RAM & storage variants tend to have better ratings**.  

### **5. Storage & RAM Comparison**  
- **128GB Storage & 6GB RAM is the most common variant.**  
- **More expensive models tend to offer 256GB+ storage options.**  

---



This dashboard provides a **one-stop view** of Flipkart's mobile trends, helping both buyers and sellers make informed decisions. 🚀
