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


