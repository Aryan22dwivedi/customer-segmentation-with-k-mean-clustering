# customer-segmentation-with-k-mean-clustering
Python code for segmenting customers and visualize by libraries

# 📊 Customer Segmentation Using K-Means

## 📌 Problem Statement
Businesses need to target different customers differently based on behavior. To maximize marketing efficiency and improve customer satisfaction, it's essential to group customers with similar purchasing patterns and behaviors.

## 🎯 Objective
Use **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on:

- **Age**
- **CustomerID**
- **Gender**
- **Annual Income (k$)**
- **Spending Score (1-100)**

This clustering helps businesses create **personalized marketing strategies** for different customer types.


## 🛠️ Requirements

### Dataset Features:
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income
- `Spending Score (1-100)`: Average amount spent per visit

### Technical Stack:
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- scikit-learn

## 🔄 Workflow

### 1. Data Collection
:**Mall_customers.csv** is downloades from Kaggle
![image](https://github.com/user-attachments/assets/212bb9a1-1da3-470c-b874-0f0e7530876f)


### 2. Data Preprocessing
- Checked for null values
- Applied **StandardScaler** to normalize the feature scale

### 3. K-Means Clustering
- Determined optimal number of clusters (k) using **Elbow Method**
- Applied **KMeans** to group customers into clusters
- Added cluster labels to the dataset

### 4. Visualization
- 2D scatter plots to visualize clusters (e.g., Income vs Spending)
- Optional: 3D scatter plots for richer insights (Age vs Income vs Spending)

### 5. Cluster Profiling
- Analyzed and interpreted each cluster
- Mapped business strategies to each customer type

## 📈 Expected Outcome

- Clearly defined **3 to 5 distinct customer segments**
- Each cluster represents a unique customer group (e.g., high-income frequent spenders, budget shoppers, etc.)
- Provides data-driven insights for marketing campaigns, product offers, and customer retention strategies

## 📷 Sample Visualizations

- **2D Cluster Plot**: Visualizes how customers group by Income and Spending
- ![image](https://github.com/user-attachments/assets/8ffbac46-1518-471a-8e4e-df70ac4d2d26)

- ![image](https://github.com/user-attachments/assets/7154c8e0-9260-43c9-86aa-3760691f4de1)

- **3D Scatter Plot**: Shows relationships among Age, Income, and Spending across clusters
- ![image](https://github.com/user-attachments/assets/6b940160-a08a-4b83-b14e-93264b26d6b4)

- ![image](https://github.com/user-attachments/assets/872db107-2e8b-43c4-a7ec-7ca1cd8af135)




## 🧠 Business Value

This segmentation enables businesses to:

- Personalize email campaigns
- Improve product recommendations
- Increase customer lifetime value
- Optimize pricing strategies

## 🙋‍♂️ Author

**Aryan kumar dwivedi**  

