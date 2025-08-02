<p align = "center">
  <img src = "https://github.com/user-attachments/assets/a5941b2b-8e9f-434f-9002-04ee8dc2df37" alt = "NASA headshot" width = "300"/>
</p>

## About Me
**Tessa Volpe**  
Simmons University  
*Bachelors of Science in Data Science and Analytics, anticipated May 2026*  

I am a Data Science & Analytics student at Simmons University who is interested in how data can be used to better understand people, systems, and decisions. I enjoy working with real-world datasets, building clean visualizations, and exploring how data can drive meaningful impact, especially in areas like healthcare, sports, and education.
I am currently a NASA JSC Summer Intern and Fellow with MIT's Break Through Tech AI program. I am still early in my career and am eager to continue learning from coursework, hands-on projects, and the people around me. I care about asking good questions, communicating clearly, and doing work that’s thoughtful and useful.

## Connect with Me
- [LinkedIn](https://www.linkedin.com/in/tessa-volpe11/)
- Email: Tessa.Volpe@Simmons.edu

# MIT-Break-Through-Tech-AI Project Portfolio
This repository contains projects I completed through my fellowship with Break Through Tech AI at MIT Schwartzman College of Computing

## Fall AI Studio Project placeholder

## Random Forest Model: Airbnb Review Score Prediction
Trained linear regression and random forest models to predict the continuous `review_scores_value` for Airbnb listings based on selected host and listing features.

Trained linear regression model saved using pickle (linear_regression_model.pkl)
- Predicts review_scores_value using key features like accommodates, minimum_nights, availability_365, and host attributes.

Trained random forest regressor saved using pickle (random_forest_model.pkl)
- Provides improved prediction performance by capturing nonlinear relationships in the data.

Cleaned and preprocessed Airbnb dataset with selected features (airbnb_data_cleaned.csv )
- calculated_host_listings_count, accommodates, minimum_nights, availability_365, host_is_superhost, instant_bookable. Missing values handled, categorical variables encoded, and ready for modeling.

## Logistic Regression Model: Airbnb Superhost Prediction
Trained logistic regression model and corresponding dataset used to predict whether an Airbnb is labeled a **Superhost**

Trained logistic regression model saved using pickle (ModelSelectionForLogisticRegression.pkl)
- This model can be reloaded and used for prediction using the same top features it was trained on.

Preprocessed Airbnb training data (airbnbData_train.csv)
- Includes one-hot encoding, scaled numeric features, and no missing values.
