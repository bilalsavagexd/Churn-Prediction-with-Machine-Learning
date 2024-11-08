<h1 align="center">Churn-Prediction-with-Machine-Learning</h1>

Welcome to the Churn Prediction App! This app is designed to predict customer churn using various machine learning models. It is built with Python, Streamlit, and various libraries like Scikit-Learn, Pandas, and XGBoost. The app enables users to visualize and predict the likelihood of customers leaving based on historical data.

The app is deployed and accessible online: [Churn Predictor](https://churn-prediction-with-machine-learning.streamlit.app/)

## Features

- Data Visualization: Interactive charts and visualizations to explore customer data.

- Model Comparisons: Multiple machine learning models (XGBoost, Random Forest, KNN, etc.) are compared for accuracy and performance.

- Real-Time Predictions: Make churn predictions based on new or existing customer data.

- Interactive User Interface: A simple and sleek user interface built with Streamlit for ease of use.

## Technologies Used

- Streamlit: For building the web app interface.

- Scikit-learn: For machine learning algorithms.

- Pandas: For data manipulation and analysis.

- Plotly: For data visualization.

- XGBoost: For advanced gradient boosting models.

This app leverages the **Groq API** to enhance inference speed and efficiency. The models were pre-trained using traditional machine learning libraries like Scikit-Learn and XGBoost, but for deploying and running predictions at scale, the Groq API provides acceleration and optimized performance. This integration ensures fast real-time predictions, making the app suitable for larger datasets and production environments.


## Getting Started

To run the app locally, follow these steps:

### Starting the Server

1. ``` git clone https://github.com/bilalsavagexd/Churn-Prediction-with-Machine-Learning.git ```

2. ``` cd Churn-Prediction-with-Machine-Learning ```

3. ``` python3 -m venv venv ```

4. ``` source venv/bin/activate (MacOS) ```

5. ``` venv\Scripts\activate (Windows Powershell) ```

6. ``` pip install -r requirements.txt ```

### Starting the App
```
streamlit run streamlit_app.py
```
## Sneak Peak
![image](https://github.com/bilalsavagexd/Churn-Prediction-with-Machine-Learning/raw/main/Images/churn_predictior.png)
