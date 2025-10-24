# 🛍️ Customer Segmentation and Spending Behavior Analysis

## 📘 Project Overview
This project analyzes customer demographics and spending behavior using a dataset containing information about **CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1–100)**.  
The primary aim is to discover spending trends, identify customer segments, and develop predictive models that help businesses better understand and target their customers.

Through a blend of **exploratory data analysis (EDA)**, **data visualization**, and **machine learning**, this project highlights how factors like income, age, and gender influence spending behavior — and how customers can be grouped into actionable market segments.

---
- ### [GitHub](https://github.com/donunobunjo/customer_analysis_prediction_and_segmentation.git)
- ### [Dataset](https://github.com/donunobunjo/customer_analysis_prediction_and_segmentation/blob/main/Mall_Customers.csv)

---

## 🎯 Objectives
- Explore the relationships among **Age**, **Annual Income**, and **Spending Score**.  
- Investigate whether **gender** influences spending behavior.  
- Predict **Spending Score** using **Linear Regression**.  
- Segment customers using **clustering algorithms** (e.g., K-Means, Hierarchical Clustering).  
- Derive actionable insights that support **marketing strategies** and **customer retention**.  
- Provide visually appealing insights through **graphs and interactive visualizations**.  

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries for EDA & Visualization:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning Framework:** Scikit-learn  
- **Clustering & Dimensionality Reduction:** K-Means, Hierarchical Clustering, PCA  
- **Development Environment:** Jupyter Notebook / Google Colab  

---

## 🔍 Exploratory Data Analysis (EDA)

### 🔸 Key Questions Explored
- What are the **distributions** of Age, Annual Income, and Spending Score?  
- Do **men spend more** than women?  
- Is **Annual Income correlated** with Spending Score?  
- How does **Age** affect spending habits?  
- Can we identify **distinct customer groups** based on income and spending?  
- Additional explorations:  
  - Which income range dominates the dataset?  
  - Which gender category has higher representation among top spenders?  
  - What’s the relationship between age and income?

### 📊 Visualizations
- **Histograms** for Age, Annual Income, and Spending Score.  
- **Pairwise Scatter Plots** and **Scatter Matrix** for quick visual correlation checks.  
- **Correlation Heatmap** to reveal relationships among numeric features.  
- **Gender-wise Comparison Charts** (Boxplots, Barplots) for spending analysis.  
- **Elbow Method** and **Silhouette Analysis** for optimal cluster selection.  
- **Cluster Scatterplots** (2D visualizations) to display distinct customer segments.  

---

## 🤖 Machine Learning Approach

### 1️⃣ Predictive Modeling — *Linear Regression*
- **Objective:** Predict *Spending Score* from customer attributes such as Age, Gender, and Annual Income.  
- **Model Used:** Linear Regression.  
- **Metrics Evaluated:**  
  - R² Score  
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  

### 2️⃣ Customer Segmentation — *Unsupervised Learning*
- **Objective:** Identify clusters of customers with similar spending and income behavior.  
- **Algorithms Used:**  
  - K-Means Clustering  
  - Hierarchical Clustering  
- **Evaluation Metrics:**  
  - Elbow Method (Inertia)  
  - Silhouette Score  
- **Dimensionality Reduction:** PCA (Principal Component Analysis) applied for better visualization and interpretability.  

---

## 📈 Results & Insights
- **Income vs. Spending:** Customers with higher annual income generally tend to have higher spending scores — though not always strictly linear.  
- **Gender Influence:** Female customers displayed slightly higher spending tendencies than males in this dataset.  
- **Age Factor:** Younger adults often have higher spending scores, whereas older customers show more conservative spending patterns.  
- **Customer Segments Identified:**  
  - High-income, high-spending — **Premium customers**.  
  - Low-income, high-spending — **Potential overspenders**.  
  - High-income, low-spending — **Under-engaged premium group**.  
  - Average-income, average-spending — **Majority group**.
  - Low-income, low-spending.  

---

## ⚖️ Model Comparison

| Model | Task | Key Metric | Summary |
|-------|------|-------------|----------|
| **Linear Regression** | Predict Spending Score | R² Score | Captures general spending trends, limited by behavioral non-linearity |
| **K-Means Clustering** | Segment Customers | Silhouette Score | Clear 4–5 cluster structure identifying distinct customer types |
| **Hierarchical Clustering** | Segment Customers | Dendrogram Analysis | Confirms similar segmentation patterns as K-Means |

---

## 💡 Conclusion
This project demonstrates the use of **data science and machine learning** to understand and segment customers based on demographic and behavioral data.  
By combining **EDA**, **predictive modeling**, and **unsupervised learning**, the analysis offers valuable insights into how customers differ by age, income, and spending patterns — insights that can drive smarter marketing and retention strategies.

---

## 🚀 Future Work
- Experiment with advanced regression models (e.g., **Random Forest**, **Gradient Boosting**).  
- Introduce more behavioral features (e.g., **shopping frequency**, **product category preferences**).  
- Explore **DBSCAN** or **Gaussian Mixture Models** for non-linear cluster shapes.  
- Build an **interactive dashboard** (using Streamlit or Power BI) for dynamic insight visualization.  

---

## 🧑‍💻 Author
**Don Unobunjo**  
Data Analytics | Machine Learning  | AI Automation | Trainer 
📍 Abeokuta, Nigeria  
🔗 [GitHub](https://github.com/donunobunjo) | [LinkedIn](https://www.linkedin.com/in/unobunjo-don)

---

⭐ *If you found this project insightful, don’t forget to star the repository!*  
