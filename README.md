# K-Means Customer Segmentation

This project implements the **K-Means clustering algorithm** to segment customers of a retail store based on their purchase history. The goal is to group customers into distinct clusters so that marketing strategies can be better targeted.

---

## 📂 Dataset

The dataset used contains the following features:

- **CustomerID** – Unique identifier for each customer  
- **Gender** – Male or Female  
- **Age** – Age of the customer  
- **Annual Income (k$)** – Customer’s yearly income (in thousands of dollars)  
- **Spending Score (1-100)** – A score that represents how much the customer spends (higher means more spending)

---

## 🔧 Features and Workflow

1. **Data Preprocessing**  
   - Dropping unnecessary columns  
   - Encoding categorical features like Gender  
   - Scaling features for better clustering

2. **Finding the optimal number of clusters**  
   - Using the **Elbow Method** to visually determine the best cluster count

3. **Applying K-Means Clustering**  
   - Segmenting customers into clusters based on their spending patterns

4. **Visualization**  
   - Plotting graphs to represent customer segments  
   - Helping identify groups for marketing campaigns

---

## 📦 How to Run

1. Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn

#The script will generate:

An Elbow plot to help decide the number of clusters

A scatter plot showing customer segments by income and spending score
#Insights

This clustering model can help businesses:

Understand customer behavior

Target specific groups for promotions

Improve customer satisfaction and sales

📌 Future Improvements

Explore other clustering algorithms like DBSCAN or hierarchical clustering

Add more features like location or shopping frequency

Enhance visualization with interactive dashboards