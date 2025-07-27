# 🛍️ Online Retail Customer Segmentation & Analysis

This project focuses on analyzing and segmenting customers based on their purchase behavior using the **Online Retail Dataset**. By applying data cleaning, feature engineering, RFM analysis, and unsupervised learning techniques, we uncover key business insights that can support marketing and customer retention strategies.

## 📁 Dataset
The dataset contains transactions from a UK-based online retail store between **2010–2011**, including:
- Invoice number, date, and time
- Product descriptions and codes
- Quantities and unit prices
- Customer IDs and countries

## 🔧 Techniques & Tools Used
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Feature Engineering**: TotalPrice, returns detection, time features
- **Data Cleaning**: Removed nulls, duplicates, and negative values
- **RFM Analysis**: Recency, Frequency, Monetary value calculation
- **Clustering**: K-Means with silhouette score evaluation
- **NLP (Optional)**: WordCloud and TF-IDF on product descriptions
- **Visualization**: Distribution plots, heatmaps, elbow curve, and cluster scatter plots

## 📊 Key Insights
- The **UK** dominates in sales, contributing to over 90% of transactions.
- Most purchases occur during **working hours** and spike around **November–December**.
- Several **popular product themes** such as "heart", "bag", and "retro" were discovered.
- **Customer segmentation** revealed distinct clusters like:
  - High-spending loyal customers
  - Infrequent or one-time buyers
  - Recently acquired customers

## 📁 Project Structure

Online-Retail-Prediction/
│
├── Swapnil_Dixit's_Clustering_prj.ipynb # Main notebook with all analysis
├── README.md # This README file

## 📌 How to Run
1. Clone the repo:
git clone: https://github.com/your-username/Online-Retail-Prediction.git


## 🚀 Future Work
- Build a predictive model to forecast customer churn or lifetime value
- Deploy as an interactive dashboard using Streamlit or Flask
- Perform market basket analysis with association rules

## 🙌 Acknowledgements
- Inspired by real-world applications in e-commerce and retail analytics

---

📌 **Developed by**: *Swapnil Dixit*  
🕓 **Year**: 2025


