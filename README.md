# **Flipkart Mobiles Dashboard**  

## **Problem Statement**  
This dashboard provides insights into mobile sales on Flipkart, analyzing brand popularity, storage/memory preferences, color trends, and total sales. It helps businesses understand customer preferences and optimize their product listings for better performance.  

---

## **Steps Followed**  

### **Step 1: Load Data into Power BI Desktop**  
- Dataset: **Flipkart_Mobiles.csv**  
- Imported and prepared data for visualization.  

### **Step 2: Data Cleaning & Preprocessing**  
- Opened **Power Query Editor** and checked **column distribution, column quality, and column profile**.  
- Identified missing values in **RAM, Storage, and Ratings** and handled them appropriately.  

### **Step 3: Data Transformations**  
- **Created new columns** to enhance analysis:  
  - **Discount (%)** = `(Original Price - Selling Price) / Original Price * 100`  
  - **Price Category**: Low (₹0-₹10K), Mid (₹10K-₹30K), Premium (₹30K+)  
  - **Total Sales per Brand**  

### **Step 4: Data Visualization**  
- **Key Insights Visualized:**  
  - **Top Rated Phones** (Donut Chart)  
  - **Top Selling Brands** (Bar Chart)  
  - **Sales by RAM Capacity** (Treemap)  
  - **Top Selling Colors** (Bar Chart)  

### **Step 5: Filters & Slicers Added**  
- **Brand & Model Filters** for brand-specific analysis.  
- **Storage & RAM Filters** for variant comparisons.  
- **Price & Rating Sliders** for user preference selection.  

### **Step 6: Publishing to Power BI Service**  
- Report was finalized and published for interactive analysis.  

---

## **Dashboard Explanation**  

### **1️⃣ Top Rated Phones (Donut Chart - Top Center)**  
- Displays **highest-rated mobile brands** based on customer reviews.  
- **Samsung (23.64%) has the highest ratings**, followed by **Apple (12.11%)** and **Realme (10.77%)**.  
- Brands like **Xiaomi, Nokia, and Vivo** have a smaller share of highly-rated phones.  

### **2️⃣ Top Selling Brands (Bar Chart - Top Right)**  
- Shows **total sales value by brand**.  
- **Samsung leads with ₹31.7M in total sales**, followed by **Realme (₹17.5M) and Apple (₹5.4M)**.  
- **Other brands like OPPO, Xiaomi, and Nokia** have lower sales volumes.  

### **3️⃣ Sales by RAM Capacity (Treemap - Bottom Left)**  
- Displays sales distribution based on **RAM size**.  
- **4GB RAM (750 units) and 6GB RAM (497 units) are the most sold variants**.  
- **Lower RAM (1GB, 2GB, 512MB) has significantly fewer sales**, showing customer preference for better performance.  

### **4️⃣ Top Selling Colors (Bar Chart - Bottom Right)**  
- **Black (489 sales) is the most popular color**, followed by **Gold (195), White (155), and Blue (146)**.  
- **Lesser-known colors like Diamond Black and Midnight Blue have lower sales**.  

### **5️⃣ Filters (Left Panel - Brand & Model Selection)**  
- Allows users to **select specific brands or models** to update the dashboard dynamically.  

---

## **Insights & Recommendations**  

### **[1] Best-Selling & Top-Rated Brands**  
- **Samsung dominates both sales and ratings**, making it the most successful brand.  
- **Apple has high ratings but lower sales**, likely due to premium pricing.  

### **[2] Price & Customer Preferences**  
- **Most sales are in the ₹10K-₹30K range**, showing mid-range phones are in demand.  
- **Higher RAM and storage variants are preferred**, as seen in the sales trend.  

### **[3] Color & Variant Preferences**  
- **Black is the most popular color**; brands should prioritize offering black models.  
- **Sales of lower RAM devices are decreasing**, indicating a shift towards higher-performance mobiles.  

### **[4] Recommendations for Flipkart & Sellers**  
✅ **Stock more 4GB & 6GB RAM variants** as they are in high demand.  
✅ **Offer better discounts on premium brands** like Apple to boost sales.  
✅ **Optimize marketing for mid-range mobiles (₹10K-₹30K)** since they dominate sales.  



This dashboard provides **a detailed view of Flipkart's mobile sales trends**, helping businesses make data-driven decisions for better customer engagement.
