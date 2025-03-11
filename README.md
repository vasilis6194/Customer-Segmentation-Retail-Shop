# 📊 Customer Segmentation for Retail Store

[![Customer Segmentation Thumbnail](https://github.com/vasilis6194/Customer-Segmentation-Retail-Shop/blob/main/presentation/clustering%20project%20thumbnail.jpg)

### Click below to view the interactive Power BI report:

[![View Power BI Report](https://github.com/vasilis6194/Customer-Segmentation-Retail-Shop/blob/main/analysis/powerbi_image.jpg)](https://app.powerbi.com/view?r=eyJrIjoiZGU5NDYyODgtMTc3NC00OTZiLWFkN2ItNDlmOTA3MjBjMGRjIiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9)

## 📌 Project Overview
This project focuses on **customer segmentation** for a retail store using **unsupervised learning (K-Means Clustering)**. By transforming transactional data into **RFM metrics (Recency, Frequency, Monetary Value)**, we successfully identified distinct customer groups, enabling **targeted marketing strategies** and improved customer retention.

---

### **Team Members**
- **George Birmpakos**
- **Konstantinos Kalentzis**
- **Vasilis Katsikas**

## 🔹 Data Processing & Feature Engineering
We started with **transaction-level data** containing:
- **InvoiceNo** → Unique transaction ID
- **StockCode & Description** → Product details
- **Quantity & UnitPrice** → Purchase details
- **InvoiceDate** → Transaction timestamp
- **CustomerID & Country** → Customer details

### ✅ Transition to RFM Analysis
To analyze customer behavior, we derived **RFM features**:
- **Recency (R):** Days since last purchase
- **Frequency (F):** Number of purchases
- **Monetary Value (M):** Total spending

**📌 Why RFM?**  
It provides a structured approach to measuring customer **engagement & value**, making it ideal for segmentation.

---

## 🔹 Applying K-Means Clustering
- **Standardized RFM data** to ensure fair clustering.
- Used **Elbow Method** to determine the optimal number of clusters.
- Applied **K-Means Clustering** to segment customers into **four groups**:

| **Cluster** | **Behavior** | **Strategy** |
|------------|-------------|-------------|
| 🟡 **Inactive** | Long recency, low frequency & spending | Win-back campaigns, discounts |
| 🟠 **Churn Risk** | Medium recency & frequency | Personalized offers, loyalty incentives |
| 🟢 **Loyal** | Frequent buyers, high spending | VIP perks, referral programs |
| 🔵 **Growing** | Recent buyers, increasing engagement | Onboarding, cross-selling |

---

## 🔹 Business Impact
By implementing this **data-driven customer segmentation**, the retail store can:
✅ **Increase retention** through personalized engagement  
✅ **Boost revenue** with targeted promotions  
✅ **Improve marketing efficiency** by focusing on high-value customers  

💡 **Next Steps:** Automating marketing campaigns and integrating segmentation into CRM systems for real-time insights. 🚀

---

## 🚀 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning** (K-Means Clustering)
- **Feature Engineering** (RFM Analysis)
- **Data Visualization** (Cluster Insights)

