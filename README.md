# Breast-Cancer-Prediction

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://breast-cancer-prediction.streamlit.app/)

The Breast Cancer Prediction App is a web application that allows users to predict whether a breast tumor is benign or malignant based on various tumor features. It is powered by an SVC (Support Vector Classifier) model trained on a breast cancer dataset.

## Prerequisites

Before you begin, you will need to have a few tools installed on your machine:

* Python 3.7 or higher.
    [Note: Streamlit only supports .py files as of now. So, notebook(.ipynb) files are not recommended]
* The scikit-learn, imblearn, numpy, pandas, streamlit packages among others.

#### Python

Python is the programming language used to develop this project. It is a popular high-level programming language known for its readability and versatility. It is widely used for web development, data analysis, and machine learning. It provides a powerful and flexible foundation for scraping and analyzing Twitter data.

#### Streamlit

Streamlit is a Python library that enables the creation of interactive and customizable web applications for data science and machine learning projects. In this project, we utilized Streamlit to develop an intuitive user interface for the Breast Cancer Prediction App, allowing users to input tumor feature values and receive predictions in a seamless and user-friendly manner.

#### Pandas

Pandas is a widely-used data manipulation library in Python that provides high-performance data structures and data analysis tools. In our project, Pandas was instrumental in handling and processing the breast cancer dataset, facilitating data exploration, manipulation, and integration.

#### scikit-learn

Scikit-learn is a comprehensive machine learning library in Python, providing a wide range of tools and algorithms for data preprocessing, modeling, and evaluation. In our project, we utilized scikit-learn's StandardScaler for feature scaling and Support Vector Classifier (SVC) for breast cancer prediction. The library's rich set of functionalities enabled us to build a robust and accurate predictive model.

#### imbalanced-learn (imblearn)

imblearn is a Python library for handling imbalanced datasets. It provides resampling techniques to address class imbalance. Used in our project to handle class imbalance in the breast cancer dataset.

#### matplotlib

Matplotlib is a Python plotting library. We used it to plot learning curves and validation curves, visualizing the model's performance and analyzing the bias-variance trade-off.

#### Joblib

Joblib is a library in Python used for efficiently storing and loading Python objects, including machine learning models. In our project, we employed Joblib to save and load the trained SVC model and StandardScaler object. This allowed us to persist the model and scaler between different app sessions, ensuring consistent and efficient predictions.

## Features

* ##### Predictive Analysis: The app utilizes an SVC model to predict whether a breast tumor is benign or malignant based on various tumor features.

* ##### User Input: Users can enter their own tumor feature values to generate personalized predictions. The app provides text input fields for each feature, allowing users to input their values.

* ##### Test Data Selection: Alternatively, users can choose from pre-defined test data, making it convenient to explore different scenarios and observe the predictions for specific tumor feature combinations.

* ##### Scalable Data: The app includes a data scaling function that standardizes the input data, ensuring that the features are on a similar scale for accurate predictions.

## User Guide

    1. Go to the web app URL in your web browser.
    2. Choose whether to enter your own values or select values from pre-defined test data.
    3. If entering your own values, input the tumor feature values in the provided text input fields. If selecting from test data, choose the values from the select boxes.
    4. Click the **Predict** button to generate predictions based on the provided input.
    5. The app will display the predicted tumor type (benign or malignant) along with a cautionary message emphasizing the need for professional medical advice.
    6. Feel free to explore different scenarios by modifying the input values or selecting different test data.

## Developer Guide

To run the app, follow these steps:

    1. Clone the repository to your local machine using the following command: git clone [https://github.com/Nirmal-Data-Scientist/Breast-Cancer-Prediction.git].
    2. Install the required libraries by running the following command: pip install -r requirements.txt.
    3. Open a terminal window and navigate to the directory where the app is located using the following command: cd [app_directory].
    4. Run the command [streamlit run app.py] to start the app.
    5. The app should now be running on a local server. If it doesn't start automatically, you can access it by going to either:
       - Local URL: [http://localhost:8501]
       - Network URL: [http://192.168.0.1:8501] (replace with your machine's IP address)

To modify the app, you can:

    1. Add additional tumor features to the input fields or test data selection.
    2. Enhance the visualizations by incorporating more interactive plots or statistical analysis.
    3. Implement additional machine learning models and compare their performance.
    4. Customize the app's styling and layout to match your preferences or branding.

## Potential Applications

1. Early Detection and Screening: The app can be used as a screening tool to assess the likelihood of breast tumors being benign or malignant. It can aid in early detection by providing quick and convenient predictions based on tumor features. This can potentially assist healthcare professionals in identifying high-risk cases and initiating timely interventions.

2. Patient Education and Empowerment: The app can serve as an educational resource for patients. By inputting their own tumor feature values or exploring pre-defined test data, individuals can gain insights into the factors that contribute to tumor classification. This knowledge empowers patients to understand the characteristics of their condition, facilitating more informed discussions with healthcare providers.

3. Research and Development: Researchers and scientists working in the field of breast cancer can utilize the app to explore different combinations of tumor features and observe the corresponding predictions. This can aid in the discovery of patterns, correlations, or potential risk factors associated with tumor malignancy. The app's interactive nature allows for quick experimentation and hypothesis testing, supporting ongoing research efforts.

## Potential issues with the app

1. Limited Scope: The app is based on a specific machine learning model (SVC) trained on a particular dataset. It may have limitations in accurately predicting tumor types for cases that deviate significantly from the training data. The model's performance may vary when applied to different populations or when dealing with rare or complex cases. It is essential to acknowledge that the app's predictions should be used as supportive information rather than a definitive diagnosis.

2. Reliance on Input Accuracy: The accuracy of the predictions heavily relies on the accuracy and completeness of the input data provided by the user. If incorrect or incomplete tumor feature values are entered, the predictions may be unreliable. Users must understand the importance of providing accurate and validated information for obtaining meaningful results. The app can include validation checks or guidelines to promote accurate data entry, but user diligence is still necessary.


## Web App Snap

![Screenshot (24)](https://github.com/Nirmal-Data-Scientist/Breast-Cancer-Prediction/assets/123751119/b2086243-fd04-44e8-a532-bbdeae7ec2b1)


## Web App Demo Video

<a href="https://www.linkedin.com/posts/nirmal-data-scientist_breastcancerawareness-machinelearning-healthcaretechnology-activity-7078127990617894912-7dUu?utm_source=share&utm_medium=member_desktop" target="_blank">Demo Video</a>

## Streamlit web URL

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://breast-cancer-prediction.streamlit.app/)

## Disclaimer

It is crucial to recognize that the app serves as a tool for preliminary assessment and should never replace professional medical advice or diagnosis. Users should consult healthcare professionals for a comprehensive evaluation and personalized treatment recommendations based on clinical examinations, diagnostic tests, and expert judgment.

## Contact

If you have any questions, comments, or suggestions for the app, please feel free to contact me at [nirmal.works@outlook.com]
