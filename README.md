# Product Recommendation System and Anamoly Detection Analysis
This project focuses on developing a robust product recommendation system utilizing various unsupervised learning techniques. The system aims to enhance user experience on e-commerce platforms by providing personalized product suggestions based on user behavior and preferences.

### Dataset:

The dataset, named 'sample30', is sourced from Kaggle and contains over 30,000 rows of product reviews and ratings across multiple categories and brands.
Key columns include user_id, product_id, reviews_rating, reviews_text, and user_sentiment.

## Unsupervised Learning Techniques Applied:

#### Clustering: Techniques used: KMeans, DBSCAN, and t-SNE.
KMeans was employed to identify clusters of similar products, while DBSCAN helped refine these clusters by identifying noise and outliers.
#### Topic Modeling:
Methods used Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF).These techniques were used to extract underlying themes from the reviews, providing insights into customer sentiments and product features.
#### Anomaly Analysis and Detection: 
Various models, including Isolation Forest and One-Class SVM, were utilized to identify unusual or fraudulent reviews.
#### Recommendation System:
Two methods were implemented:

   1. Cosine Similarity with TF-IDF: This method used user and product encoding to recommend similar products based on user interactions.
      
   2. Graph-Based Approach: Leveraging Word2Vec for category embeddings to recommend products based on graph nodes.

## Results and Insights:

#### Clustering Results:

The optimal number of clusters was determined to be three using the Elbow Method.
t-SNE provided better visualization of clusters, revealing distinct groupings based on product reviews.

#### Topic Modeling Insights:

LDA and NMF identified key topics related to cleaning products, movies, and beauty items, helping to categorize customer sentiments effectively.

#### Anomaly Detection Findings:

A significant number of anomalous reviews were identified, indicating potential fraudulent activity, which was crucial for maintaining the integrity of the recommendation system.

#### Recommendation System Performance:

The system successfully provided personalized product recommendations, enhancing user engagement and satisfaction.


## Streamlit
A simple Streamlit app template for you to modify!

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
