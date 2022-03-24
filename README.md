# Krutika_Portfolio
Data Science Portfolio
 - [Project 1: House Price Prediction - Machine learning project (Regression)](https://github.com/KrutikaDesai02/HousePricePrediction)
 - [Project 2: Sports Person Classifier - Machine learning project (Classification)](https://github.com/KrutikaDesai02/SportsPersonClassifier)
 - [Project 3: Sales Insights - Data Analyst project (Tableau)](https://github.com/KrutikaDesai02/SalesInsights)

# [Project 1: House Price Prediction: Project Overview](https://github.com/KrutikaDesai02/HousePricePrediction)
* Build a model that predict property price based on certain features such as bedroom, bathroom, sq feet, location etc. So, the task is to build a website using HTML/CSS/JavaScript that predicts estimated price for your house.
* In terms of project architecture, we are going to take a home set from Kaggle.com. Using that data set we will make a machine learning model. We are going to cover some data science concepts such as data cleaning, feature engineering, Dimensionality reduction, outliner detection etc.
* Before and after outliers removal: Rajali Nagar

 ![](/images/real1.png)
 
* Before and after outliers removal: Hebbal 

 ![](/images/real2.png)
 
* Histogaram after removing the outliers:

 ![](/images/real3.png)

* During model building we do GridSearchCV for hyperparameter tunning, k fold cross validation. For model building I used linear regression to achieve 84% accuracy.
* Once the model is built, we are going to export it to a pickle file and then we will write a python flask server which will consume this pickle file and do price prediction for us.
* This python flask server will expose HTTP endpoints for various requests and the UI written in HTML/CSS/JavaScript will make HTTP Get and Post calls.
* In terms of tools and technology we will use python as programming language, Pandas for data cleaning, Matplotlib for data visualization, Sklearn for model building, python flask for a back-end server, HTML/CSS/JavaScript for building our website.

 ![](/images/real4.png)

# [Project 2: Sports Person Classifier: Project Overview](https://github.com/KrutikaDesai02/SportsPersonClassifier)
* This is an end to end project on Image classification where our end goal is to build a website where you can drag and drop an image of a sport person and it will identify that sport person name.
* We have used Fatkun Chrome Tool to gather images and did data cleaning using Haar Cascade from OpenCV.

 ![](/images/virat1.png)
* We did feature eEngineering using Wavelet Transforms

 ![](/images/virat2.png)

* After cleaning the data tried support vector machine and tried couple of other models using GridSearchCV. Final ensembled model achieved SVM with linear kernel around 85% score.
*  Heat Map: 

 ![](/images/index.png)
 
* We will build a model first, hyper tune it, exported to a file, then we will run a python flask server and our website will make a call to that python flask server. 
* From our website we drop an image of Sport person to identify his/her name.

 ![](/images/virat5.png)

# [Project 3: Sales Insights: Project Overview](https://github.com/KrutikaDesai02/SalesInsights)
* Tableau is a BI and data analysis platform. It went on to become very popular because every corporate wanted to study its data in a short time frame and collaborate with the employees in the organization. Visualization is a great way to analyze a huge amount of data and that is exactly what Tableau does. Tableau has helped leading industries cut down their analysis time and make their business more data-driven while ensuring flexibility, security, and reliability.
* Our case study is based on a computer hardware business which is facing challenges in dynamically changing market, so we build Tableau dashboard that can give real time sales insights and based on that company can take their decision. we’ll go over project planning then we’ll build a dashboard in Tableau step by step.
* This Sales Insights project carries different steps :
    1. Problem Statement
    2. Data Discovery
    3. Data Analysis Using SQL
    4. Data Cleaning & ETL in Tableau
    5. Build Tableau Dashboard
    6. Feedback from Stakeholders & Profit Analysis
 
 * In our Star schema our transaction table comes in the middle, and it’s call fact table, rest of the tables are dimension tables

 ![](/images/1.png)
 
* Revenue By Markets

 ![](/images/2.png)
 
* Top 5 Customers

 ![](/images/3.png)
 
 * Revenue By Year

 ![](/images/4.png)
 
 * Tableau Dashboard

 ![](/images/5.png)


