# Customer Segmentation Analysis using K-Means Clustering

## Project Overview
This project focuses on identifying distinct customer segments within a retail dataset using Unsupervised Machine Learning. By analyzing annual income and spending scores, the model categorizes customers into groups to enable data-driven marketing strategies and improved customer relationship management.

## Technical Stack
* **Language:** Python 3.12
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / VS Code

## Methodology
The analysis follows a standard data science workflow:
1. **Data Exploration:** Initial analysis of the distribution and correlation of features.
2. **Feature Selection:** Selecting relevant attributes (Annual Income and Spending Score) for clustering.
3. **Hyperparameter Tuning:** Utilizing the **Elbow Method** to determine the optimal number of clusters (K) by calculating the Within-Cluster Sum of Squares (WCSS).
4. **Model Training:** Implementing the K-Means algorithm with the optimized K value.
5. **Visualization:** Mapping the segments and their respective centroids to interpret customer behavior.

## Key Findings
The model successfully identified 5 primary customer segments:
* **High Income, High Spending:** Target group for premium products and loyalty programs.
* **High Income, Low Spending:** Potential group for targeted promotional offers.
* **Average Income, Average Spending:** Stable customer base.
* **Low Income, High Spending:** High-engagement group, sensitive to trends.
* **Low Income, Low Spending:** Budget-conscious segment.

## How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed:
   `pip install pandas scikit-learn seaborn matplotlib`
3. Open and run the `analiz.ipynb` notebook.