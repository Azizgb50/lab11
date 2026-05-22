# Lab 11: Credit Card Customer Segmentation Using K-Means

## Project Description

This lab focuses on customer segmentation using machine learning. The goal is to apply the K-Means clustering algorithm to a credit card customer dataset and group customers based on their spending and payment behavior.

The project includes data loading, data cleaning, exploratory data analysis, feature scaling, choosing the best number of clusters, applying K-Means, and visualizing the final customer groups.

## Dataset

The dataset used in this lab is:

`CC_GENERAL.csv`

It contains credit card customer information such as balance, purchases, cash advances, credit limit, payments, and other financial behavior features.

## Files Included

- `Lab11_Credit_Card_Customer_Segmentation_Completed.ipynb`
- `CC_GENERAL.csv`
- `README.md`

## Tools and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Main Steps

1. Import required libraries
2. Load the dataset
3. Explore the data
4. Check missing values
5. Clean and prepare the dataset
6. Scale the data using StandardScaler
7. Use the Elbow Method to choose the number of clusters
8. Apply K-Means clustering
9. Analyze the final clusters
10. Visualize the clusters using PCA
11. Answer the final lab questions

## Machine Learning Method

The main machine learning algorithm used in this lab is:

`K-Means Clustering`

K-Means is an unsupervised learning algorithm used to divide data into groups based on similarity. In this lab, it is used to segment credit card customers into different customer groups.

## Output

The notebook produces:

- Dataset preview
- Data information
- Missing value summary
- Data visualization graphs
- Elbow curve
- Silhouette score results
- Final customer clusters
- PCA cluster visualization
- Final written answers

## How to Run

1. Download the notebook and dataset.
2. Place `CC_GENERAL.csv` in the same folder as the notebook.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Run all cells from top to bottom.
5. Review the generated graphs and final answers.

## Conclusion

This lab demonstrates how K-Means clustering can be used to segment customers based on financial behavior. The results can help businesses understand different customer types and make better marketing or service decisions.
