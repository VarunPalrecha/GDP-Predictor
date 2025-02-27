# GDP Prediction using Linear Regression

Overview

This project builds a Linear Regression Model to predict GDP based on three key economic indicators:

Exchange Rate

Inflation Rate

Repo Rate

The dataset contains quarterly GDP and other economic variables, which are reshaped and used to train the model.

Features

Reads economic data from a CSV file

Converts quarterly data into a long format for better analysis

Splits data into training and testing sets

Trains a Linear Regression Model

Calculates Mean Squared Error (MSE) for performance evaluation

Provides an interactive prompt for GDP prediction based on user input

Installation

Clone the repository:

git clone https://github.com/VarunPalrecha/GDP-Predictor

Navigate to the project directory:

cd gdp-prediction

Install required dependencies:

pip install pandas numpy scikit-learn

Usage

Ensure your dataset (FinalData_1.xlsx) is available in the specified path.

Run the script:

python gdp_prediction.py

The script will:

Train the model

Print the Mean Squared Error

Ask for user input to predict GDP

File Structure

📂 gdp-prediction
├── 📄 gdp_prediction.py  # Main script
├── 📄 FinalData_1.xlsx           # Input dataset (replace with your data)
├── 📄 README.md          # Project documentation

Example Input/Output

Enter the following values for GDP prediction:
Exchange Rate: 0.5
Inflation Rate: 6
Repo Rate: 3.5

Predicted GDP: 5.24

Model Evaluation

The model's accuracy is measured using Mean Squared Error (MSE). Lower MSE values indicate better predictions.

Future Improvements

Handle missing values before training

Normalize data for improved accuracy

Add more economic factors to enhance predictions

Implement a web-based interface for easy access

License

This project is licensed under the MIT License.

Author

Varun Palrecha
