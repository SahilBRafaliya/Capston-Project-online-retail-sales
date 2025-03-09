# 🚀 Online Retail Customer Segmentation

## 📌 Project Overview
This project focuses on **customer segmentation for an online retail store** to enhance marketing strategies and business performance. By analyzing purchasing patterns, the project aims to identify distinct customer groups and provide actionable insights for **targeted marketing** and **inventory management**.

---
## 🎯 Features
✅ Customer segmentation using **RFM Analysis**  
✅ Clustering customers based on purchase behavior  
✅ Data visualization for better insights  
✅ Targeted marketing recommendations  

---
## 🛠️ Technologies Used
- 🐍 Python
- 📊 Pandas, NumPy
- 🤖 Scikit-learn
- 🎨 Matplotlib, Seaborn

---
## 🔍 Techniques Used

### 1️⃣ RFM (Recency, Frequency, Monetary) Analysis
📅 **Recency:** Measures how recently a customer made a purchase.  
🔁 **Frequency:** Counts how often a customer purchases.  
💰 **Monetary Value:** Captures the total spending of a customer.  

### 2️⃣ Data Pre-processing
🛠️ **Handling Missing Values:** Removed rows with missing data.  
❌ **Filtering Negative Quantities:** Excluded transactions with negative values.  
📆 **Date Conversion:** Converted purchase dates to datetime format.  
📏 **Feature Standardization:** Scaled RFM values for clustering.  

### 3️⃣ K-Means Clustering
📌 Applied **K-means clustering** to segment customers into 4 groups.  
📊 Used the **Elbow Method** to determine the optimal number of clusters.  

### 4️⃣ Model Evaluation & Visualization
📈 Used **pair plots** and **box plots** to analyze cluster distributions.  
🛍️ Assigned meaningful labels to clusters:
   - 🏆 **High-Value Customers**
   - 🎯 **Mid-Value Customers**
   - 📉 **Low-Value Customers**
   - ⚠️ **Churn Risk Customers**

---
## 🚀 How to Use
1️⃣ Load the dataset `OnlineRetail.csv`.  
2️⃣ Run the provided Jupyter Notebook to process data and perform clustering.  
3️⃣ Visualize customer segments and analyze business insights.  

---
## 🔮 Future Enhancements
📢 **Integration with Marketing Campaigns:** Implement targeted promotions.  
📊 **Continuous Monitoring:** Update clustering based on evolving customer behavior.  
🛍️ **E-commerce Integration:** Automate segmentation for personalized recommendations.  

---
## 📌 Conclusion
This project demonstrates how **RFM analysis** and **K-means clustering** can effectively segment customers for an online retail business, enabling data-driven marketing strategies. **Continuous monitoring and adaptation** will enhance long-term customer engagement.  

---
## 📚 References
📖 MacQueen, J.B. (1967). *Some Methods for Classification and Analysis of Multivariate Observations*, University of California Press.

