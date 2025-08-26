# CUSTOMER_SEGMENTATION-USING-CLUSTERING
This project applies **unsupervised learning** to segment mall customers based on demographic and spending data. The goal is to identify customer groups to help businesses design targeted marketing strategies.

## Dataset
- **Source:** [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- Contains customer demographic information (Gender, Age, Income) and spending behavior (Spending Score).  

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Checked distributions of Age, Income, and Spending Score.
   - Identified customer behavior patterns and correlations.

2. **Feature Scaling**
   - Standardized features for fair distance-based clustering.

3. **Clustering**
   - **K-Means Clustering:** Optimal clusters determined using Elbow Method & Silhouette Score.  
   - **Hierarchical Clustering:** Agglomerative clustering with dendrogram analysis.  

4. **Visualization**
   - 2D and 3D cluster plots for better understanding of customer groups.  
   - Clear separation of segments like high-income/high-spending, low-income/low-spending, etc.  

## Results & Insights
- Identified **distinct customer groups** based on demographics and spending.  
- Business Insights:
  - High-income & high-spending customers → Premium targeting.  
  - Low-income & high-spending → Discount campaigns.  
  - Young customers → Trend-based marketing.  

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, scipy  

## Future Improvements
- Apply advanced clustering (DBSCAN, Gaussian Mixture Models).  
- Deploy clustering results in a dashboard (e.g., Power BI, Tableau, Streamlit).  
- Integrate customer segmentation with recommendation systems.  

---

### 🔗 Author
Developed as part of a **Machine Learning project** to explore clustering techniques and business applications.
