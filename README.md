![image](https://github.com/Golnaz-spa/ML_predict_webapp/assets/93345507/6618de28-1c7d-4a99-b07c-17dcaa185158)# Diabetes Prediction Web App

## About

Welcome to the Diabetes Prediction Web App project. In this project, we have deployed a public machine learning web app using Streamlit. The main objective of this web app is to provide users with an intuitive interface to interact with a Support Vector Machine (SVM) classifier model. The model's purpose is to predict whether a person, with specific features, is likely to have Diabetes or not.

**Web App Link**: [Diabetes Prediction Web App](https://mlpredictwebapp-s9pidwfz5c7rl9rzgbybdq.streamlit.app/)

The web app allows users to input various health-related features, and the SVM model processes the data to make a Diabetes prediction.

## Model Details

The machine learning model used in this project is an SVM classifier. It is trained on a labeled dataset to predict the likelihood of a person having Diabetes. 
The model is saved as a binary file named `model.sav`.

## Project Structure

The project is organized as follows:

- `mdps_public.py`: This Python script contains the Streamlit code that powers the web app.
- `diabetes_model.sav`: The pre-trained SVM classifier model saved as a binary file.
- `requirements.txt`: This file lists all the necessary libraries and their versions for easy setup.
- `web_app_screenshot.png`: A screenshot of the web app for reference.

## Installation and Usage

To run this project on your local machine, follow these steps:

### Prerequisites

- Python 3.x
- Install the required libraries from `requirements.txt`:

```bash
pip install -r requirements.txt


