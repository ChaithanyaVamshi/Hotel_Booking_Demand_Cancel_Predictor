
# Predicting Hotel Booking Demand Analysis and Booking Cancellations Using Machine Learning with Python

![image](https://user-images.githubusercontent.com/31254745/150643459-43963186-0349-4f1c-abdf-fde59eb0b28d.png)


In this project, I have built an end-end Industry oriented and real-world Data-driven Machine
learning project in the Hotel Industry (Hospitality) using AGILE CRISP-DM Methodology right
from understanding the Business problem to the Model deployment of Web Application on
Heroku Cloud using Python and Streamlit.

I have also applied advanced Machine learning techniques like Ensemble Learning Techniques
and Evaluation metrics to maximize Revenue and Optimize business performance like
Inventory Management, Dynamic Pricing, Distribution and Overbooking strategies in the
Hotel Industry.




## Project Motivation
<img align="right" alt="GIF" src="https://user-images.githubusercontent.com/31254745/150643490-2f065715-85a4-4252-bc54-eb82bc6f65a4.png" width="300" height="230" />

My motivation for this project is to solve various business problems faced by the Hotel
Industry by making a Scalable and robust Data Science Proof of Concept (POC) product that
can be accessed by the Business User or a Customer to generate business value.

Using Machine learning techniques, we can predict the guests who are likely to cancel the
reservation at the Hotels and predict the price of hotel booking which is expected to increase
or decrease in the future leading to booking now or waiting for a better offer/discount. Hence
this will create a surplus revenue, better forecasts and reduce uncertainty in business
management decisions to both the hotels and hotel technology firms.

In particular, I wanted to document the entire machine learning workflow implemented in
this project and apply that workflow in the hotel industry


## Machine Learning Project Life Cyle
<img align="right" alt="GIF" src="https://user-images.githubusercontent.com/31254745/150643661-87437220-ffe6-44cc-84f1-d6c905815147.png" width="300" height="230" />

  1. Business Understanding
  2. Data Collection and Understanding
  3. Data Exploration
  4. Data Preparation
  5. Modelling
  6. Model Evaluation
  7. Model Deployment


## Project Skills and Tools 

**Project Tools:** Python, Matplotlib, Seaborn, Plotly, Pandas, NumPy, Scikit-Learn, Google Colab 

**Project Skills:** Analytical Skills, Business Understanding, Data Visualization, Exploratory Data Analysis, Machine Learning, Problem Solving, Project Documentation 


## 1. Understanding Business Problem

I have implemented a combination of both Supervised Machine learning algorithms and
Unsupervised learning Algorithms to solve three business problems faced by the Hotel
Industry.

**Supervised Machine Learning**

• **Regression:** Predicting the Cost/Price of a Hotel Booking made by the Hotel
Guest/Customer

• **Classification:** Predicting whether the Hotel Booking made by the Guest/Customer will
be Cancelled or not?

**Unsupervised Machine Learning**

• **Clustering:** Identifying Profitable Customers/Guests by Customer Market
Segmentation

## 2. Data Collection and Understanding

I have selected a data set containing hotel booking information that was
uploaded to Kaggle, an online community of data scientists, by user Jesse Mostipak.

This dataset is available at Kaggle in the link: https://www.kaggle.com/jessemostipak/hotel-booking-demand

## 3. Data Exploration

In this step, I have applied Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Cancellations by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn. It is always a good practice to understand the data first and try to gather as many insights from it.

**Steps to Perform in Data Exploration**

1. Understanding the Dataset and Shape (Rows & Columns)
2. Checking Data Types of the Attributes
3. Exploring Categorical Attributes
4. Exploring Numerical Attributes
5. Checking Statistical Summary of the dataset - Descriptive Statistics
6. Checking Missing Values (Nan) in Dataset
7. Checking Distribution of Target Attribute
8. Checking Skewness of Attributes - Inferential Statistics
9. Data Visualization of Important Attributes

## 4. Data Preparation
After exploring the dataset, we will find a lot of information that will help you prepare the data. Most important steps in Data Preparation are:

1. Handling Missing Values in the dataset
2. Feature Encoding Categorial Attributes
3. Handling Skewness of Attributes
4. Correlation between Independent and Dependent features
5. Removing Irrelevant Attributes

## 5. Modeling

1. Algorithm Selection
2. Train - Test Split
3. Model Fitting
4. Models Accuracy Scores on Train and Test Data
5. Hyperparameter Tuning using Grid Search CV on all models
6. Applying Stratified Kfold Cross-Validation to know the exact Mean CV Accuracy Score

## 6. Model Deployment

After building a model and evaluating it, the final stage of the machine learning lifecycle is to
deploy the ML model. A Machine Learning model is not particularly useful unless the
customer can access its results.

To build the Web Application, I will use the 10 most important features that help predict the
Hotel Booking Cancelation from the guests since it would be a pain for a front-end user to fill
all 23 features on the web app.

Once the training is completed, we need to expose the trained model as an API for the user
to consume it. For prediction, the saved pickle file and model is loaded first and then the
predictions are made using it.

I have deployed Machine Learning Model on Heroku Cloud using Python and Streamlit. Once we have
deployed it on the cloud, we have successfully built a Data Science product that can be used by the
Business User/ Customer.

**Link to the ML Web App:** https://cancelation-predictor.herokuapp.com/

**Link to ML Web App Demo Video:** https://www.youtube.com/embed/aP_RoSbcxGA



## Appendix

Kaggle Dataset: https://www.kaggle.com/jessemostipak/hotel-booking-demand

ML Classification Python Code:
https://colab.research.google.com/drive/1pW6WcYp58pkBE4A2vVfFs0tDhDYZQuKr?usp=sharing

ML Clustering Python Code:
https://colab.research.google.com/drive/1V7AlYbHw2SLsbhLY0agkcjmHra4TJKBx?usp=sharing

ML Regression Python Code:
https://colab.research.google.com/drive/1gx51aappEKYJ6Rn7n7kZB_QeeJkGccJ_?usp=sharing

ML Web App: https://cancelation-predictor.herokuapp.com/

ML Web App Demo Video: https://www.youtube.com/embed/aP_RoSbcxGA

