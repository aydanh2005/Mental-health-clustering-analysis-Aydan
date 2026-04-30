# Mental Health Clustering Project

---

## Project Overview

This project applies unsupervised machine learning techniques to the OSMI Mental Health in Tech Survey (2016) dataset.

The objective is to identify hidden patterns among respondents using demographic and workplace mental health variables.

---

## Dataset

OSMI Mental Health in Tech Survey (2016)

Source: [Kaggle Dataset - Mental Health in Tech 2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)

The dataset contains survey responses related to:
- Age
- Gender
- Country
- Mental health treatment history
- Company size
- Workplace attitudes toward mental health

---

## Methods Used

- Data Cleaning
- Missing Value Handling
- Label Encoding
- Feature Scaling
- KMeans Clustering
- Elbow Method
- PCA (Principal Component Analysis)

---

## Key Results

- The dataset was segmented into four clusters.
- The elbow method supported the selection of k = 4.
- PCA was used to visualize the cluster structure.
- The four clusters showed different employee profiles:
- Cluster 0: Younger employees, average age approximately 31.6 years, usually from smaller companies, with higher treatment history.
- Cluster 1: Mid-age employees, average age approximately 34.3 years, usually from larger companies, with lower treatment history.
- Cluster 2: Younger employees, average age approximately 32.5 years, mainly from the smallest companies, with limited treatment engagement.
- Cluster 3: Older employees, average age approximately 38.2 years, usually from the largest companies, with the highest treatment history.
- Meaningful differences were observed across demographic and workplace-related variables.

---

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## How to Run

1. Open the notebook file in Google Colab or Jupyter Notebook  
2. Run all cells step by step  
3. Review clustering outputs and PCA visualization

---

## Repository Contents

- Final project notebook (.ipynb)
- README.md

---

## Author

Aydan Huseynli

Created for the IU module:  
**Machine Learning - Unsupervised Learning and Feature Engineering**
