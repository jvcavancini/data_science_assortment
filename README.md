**Project Title:** Data-Driven Product Recommendation System using Market Sales Data

**Description:**

This repository contains the final project for the **Data Science** course (COPxxxx - *[Insert Course Code if known]*) within the **Computer Science Master's program at UFRJ (Universidade Federal do Rio de Janeiro)**.

The objective of this project was to develop a **dynamic product recommendation pipeline** for a retail store based on historical market sales data.

### Key Contributions & Methods:

* **Feature Engineering:** Calculated core performance metrics (Total Revenue, Volume, Frequency) and implemented **Price Segmentation** (Low, Medium, High) relative to product categories.
* **Optimal K Determination (AI-driven Insight):** Employed a **Marginal Gain Analysis (Pareto Principle)** to dynamically determine the optimal number ($K$) of top-performing products to recommend per category, based on revenue contribution.
* **Recommendation Algorithm:** Developed a hybrid filtering mechanism that prioritizes products based on a **Weighted Performance Score** while explicitly guaranteeing **variety in price segments** (Low/Medium/High) within the final recommendation list.

**Technologies:** Python, Pandas, NumPy, Scikit-learn (for K-Means/Normalization), Matplotlib/Seaborn.
