# Customer Segmentation with KMeans Clustering

This project uses KMeans clustering to segment mall customers based on their age, annual income, and spending score. The objective is to help the marketing team identify distinct customer groups and create targeted strategies to engage each segment effectively.

---

## Problem Statement

The marketing team at a retail mall wants to understand customer behavior to design more effective and personalized marketing campaigns. The goal is to segment customers into meaningful groups based on demographics and spending patterns.

---

## Dataset

- File: `Mall_Customers.csv`
- Contains 200 customer records with the following features:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## Approach

1. **Exploratory Data Analysis (EDA)**
2. **Data Preprocessing**
   - One-hot encoding for categorical variables
   - Feature scaling using StandardScaler
3. **KMeans Clustering**
   - Elbow method to determine optimal number of clusters
   - Final clustering model with customer assignments
4. **Cluster Profiling**
   - Summary statistics (mean Age, Income, Spending Score)
   - Custom business metric: Segment Value = Income × Spending Score
5. **Visualizations**
   - Annual Income vs Spending Score (colored by cluster)
   - Age vs Spending Score
   - Gender distribution by cluster

---

## Key Insights

- Five unique customer segments were identified.
- Some segments represent high-value customers based on income and spending behavior.
- Each cluster demonstrates distinct demographic and behavioral characteristics that can inform targeted marketing strategies.

---

## Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## Sample Segment Recommendations

| Segment | Description | Suggested Strategy |
|---------|-------------|--------------------|
| Segment A | Young, high spending | Social media campaigns, influencer collaborations |
| Segment B | High income, low spending | Personalized offers, loyalty programs |
| Segment C | Balanced profile | General engagement strategies, A/B testing |
| Segment D | Low income, low spending | Minimal marketing investment, basic engagement |

---

## Project Files

- `Customer_Segmentation.ipynb`: Main notebook with all code and analysis
- `Mall_Customers.csv`: Dataset used for clustering
- (Optional) `Slides.pdf`: Summary presentation of project and findings

---

## About Me

I’m Anvesha, a data analyst passionate about turning complex datasets into actionable business insights. Outside of analytics, I enjoy singing, playing guitar, and reading fiction. Feel free to connect on [LinkedIn](https://www.linkedin.com/in/anvesha-m-17110296/).
