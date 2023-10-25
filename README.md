# SWIGGY RESTAURANT RECOMMEDATION MODEL 

## Introduction
the 'Swiggy Restaurant Recommendation Model,' simplifies decision-making by using data science and machine learning. It offers personalized restaurant suggestions to users based on their cuisine and location preferences. The process involves data scraping, cleaning, machine learning, and the creation of an interactive web app for an enhanced dining experience."

## 🍽️ Problem Aimed to Solve
In a world where dining preferences and choices are abundant, it can be challenging for individuals to decide where to eat. This project aims to address this problem by developing a Restaurant Recommendation Model. The goal is to provide users with personalized restaurant recommendations based on their cuisine preferences and location. To achieve this, the project involves collecting restaurant data from the Swiggy website, cleaning and preprocessing the data, building a machine learning model for price prediction, and creating an interactive web application for user-friendly recommendations.
## 📋 Project Overview
The project can be divided into several key components:
### 🌐 Data Extraction
-Using web scraping methods that involve Selenium and Beautiful Soup, we gather extensive details about restaurants from the Swiggy website. This information encompasses restaurant names, the types of cuisine they offer, their locations, user feedback, and the pricing details listed on their menus.

![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/590c81b7-98d3-4fb3-a599-de04b5219b23)
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/98e0488f-5fcb-4854-9d12-d62b3c1148f0)

### 🧹 Data Preprocessing
- Handling noisy data, null values, and duplicates to ensure data quality.
- Conducting outlier analysis to identify and address data points that could affect predictions.

  
### 📊 Insights and Visualizations
- Exploring and analyzing the collected data to gain insights into restaurant trends, popular cuisines, and price ranges.
- Creating visualizations to present these insights to users.
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/e4b4863a-12f1-497b-bca7-969a5e83665b)
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/366985ef-88f6-4997-85eb-4ff5a4e564b7)


### 🤖 Machine Learning Modeling
## Linear Regression Model for Price Prediction

- Building a Linear Regression Model to predict restaurant prices based on various factors, including cuisine, location, and user reviews.
- After scaling of numerical columns, Converting categorical columns into numerical values using One hot Encoding for model training.
  
-![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/ef7d1485-6690-4207-b2ec-b82cf69637a2)

- perfom PCA for dimentional reductions .
- ![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/3fdfca5b-6a35-4c3a-9bfc-d03bf03fddc0)
-![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/b66aafe3-3905-4cc0-9472-3b4feb096b7d)
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/045067b8-1076-4357-a296-638e3e04de6d)


## Random Forest classifier for Cusines Prediction
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/e1facb9d-de6c-4bde-9a0c-95a2345e668f)



### 🌐 Web Application
We developed an interactive web application using Flask.
It allowed users to input their preferences and received personalized restaurant recommendations.
We implemented user-friendly features for an enhanced dining experience.
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/413d0d0f-052e-4ead-93ff-950f8cf8362c)
![image](https://github.com/roshnipatidar/swiggy_recommendation_model/assets/143728620/aea774f0-b134-43e0-af51-5ad9969042d3)


### 🚧 Challenges and Learnings
 #### Web Scraping Challenges:
Data Retrieval Hurdles

Web Page Structure Volatility

#### Machine Learning Model Selection Challenges:
Model Complexity Dilemma

The Data Predicament: Quantity and Quality

#### Web Page-Related Challenges:
Dynamic Content Handling

Navigating HTML Variability


  
### 🚀 Future Scope
- Exploring opportunities for real-time updates in menu prices and user preferences.
- Enhancing the recommendation model with advanced machine learning algorithms.
- Improving the transparency and interpretability of restaurant recommendations.

  
## 📈 Insights
Exploratory Data Analysis (EDA) and visualizations play a significant role in understanding restaurant data. Some key insights include:
- Pan asian  emerge as the highest average price for one  popular cuisines among users, followed by Japanese and Pastas.
- The analysis also reveals that North Indian and chinese cuisine tends to be the most popular, followed by south indian.
  

## 📝 Conclusion
Our project has delivered a comprehensive restaurant recommendation model for prospective restaurateurs in Bangalore. It provides insights into popular cuisines, average prices, and top restaurants in chosen areas. Moreover, it offers pricing suggestions and recommends suitable locations based on user preferences. This model is a valuable asset for those entering the restaurant business, guiding them toward well-informed decisions and increased chances of success in the vibrant Bangalore restaurant scene.



