# Customer Inquiry Categorization using NLP & Machine Learning


### Project Overview

This project focuses on automating customer inquiry categorization in the banking industry using Natural Language Processing (NLP) and Machine Learning. By leveraging SBERT embeddings, clustering (DBSCAN), and classification models (XGBoost, DNN, SVM, etc.), we aim to improve customer support efficiency, reduce manual effort, and provide actionable insights.

---

### Key Features

- **Text Preprocessing:** Removed stopwords, punctuation, HTML tags, and lemmatized text for cleaner embeddings.
- **SBERT Embeddings (384D):** Converted customer inquiries into numerical representations for analysis.
- **Unsupervised Clustering (DBSCAN + UMAP):** Identified 7 major topics by reducing dimensions and clustering inquiries.
- **Supervised Classification Models:** Trained and evaluated XGBoost, CatBoost, DNN, SVM, Logistic Regression, Random Forest, etc.
- **Model Performance Evaluation:** Compared models using accuracy, precision, recall, and F1-score.

---

## Project Structure

📁 Customer_Inquiry_Categorization  
│── 📂 data/                # Raw and processed datasets  
│── 📂 codes/               # Jupyter notebooks for EDA, clustering, and modeling  
│── 📂 models/              # Saved trained models (XGBoost, DNN, etc.)  
│── 📂 images/              # visualizations, and insights    
│── 📄 README.md            # Project documentation 

---
# Model Performance Summary

| Model / Score | Accuracy | Precision | Recall | F1 |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression | 0.9916 | 0.9891 | 0.9891 | 0.9891 |
| SVC | 0.9935 | 0.9914 | 0.9913 | 0.9914 |
| Random Forest | 0.9814 | 0.9750 | 0.9782 | 0.9757|
| LightGBM | 0.9874 | 0.9851 | 0.9850 | 0.9847 |
| XGBoost | 0.9818 | 0.9817 | 0.9818 | 0.9813 |
| CatBoost | 0.9850 | 0.9856 | 0.9855 | 0.9853 |
| MLP| 0.9895 | 0.9894 | 0.9895 | 0.9894 |
| DNN| 0.9859 | 0.9861 | 0.9859 | 0.9858 |



