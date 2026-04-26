# Clustering Countries for Humanitarian Aid

**Final Project – Sanbercode Data Science Bootcamp**

## 📌 Project Overview

This project aims to cluster countries based on key socioeconomic indicators to help prioritize and allocate humanitarian aid effectively. By using unsupervised learning techniques, specifically K-Means clustering, we identify patterns and group countries with similar conditions.

## 🎯 Objectives

* Analyze the relationship between income and child mortality
* Identify clusters of countries with similar socioeconomic conditions
* Provide insights to support humanitarian aid distribution

## 📊 Dataset

The dataset contains various socioeconomic indicators such as:

* Income
* Child mortality rate
* Other supporting features (if applicable)

## ⚙️ Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Outlier removal using IQR method
   * Feature selection

2. **Data Transformation**

   * Standardization using scaling techniques

3. **Modeling**

   * K-Means clustering with k=3
   * Evaluation based on cluster distribution

4. **Visualization**

   * Scatter plot of Income vs Child Mortality
   * Cluster visualization with centroids

## 📈 Results & Insights

* Countries are grouped into 3 clusters based on their socioeconomic conditions
* Clear separation observed between high-income/low-mortality and low-income/high-mortality groups
* Clusters can be used to prioritize aid allocation strategies

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script

## 📌 Conclusion

This project demonstrates how clustering techniques can be applied to real-world problems such as humanitarian aid distribution. The insights generated can support decision-making in identifying which countries may need more attention and resources.

## 📬 Contact

Feel free to reach out for collaboration or discussion!
