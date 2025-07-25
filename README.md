# Bank Customer Segmentation (ML Project)

This project applies **unsupervised machine learning** to segment bank customers into distinct groups based on their behavior, product usage, and churn risk. The goal is to help the bank identify loyal vs. inactive customers and design targeted campaigns to increase engagement and reduce churn.

---

## Project Files

- `Bank_Customer_Segmentation.ipynb` – Main analysis notebook
- `Bank_Churn.csv` – Source dataset (customer attributes)
- `README.md` – Project overview and instructions

---

## Project Context

A UK bank manager approached me with a challenge:

> “I have data on thousands of customers and want to grow our customer base — but I also need to know who’s loyal, who’s inactive, and how to target each group with the right campaign.”

To help, I applied unsupervised machine learning to segment the customer base into four distinct groups based on their behavior, product usage, and churn risk.

This segmentation enabled:
- Clear identification of high-risk and loyal customers
- Campaign strategies tailored to each segment
- A data-driven foundation for improving retention and engagement

This project turns raw data into actionable strategy — powered by clustering.

---

## Methods Used

- Data Cleaning and Preprocessing
- Feature Selection and Engineering
- **Standardization (Z-score)**
- **K-Means Clustering**
- Cluster Evaluation using:
  - Elbow Method (Inertia)
  - Silhouette Score
- Business Interpretation of Clusters

---

## Cluster Summary

| Cluster | Customer Type                      | Churn Risk | Recommended Action                               |
|---------|------------------------------------|------------|--------------------------------------------------|
| 0       | No Credit Card                     | Medium     | Offer entry-level credit card                    |
| 1       | High Balance, Low Products         | High       | Retain with wealth products, financial seminars  |
| 2       | Loyal, More Products               | Low        | Reward loyalty and upsell                        |
| 3       | Many Products Quickly, Short Tenure| High       | Onboard early, offer incentives to stay          |

---

## Recommendations for the Bank Manager

Based on the customer clusters identified, here’s what the bank can do:

- **Cluster 0 (No Credit Card):**  
  → Offer entry-level credit card products and personalize outreach using demographics.

- **Cluster 1 (High Balance, High Churn Risk):**  
  → Target with retention efforts like wealth management advisors or investment seminars.

- **Cluster 2 (Loyal, More Products):**  
  → Reward them with loyalty programs and encourage upselling additional services.

- **Cluster 3 (New, Many Products Quickly):**  
  → Onboard quickly and offer long-term product bundles to reduce churn.

These insights help match the **right campaign to the right customer segment**, improving engagement and reducing churn.

---

## Key Insights

- **Cluster 1** customers have high balances but are most at risk — they need proactive retention.
- **Cluster 2** are your loyal base — reward them and grow their value.
- Geographic differences also influence churn — e.g., more French customers in Cluster 2.


---

## Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn (StandardScaler, KMeans)
- Seaborn & Matplotlib
- Jupyter Notebook

---

## Author

**Md ShahNawaj**  
_Data Science enthusiast focused on real-world business impact._

---

Feel free to fork this repo, open issues, or suggest improvements!
