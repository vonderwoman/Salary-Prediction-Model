# Salary-Prediction-Model
![image](https://pianalytix.com/wp-content/uploads/2020/12/Salary-Prediction-Model-using-ML.jpg)

# Salary Prediction Model README

This README provides an overview of the Salary Prediction Model project, including the dataset, objectives, associated tasks, and deployment instructions using Streamlit.

## Table of Contents

- [Background](#background)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Dataset](#dataset)
- [Objectives and Aims](#objectives-and-aims)
- [Associated Tasks](#associated-tasks)
- [Deployment](#deployment)

## Background

In this project, we aim to develop a machine learning model that predicts the salary of software engineers based on certain factors. The model takes into account the software engineer's country, education level, and years of professional coding experience as input and provides an estimate of their salary as the output.

## Key Performance Indicators (KPIs)

The key performance indicator for this project is the accuracy of the salary predictions made by the machine learning model. We will evaluate the model's performance using regression evaluation metrics such as mean squared error (MSE)

## Dataset

The dataset used for this project is the publicly available Stack Overflow Developer Survey dataset. It contains information collected from thousands of software developers, including their demographics, education level, professional experience, and salary details. The dataset is provided in a CSV file format named `survey_results_public.csv`.

## Objectives and Aims

The main objectives of this project are as follows:

1. Develop a machine learning model to predict the salary of software engineers based on their country, education level, and years of professional coding experience.
2. Evaluate and optimize the model's performance using appropriate regression evaluation metrics.
3. Provide a user-friendly interface for users to input their information and obtain salary predictions.

## Associated Tasks

The project involves the following tasks:

1. Data preprocessing:
   - Handle missing values in the dataset.
   - Convert categorical variables, such as "Country" and "EdLevel," into numerical representations suitable for machine learning models.

2. Feature selection:
   - Identify and select the relevant features for salary prediction: "Country," "EdLevel," and "YearsCodePro."

3. Model training and evaluation:
   - Train a regression model using the selected features and salary data.
   - Evaluate the model's performance using regression evaluation metrics such as MSE, MAE, and R-squared score.

4. Model improvement:
   - Experiment with different regression algorithms and hyperparameter tuning techniques to optimize the model's performance.
   - Consider feature engineering methods to capture potential non-linear relationships between the input features and salary.

5. Deployment:
   - Deploy the trained model using Streamlit, a Python library for building interactive web applications.
   - Create a user interface where users can input their country, education level, and years of professional coding experience to obtain salary predictions.

## Deployment

To deploy and use the salary prediction application, follow these steps:

- Clone the project repository to your local machine.

 - Execute the application by running the following command:
            streamlit run app.py

  - After running the streamlit run app.py command, Streamlit will start a local web server and provide a URL.
        
   - Open your preferred web browser and enter the provided URL in the address bar.
   - This will navigate you to the Streamlit application's interface.

   - Enter your country, education level, and years of professional coding experience in the respective input fields.
   
        On the Streamlit application interface, you will find input fields for entering your information.
        Locate the input fields labeled "Country," "Education Level," and "Years of Professional Coding Experience."
        Enter your information in these fields based on your current circumstances.
        Ensure that you provide accurate and relevant data to obtain more accurate salary predictions.

  - Click the "Predict Salary" button to obtain the predicted salary based on your inputs.
        Once you have entered your information in the respective input fields, locate the "Predict Salary" button.
        Click the button to initiate the salary prediction process.
        The machine learning model will use the provided inputs to calculate and display an estimated salary based on the trained model's          predictions.
        
  ## App deployed on Streamlit

![Streamlit GIF](assests/app%20%C2%B7%20Streamlit%20%E2%80%94%20Mozilla%20Firefox%202023-05-11%2022-14-36.mp4)

