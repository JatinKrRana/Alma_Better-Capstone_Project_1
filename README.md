# AlmaBetter-Capstone_Project

# Zomato Restaurant Clustering And Sentiment Analysis

![zomato-infinity-dining-916x516-1](https://github.com/user-attachments/assets/f49e3216-181e-4975-9503-a7adbc78a41a)

**Introduction:**

The Zomato Restaurant Clustering and Sentiment Analysis project aim to leverage unsupervised machine learning techniques to extract valuable insights from the vast amount of user-generated data on the Zomato platform. Zomato, a popular online restaurant discovery and food delivery platform, accumulates a diverse set of reviews and ratings from users worldwide. The primary objectives of this project are to cluster restaurants based on various features and perform sentiment analysis on user reviews, providing a comprehensive understanding of the dining landscape.

**Data Collection and Preprocessing:**

The first step involves gathering data from the Zomato API, which provides detailed information about restaurants, including their location, cuisine, cost, user ratings, and reviews. The data undergoes thorough exploratory analysis to identify shape, variables descriptions, missing values, duplicates, relationship and correlation among variables. Then the data undergoes preprocessing to handle missing values, remove duplicatas, and convert categorical variables into a suitable format for analysis. Additionally, text data preprocessing techniques such as tokenization, stemming, and removal of stop words are applied to enhance the quality of textual information.

![download (3)](https://github.com/user-attachments/assets/ca534579-5828-4424-84f9-4e7b1e83b95d)
![download (5)](https://github.com/user-attachments/assets/9c4ca6fb-bfec-404b-9c6c-7f6a1f8a02ce)
![download (6)](https://github.com/user-attachments/assets/30c2d1ba-3019-4f62-ba09-203ed516db75)
![download (7)](https://github.com/user-attachments/assets/33bc1ac6-d119-469b-b814-ce93dfcc8484)
![download (8)](https://github.com/user-attachments/assets/a8929f83-70fb-4ae0-8928-0b6c629d6e0c)
![download (10)](https://github.com/user-attachments/assets/43f2729f-cbef-42ad-b8cc-d47577fda558)
![download (12)](https://github.com/user-attachments/assets/fec14fd8-b9f2-439f-abee-2dbfa63876b0)
![download (13)](https://github.com/user-attachments/assets/571a1ee7-edaa-4c30-a9ab-6b5693f50f33)


**Feature Engineering:**

To facilitate clustering, relevant features are selected, including restaurant location, cuisine type, cost, and average user ratings. Additionally, text-based features such as sentiment scores extracted from reviews are incorporated. Feature scaling and normalization are performed to ensure that all features contribute equally to the clustering process.

**Clustering Analysis:**

Unsupervised machine learning algorithms like k-means clustering are applied to group restaurants with similar characteristics into distinct clusters. The optimal number of clusters is determined using techniques like the elbow method. The resulting clusters provide insights into the diverse culinary landscape, enabling users and businesses to identify patterns and trends within the restaurant data.

![download (16)](https://github.com/user-attachments/assets/9a293f14-0f0c-4252-b5f0-9b0b7f0db583)
![download (15)](https://github.com/user-attachments/assets/6cb4c5d7-8fc8-456e-a0bd-65aa2843dbdd)
![download (17)](https://github.com/user-attachments/assets/5e757938-1283-4bdf-8a30-24005818a2c8)


**Sentiment Analysis:**

Sentiment analysis is conducted on user reviews to assess the overall sentiment associated with each restaurant. Natural Language Processing (NLP) techniques, such as the use of sentiment lexicons or machine learning models like Support Vector Machines (SVM) or recurrent neural networks (RNN), are employed to classify reviews as positive, negative, or neutral. This analysis offers valuable information about customer satisfaction and the factors influencing their opinions.

![Screenshot 2024-08-25 203249](https://github.com/user-attachments/assets/c92f4e90-8e8d-447a-9ccc-ee2801eae3b0)

**Insights and Recommendations:**

The project concludes with the extraction of actionable insights and recommendations for Zomato users, restaurant owners, and the platform itself. Users can benefit from discovering new restaurants within specific clusters that match their preferences. Restaurant owners can gain insights into the factors influencing customer satisfaction and adjust their strategies accordingly. Zomato can utilize the findings to enhance user experience, improve recommendation algorithms, and refine the overall platform.

In conclusion, the Zomato Restaurant Clustering and Sentiment Analysis project harnesses the power of unsupervised machine learning to uncover meaningful patterns in restaurant data. By clustering restaurants and analyzing user sentiments, the project delivers valuable insights that can enhance the dining experience for both users and restaurant owners, contributing to the continual improvement of the Zomato platform.
