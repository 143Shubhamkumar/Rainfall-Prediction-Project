# Rainfall-Prediction-Project
Rainfall Prediction Project
This project contains a Jupyter Notebook that demonstrates a simple machine learning model to predict rainfall. The model is built using a linear regression algorithm and is trained on weather data.

Project Description
The purpose of this project is to build and evaluate a rainfall prediction model. It uses historical weather data to predict precipitation based on several key features.

Key Features
Data Source: The model uses a dataset from an austin_weather.csv file.

Model: A LinearRegression model from the scikit-learn library is used for the prediction.

Evaluation Metrics: The model's performance is evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

Visualizations: The notebook includes plots to visualize the actual versus predicted rainfall and a residual plot.

Dependencies
To run this notebook, you need to install the following Python libraries:

pandas

numpy

scikit-learn

matplotlib

You can install these dependencies using pip:

pip install pandas numpy scikit-learn matplotlib
How to Run the Notebook
Make sure you have all the dependencies installed.

Place the austin_weather.csv file in the same directory as the Rainfall_Prediction.ipynb notebook.

Open the Rainfall_Prediction.ipynb file in a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, or Google Colab).

Run the cells in the notebook sequentially to train the model and see the results.

Model Results
The following are the results from the model evaluation:

Mean Squared Error (MSE): 0.0497

Root Mean Squared Error (RMSE): 0.2230

R-squared (R2): 0.1662

These metrics indicate the model's performance on the test data, with a low R-squared value suggesting that the selected features do not strongly correlate with rainfall.
