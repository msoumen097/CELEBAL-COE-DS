## Loan Approval Prediction Web Application
This is a Flask-based web application that predicts loan approval status based on user input. The application uses a pre-trained machine learning model to make predictions and provides a simple web interface for users to interact with.

## Features
User Input: The application collects data on various features like gender, marital status, income, loan amount, etc., through a web form.
Prediction: Based on the user input, the application predicts whether a loan will be approved or not.
Model: The prediction is made using a machine learning model trained on historical loan data.
Getting Started
Prerequisites
Python 3.x
Flask
Scikit-learn (for loading the model)
HTML/CSS knowledge for front-end customization

Running the Application
Start the Flask application:

bash
Copy code
python app.py
Open a web browser and go to http://127.0.0.1:5000/.

Input the required details on the form and click "Predict" to see the loan approval status.

## Model Information
The model is a machine learning algorithm trained to predict loan approval status based on features such as:
Gender
Marital Status
Number of Dependents
Education Level
Employment Status
Credit History
Property Area
Applicant and Co-applicant Income
Loan Amount and Loan Term
The model file (model.pkl) must be present in the project directory.
Deployment on Azure
To deploy this application on Azure:

## Create an Azure Web App:
1) Navigate to Azure Portal:
2) Log in to the Azure Portal.
3) Create a New Resource:
4) Search for "App Service" and create a new App Service.
5) Choose the Subscription, Resource Group, and Name your Web App.
6) Select the Runtime Stack (Python version).
7) Choose a Region close to your users.
8) Review and Create.
9) Set Pricing Tier:
![1](./images_/a1.png)
Under Plan, click on Create new.
App Service Plan: Choose the Free (F1) tier.
Click Apply and then Review + create.

![2](./images_/s1.png)
## Go to the Azure Portal.
Create a new Web App and choose the appropriate configuration for your Flask application.
Deploy your application:
.images_/Screenshot 2024-08-17 174346 1.png
Use Azure CLI, GitHub Actions, or any other deployment method to push your code to the Azure Web App.
## Configure Environment Variables:
![3](./images_/s2.png)
Ensure all necessary environment variables and configurations are set up in Azure.
## Access your web application:

After successful deployment, you can access your application via the Azure Web App URL.
